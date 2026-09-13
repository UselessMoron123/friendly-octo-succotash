# Character ID audit & fixes

Full audit of all `characters/*.txt` (37,700 blocks after fixes): every `father=`, `mother=`,
`add_spouse=`, `remove_spouse=`, `employer=`, `killer=`, `add/respectively remove_friend/rival/lover/consort`
reference was checked against all defined character IDs, plus a parent/child date-sanity scan.

Result before fixes: **0 duplicate IDs**, **11 dangling `father=`**, **1 dangling `mother=`**,
**2 genuinely dangling `employer=`**, **2 absurd-but-resolving father links** (sons of a
3rd-century prophet), and **1 typo'd block ID**. All fixed below. No other changes were made to history data.

## Fixes applied

| # | File | Character | Change | Why |
|---|------|-----------|--------|-----|
| 1 | `bedouin_arabic.txt` | 251001 Muhammad (b.774) | `father=291001` → `251000` | 291001 never existed. 251000 Ali (b.740, d.780, same dynasty 1060000, previously childless) is the patriarch. |
| 2 | `bedouin_arabic.txt` | 251002 Hussayn (b.831) | `father=291002` → `251001` | 291002 never existed. Chained to 251001 (d.836, age 57 — date-consistent; the patriarch died 51y before this birth). |
| 3 | `bedouin_arabic.txt` | 251004 Al-Muhtadi (b.770) | `father=291004` → `251003` | 291004 never existed. 251003 Kadi (b.732, d.775, same dynasty 1060002, previously childless) is the patriarch. |
| 4 | `bedouin_arabic.txt` | 251005 Abdullah (b.840) | `father=291005` → `251004` | 291005 never existed. Chained to 251004 (d.845 — date-consistent; the patriarch died 65y before this birth). |
| 5 | `breton.txt` | 10060 Guimarc'h (b.1056) | `father=91244` → `91245` | Off-by-one typo; 91244 doesn't exist. 91245 Alfred (b.1015, same dynasty 20017, age 41 at birth) fits exactly. |
| 6 | `frankish.txt` | 212770 Beatrice (b.1125) | `father=213030` removed (kept as `#` comment) | 213030 doesn't exist; block is orphaned (no dynasty, no referrers) and no candidate fits. |
| 7 | `hausa.txt` | 251184 Kacinna (b.1066, "princess of Daura") | `father=1228658` → `251193` | 1228658 doesn't exist. 251193 Atuma (b.1043, Daura king, age 23 at her birth) is the only right-generation candidate. |
| 8 | `irish.txt` | 260495 Donnchad (b.1248) | `father=250494` → `260494` | Digit typo (`250494` → `260494`); 250494 doesn't exist. 260494 Domnall (b.1215, same dynasty, age 33 at birth) fits exactly. |
| 9 | `kanuri.txt` | 248748 Hummay (b.1050) | `father=1000228558` removed (kept as `#` comment) | Garbage 10-digit ID. Hummay ("first muslim ruler") heads a clean father→son chain, so he is the founder. |
| 10 | `maghreb_arabic.txt` | 273088 'Abu-Umar (b.1060) | `father=1144550` removed (kept as `#` comment) | 1144550 doesn't exist; sole member of dynasty 1069081 with no candidate father. |
| 11 | `mongol.txt` | 248206 Chotan (b.1227, female) | `father=248200` → `248204` | 248200 doesn't exist. 248204 Yasaur (b.1200, dynasty patriarch, age 27 at birth) is the only candidate. |
| 12 | `mongol.txt` | 248207 Altan (b.1261, sunni) | `father=248201` → `248205` | 248201 is **Mani, the 3rd-century prophet** (b.216!) — obvious typo. 248205 Bolkhada (b.1225, converted sunni 1260, age 36 at birth) matches on age, dynasty, and religion. The author's own sibling block 248210 already uses `father=248205`. |
| 13 | `mongol.txt` | 248208 Doguz (b.1264, sunni, female) | `father=248201` → `248205` | Same Mani typo as #12; same evidence (Bolkhada age 39 at birth). |
| 14 | `bodpa.txt` | **created 247095** (consort, b.672, d.745) | new block between 247094 and 247096 | 247095 was referenced twice — `247091`'s 690.1.1 `add_consort=c_247095` and `247098`'s `mother=247095` (`child_of_consort`) — but never defined. Reconstructed as lowborn (no `dynasty=` line), bon, bodpa; name/dates marked as placeholders in comments. |
| 15 | `german.txt` | 170341 Johannes | `employer=330444` → `30444` | Extra-digit typo. 30444 is Volkwin of the Livonian Swordbrothers, dynasty von Naumburg (matches the inline comment), died Sep 1236 — the employment starts Jan 1236. |
| 16 | `panjabi.txt` | 248075 Ibrahim Shah | `1246.1.1 = { employer = 1060080 }` commented out | 1060080 doesn't exist (looks like a dynasty ID pasted into a character field); no identifiable employer. Kept as `#` comment. |
| 17 | `kurdish.txt` | Hasanwayh (b.925, dynasty 1062496) | block ID `2601031` → `261031` | Extra-`0` typo: sits right after 261030 Husayn (same dynasty) as the file's last block. 261031 was free and nothing referenced either ID, so a pure rename. |

## Deliberately left alone

- **`employer = 0` (36 cases)** — a consistent idiom across files (military-order brothers, El Cid, Delhi sultans…), meaning "no employer". Not an error.
- **6 mother-date gaps of 6–10 years** (e.g. bodpa 247124/247125/247126 vs mother d.798; german 7658; nepali 12374; irish 166103) — the mother IDs look correct and the gaps are typical year-approximation noise. Fixing those would mean rewriting history dates, which is out of scope for an ID audit.
- **`248209`'s `#father=248203`** — already commented out by the author; left as is.
- No duplicate IDs were found anywhere (37,700 unique).

## Verification (re-ran after edits)

- 0 duplicate IDs, 0 unbalanced blocks, 0 dangling `father` / `mother` / spouse / killer / friend / rival / lover / consort refs.
- Remaining dangling `employer` refs: only the 36 intentional `employer = 0`.
- Every re-pointed parent/child pair is chronologically consistent (see table dates above).
- Byte-safe edits: files kept their original Windows-1252 encoding and CRLF line endings (mongol.txt was already LF and stayed LF).
