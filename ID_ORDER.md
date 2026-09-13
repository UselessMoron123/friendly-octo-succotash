# Character ID ordering & gap analysis

Read-only analysis of block order and ID gaps across `characters/*.txt` (37,700 blocks).
No history files were changed for this report. Method: blocks parsed in file order via `^ID = {`;
comment-aware brace matching; IDs verified unique (see `ID_FIXES.md`).

## TL;DR

- Files are **organized in ascending runs (families/ranges appended in chunks)**, not globally sorted: 82–100% of adjacent ID pairs are ascending, but each file contains several out-of-order chunks.
- Gaps are **huge and harmless**: 37,700 IDs spread over a 0–1.06M space (3.56% dense). The engine only needs uniqueness.
- The `1059xxx–10599xx` cluster and dense `248xxx` block are **deliberate content ranges**, not accidents.
- One gap-causing typo was already fixed: kurdish `2601031` → `261031` (see `ID_FIXES.md` #17).
- Recommendation: leave order and gaps as-is (ID stability matters for saves/tools; sorting would scatter family groups).

## Global picture

- Unique IDs: **37,700** | global min **98** | global max **1,059,999**
- Global span: **1,059,902** → density **3.56%**

### Blocks per 100k ID bucket (global)

| Bucket | Blocks | Bar |
|---|---|---|
| 0-99k | 13,527 | ██████████████████████████████ |
| 100-199k | 13,802 | ███████████████████████████████ |
| 200-299k | 7,913 | ██████████████████ |
| 300-399k |    68 | █ |
| 400-499k | 2,328 | ██████ |
| 500-599k |     4 | █ |
| 600-699k |     0 | · |
| 700-799k |     0 | · |
| 800-899k |     0 | · |
| 900-999k |     0 | · |
| 1000-1099k |    58 | █ |

## Per-file ordering stats

`runs` = number of ascending chunks (1 = perfectly sorted file). `displaced` = blocks appearing after a higher ID.

| File | Blocks | Min | Max | Runs | Adjacent-ordered | Displaced | Max gap |
|---|---|---|---|---|---|---|---|
| `characters/afghan.txt` | 46 | 74,723 | 1,059,735 | 5 | 95.6% | 4 | 798,409 |
| `characters/alan.txt` | 92 | 9,953 | 480,210 | 80 | 86.8% | 79 | 205,520 |
| `characters/andalusian_arabic.txt` | 188 | 3,212 | 487,001 | 173 | 94.1% | 172 | 202,630 |
| `characters/arberian.txt` | 13 | 34,446 | 260,675 | 4 | 83.3% | 3 | 180,559 |
| `characters/armenian.txt` | 534 | 4,554 | 465,911 | 468 | 97.0% | 467 | 198,910 |
| `characters/assamese.txt` | 80 | 190,039 | 261,130 | 11 | 98.7% | 10 | 69,525 |
| `characters/assyrian.txt` | 14 | 248,115 | 248,129 | 1 | 100.0% | 0 | 1 |
| `characters/avar.txt` | 50 | 146,137 | 194,006 | 50 | 93.9% | 49 | 25,420 |
| `characters/baloch.txt` | 17 | 6,899 | 261,114 | 1 | 100.0% | 0 | 171,107 |
| `characters/basque.txt` | 426 | 7,562 | 475,551 | 395 | 97.2% | 394 | 249,971 |
| `characters/bedouin_arabic.txt` | 995 | 3,080 | 261,370 | 870 | 95.4% | 869 | 59,051 |
| `characters/bengali.txt` | 271 | 154,000 | 261,126 | 237 | 95.6% | 236 | 69,572 |
| `characters/bodpa.txt` | 484 | 12,000 | 261,096 | 261 | 98.8% | 260 | 230,796 |
| `characters/bohemian.txt` | 205 | 500 | 471,525 | 171 | 98.0% | 170 | 189,785 |
| `characters/bolghar.txt` | 133 | 3,500 | 260,707 | 115 | 94.7% | 114 | 55,229 |
| `characters/bosnian.txt` | 22 | 34,145 | 468,810 | 12 | 95.2% | 11 | 208,152 |
| `characters/breton.txt` | 336 | 178 | 455,581 | 312 | 94.0% | 311 | 195,098 |
| `characters/bulgarian.txt` | 137 | 712 | 468,555 | 96 | 94.9% | 95 | 203,214 |
| `characters/carantanian.txt` | 14 | 168,580 | 260,633 | 1 | 100.0% | 0 | 91,480 |
| `characters/castillan.txt` | 1,116 | 9,051 | 460,614 | 922 | 99.5% | 921 | 223,381 |
| `characters/catalan.txt` | 614 | 405 | 461,550 | 481 | 98.9% | 480 | 244,952 |
| `characters/coptic.txt` | 38 | 35,001 | 261,308 | 1 | 100.0% | 0 | 126,489 |
| `characters/crimean_gothic.txt` | 14 | 20,463 | 260,818 | 7 | 84.6% | 6 | 74,608 |
| `characters/croatian.txt` | 157 | 8,600 | 470,024 | 145 | 95.5% | 144 | 207,199 |
| `characters/cuman.txt` | 229 | 753 | 480,150 | 168 | 89.0% | 167 | 217,925 |
| `characters/daju.txt` | 14 | 248,734 | 248,747 | 1 | 100.0% | 0 | 0 |
| `characters/dalmatian.txt` | 13 | 145,199 | 297,792 | 6 | 75.0% | 5 | 66,144 |
| `characters/danish.txt` | 212 | 6,904 | 451,804 | 110 | 96.2% | 109 | 140,636 |
| `characters/dutch.txt` | 448 | 358 | 487,058 | 360 | 96.4% | 359 | 192,386 |
| `characters/eastereggs.txt` | 118 | 157,000 | 257,047 | 71 | 95.7% | 70 | 35,127 |
| `characters/egyptian_arabic.txt` | 120 | 3,090 | 485,120 | 111 | 92.4% | 110 | 223,669 |
| `characters/english.txt` | 734 | 7,284 | 487,043 | 415 | 97.1% | 414 | 99,344 |
| `characters/ethiopian.txt` | 232 | 32,225 | 261,329 | 177 | 98.3% | 176 | 77,384 |
| `characters/finnish.txt` | 117 | 6,828 | 486,030 | 99 | 92.2% | 98 | 166,971 |
| `characters/frankish.txt` | 2,508 | 200 | 487,045 | 1939 | 94.7% | 1,938 | 69,860 |
| `characters/frisian.txt` | 17 | 131,724 | 168,626 | 3 | 87.5% | 2 | 35,971 |
| `characters/georgian.txt` | 174 | 9,950 | 466,763 | 120 | 94.8% | 119 | 229,151 |
| `characters/german.txt` | 3,250 | 289 | 500,004 | 2512 | 97.6% | 2,511 | 131,977 |
| `characters/greek.txt` | 1,212 | 481 | 468,503 | 950 | 97.8% | 949 | 199,463 |
| `characters/gujurati.txt` | 79 | 188,062 | 191,684 | 13 | 98.7% | 12 | 3,325 |
| `characters/han.txt` | 424 | 206,811 | 1,059,723 | 359 | 98.6% | 358 | 798,577 |
| `characters/hausa.txt` | 78 | 251,177 | 251,254 | 22 | 98.7% | 21 | 0 |
| `characters/hindustani.txt` | 353 | 12,248 | 261,128 | 86 | 96.6% | 85 | 165,727 |
| `characters/hungarian.txt` | 553 | 460 | 470,218 | 384 | 98.2% | 383 | 200,389 |
| `characters/irish.txt` | 1,473 | 900 | 454,205 | 1371 | 98.4% | 1,370 | 122,092 |
| `characters/italian.txt` | 2,576 | 496 | 478,504 | 2374 | 98.2% | 2,373 | 150,680 |
| `characters/jurchen.txt` | 17 | 215,597 | 244,009 | 4 | 81.2% | 3 | 26,267 |
| `characters/kannada.txt` | 339 | 74,400 | 261,119 | 293 | 99.1% | 292 | 100,203 |
| `characters/kanuri.txt` | 50 | 248,708 | 248,840 | 1 | 100.0% | 0 | 52 |
| `characters/karluk.txt` | 82 | 3,000 | 261,068 | 60 | 85.2% | 59 | 109,229 |
| `characters/khanty.txt` | 41 | 159,735 | 261,077 | 1 | 100.0% | 0 | 71,559 |
| `characters/khazar.txt` | 70 | 20,663 | 261,005 | 41 | 91.3% | 40 | 71,759 |
| `characters/khitan.txt` | 114 | 93,258 | 261,079 | 15 | 96.5% | 14 | 73,527 |
| `characters/kirghiz.txt` | 44 | 34,873 | 261,085 | 3 | 97.7% | 2 | 159,318 |
| `characters/komi.txt` | 96 | 6,855 | 260,792 | 2 | 98.9% | 1 | 152,878 |
| `characters/kurdish.txt` | 159 | 3,854 | 261,031 | 133 | 93.0% | 132 | 51,590 |
| `characters/lappish.txt` | 36 | 20,617 | 486,010 | 29 | 88.6% | 28 | 225,447 |
| `characters/lettigallish.txt` | 56 | 6,892 | 261,267 | 20 | 94.5% | 19 | 115,056 |
| `characters/levantine_arabic.txt` | 544 | 3,814 | 485,490 | 446 | 97.6% | 445 | 215,425 |
| `characters/lithuanian.txt` | 186 | 6,893 | 473,515 | 143 | 96.2% | 142 | 210,255 |
| `characters/lombard.txt` | 423 | 1,116 | 262,441 | 288 | 97.6% | 287 | 71,728 |
| `characters/maghreb_arabic.txt` | 682 | 3,210 | 485,150 | 605 | 96.8% | 604 | 147,701 |
| `characters/manden.txt` | 81 | 161,011 | 260,875 | 1 | 100.0% | 0 | 62,346 |
| `characters/manichean_church.txt` | 3 | 248,201 | 248,203 | 1 | 100.0% | 0 | 0 |
| `characters/marathi.txt` | 185 | 74,411 | 261,118 | 16 | 99.5% | 15 | 103,302 |
| `characters/meshchera.txt` | 21 | 159,710 | 256,125 | 1 | 100.0% | 0 | 61,886 |
| `characters/mongol.txt` | 590 | 34,430 | 480,000 | 542 | 95.2% | 541 | 211,712 |
| `characters/mordvin.txt` | 68 | 6,849 | 260,784 | 30 | 97.0% | 29 | 122,512 |
| `characters/nepali.txt` | 215 | 12,300 | 247,720 | 78 | 97.7% | 77 | 234,638 |
| `characters/norman.txt` | 428 | 140 | 465,525 | 353 | 92.3% | 352 | 133,498 |
| `characters/norse.txt` | 505 | 242 | 451,005 | 327 | 94.8% | 326 | 140,974 |
| `characters/norwegian.txt` | 273 | 5,787 | 487,074 | 102 | 96.7% | 101 | 170,642 |
| `characters/nubian.txt` | 167 | 20,572 | 260,894 | 75 | 97.6% | 74 | 113,936 |
| `characters/occitan.txt` | 844 | 228 | 462,701 | 763 | 82.6% | 762 | 159,673 |
| `characters/old_frankish.txt` | 293 | 6,392 | 245,003 | 253 | 94.9% | 252 | 40,456 |
| `characters/old_saxon.txt` | 22 | 190,455 | 190,476 | 1 | 100.0% | 0 | 0 |
| `characters/oriya.txt` | 235 | 175,120 | 191,467 | 126 | 98.3% | 125 | 14,036 |
| `characters/panjabi.txt` | 231 | 178,000 | 261,116 | 22 | 98.7% | 21 | 52,825 |
| `characters/pecheneg.txt` | 82 | 483 | 479,050 | 78 | 95.1% | 77 | 214,722 |
| `characters/persian.txt` | 545 | 3,050 | 1,059,970 | 513 | 94.7% | 512 | 581,672 |
| `characters/pictish.txt` | 106 | 166,513 | 166,620 | 1 | 100.0% | 0 | 1 |
| `characters/polish.txt` | 393 | 752 | 472,900 | 290 | 98.0% | 289 | 195,497 |
| `characters/pommeranian.txt` | 200 | 505 | 471,662 | 158 | 96.5% | 157 | 178,461 |
| `characters/portuguese.txt` | 1,439 | 70,048 | 459,562 | 1371 | 93.3% | 1,370 | 246,510 |
| `characters/prussian.txt` | 30 | 28,015 | 261,242 | 9 | 96.6% | 8 | 116,651 |
| `characters/rajput.txt` | 782 | 12,267 | 261,129 | 575 | 98.0% | 574 | 95,732 |
| `characters/roman.txt` | 145 | 7,600 | 168,799 | 66 | 98.6% | 65 | 74,540 |
| `characters/romanian.txt` | 59 | 20,638 | 475,560 | 47 | 91.4% | 46 | 213,702 |
| `characters/russian.txt` | 841 | 601 | 475,430 | 278 | 99.0% | 277 | 208,059 |
| `characters/saka.txt` | 86 | 166,632 | 261,086 | 65 | 97.6% | 64 | 81,327 |
| `characters/samoyed.txt` | 115 | 20,619 | 260,783 | 1 | 100.0% | 0 | 139,095 |
| `characters/sardinian.txt` | 186 | 20,325 | 262,601 | 175 | 96.2% | 174 | 72,614 |
| `characters/saxon.txt` | 537 | 98 | 261,390 | 191 | 95.9% | 190 | 40,997 |
| `characters/scottish.txt` | 513 | 960 | 487,061 | 289 | 93.2% | 288 | 99,315 |
| `characters/sephardi.txt` | 21 | 3,220 | 261,384 | 6 | 90.0% | 5 | 171,245 |
| `characters/serbian.txt` | 151 | 4,491 | 468,511 | 135 | 93.3% | 134 | 205,798 |
| `characters/sindhi.txt` | 76 | 175,050 | 261,109 | 15 | 98.7% | 14 | 72,539 |
| `characters/sinhala.txt` | 82 | 175,010 | 217,396 | 25 | 95.1% | 24 | 28,198 |
| `characters/slovieni.txt` | 51 | 146,176 | 273,065 | 1 | 100.0% | 0 | 73,028 |
| `characters/sogdian.txt` | 61 | 12,220 | 1,059,727 | 16 | 95.0% | 15 | 798,656 |
| `characters/somali.txt` | 16 | 145,619 | 260,929 | 1 | 100.0% | 0 | 114,970 |
| `characters/songhay.txt` | 39 | 161,040 | 260,878 | 1 | 100.0% | 0 | 99,800 |
| `characters/soninke.txt` | 82 | 161,000 | 251,176 | 2 | 98.8% | 1 | 62,374 |
| `characters/suebi.txt` | 1 | 200,058 | 200,058 | 1 | 100.0% | 0 | 0 |
| `characters/sumpa.txt` | 6 | 12,068 | 247,342 | 5 | 80.0% | 4 | 230,334 |
| `characters/swedish.txt` | 440 | 20,005 | 487,072 | 252 | 96.8% | 251 | 207,973 |
| `characters/tamil.txt` | 113 | 175,070 | 261,120 | 21 | 97.3% | 20 | 43,729 |
| `characters/tangut.txt` | 225 | 12,200 | 1,059,999 | 213 | 96.0% | 212 | 816,967 |
| `characters/telugu.txt` | 68 | 175,110 | 261,122 | 4 | 97.0% | 3 | 70,840 |
| `characters/tocharian.txt` | 56 | 166,702 | 261,123 | 1 | 100.0% | 0 | 94,366 |
| `characters/turkish.txt` | 679 | 3,012 | 480,280 | 509 | 97.2% | 508 | 166,058 |
| `characters/ugricbaltic.txt` | 86 | 6,830 | 261,298 | 26 | 91.8% | 25 | 115,123 |
| `characters/uyghur.txt` | 160 | 166,323 | 1,059,986 | 100 | 89.9% | 99 | 798,641 |
| `characters/visigothic.txt` | 334 | 70,000 | 457,681 | 3 | 99.7% | 2 | 197,077 |
| `characters/welsh.txt` | 797 | 6,358 | 454,211 | 741 | 97.6% | 740 | 87,960 |
| `characters/zaghawa.txt` | 39 | 248,717 | 248,817 | 22 | 97.4% | 21 | 33 |
| `characters/zhangzhung.txt` | 28 | 242,400 | 261,089 | 11 | 81.5% | 10 | 9,061 |

Total ascending runs across all files: **27463** in 117 files.

## Largest gaps (top 25, per file)

| # | File | Gap size | Between IDs |
|---|---|---|---|
| 1 | `characters/tangut.txt` | 816,967 | 243,019 → 1,059,987 |
| 2 | `characters/sogdian.txt` | 798,656 | 261,067 → 1,059,724 |
| 3 | `characters/uyghur.txt` | 798,641 | 261,087 → 1,059,729 |
| 4 | `characters/han.txt` | 798,577 | 261,136 → 1,059,714 |
| 5 | `characters/afghan.txt` | 798,409 | 261,322 → 1,059,732 |
| 6 | `characters/persian.txt` | 581,672 | 478,028 → 1,059,701 |
| 7 | `characters/basque.txt` | 249,971 | 207,610 → 457,582 |
| 8 | `characters/portuguese.txt` | 246,510 | 210,510 → 457,021 |
| 9 | `characters/catalan.txt` | 244,952 | 210,576 → 455,529 |
| 10 | `characters/nepali.txt` | 234,638 | 12,441 → 247,080 |
| 11 | `characters/bodpa.txt` | 230,796 | 12,203 → 243,000 |
| 12 | `characters/sumpa.txt` | 230,334 | 12,068 → 242,403 |
| 13 | `characters/georgian.txt` | 229,151 | 232,770 → 461,922 |
| 14 | `characters/lappish.txt` | 225,447 | 260,552 → 486,000 |
| 15 | `characters/egyptian_arabic.txt` | 223,669 | 261,330 → 485,000 |
| 16 | `characters/castillan.txt` | 223,381 | 232,021 → 455,403 |
| 17 | `characters/cuman.txt` | 217,925 | 261,074 → 479,000 |
| 18 | `characters/persian.txt` | 216,677 | 261,342 → 478,020 |
| 19 | `characters/levantine_arabic.txt` | 215,425 | 262,599 → 478,025 |
| 20 | `characters/pecheneg.txt` | 214,722 | 260,697 → 475,420 |
| 21 | `characters/romanian.txt` | 213,702 | 261,397 → 475,100 |
| 22 | `characters/mongol.txt` | 211,712 | 261,082 → 472,795 |
| 23 | `characters/lithuanian.txt` | 210,255 | 261,247 → 471,503 |
| 24 | `characters/bosnian.txt` | 208,152 | 260,647 → 468,800 |
| 25 | `characters/russian.txt` | 208,059 | 260,770 → 468,830 |

## Example: chunk layout of `characters/english.txt`

734 blocks in 22 ascending chunks (file order):

| Chunk | Blocks | ID range |
|---|---|---|
| 1 | 170 | 144,237 → 232,682 |
| 2 | 162 | 31,001 → 487,043 |
| 3 | 1 | 71,809 → 71,809 |
| 4 | 5 | 7,284 → 7,356 |
| 5 | 49 | 7,348 → 82,084 |
| 6 | 72 | 31,381 → 204,571 |
| 7 | 1 | 203,571 → 203,571 |
| 8 | 2 | 138,426 → 138,451 |
| 9 | 49 | 34,349 → 161,373 |
| 10 | 16 | 161,331 → 204,060 |
| 11 | 123 | 161,426 → 183,222 |
| 12 | 14 | 183,029 → 183,210 |
| 13 | 5 | 183,010 → 183,074 |
| 14 | 1 | 180,790 → 180,790 |
| 15 | 1 | 180,056 → 180,056 |
| 16 | 7 | 180,050 → 180,791 |
| 17 | 10 | 180,057 → 180,715 |
| 18 | 3 | 144,241 → 144,247 |
| 19 | 5 | 144,243 → 454,571 |
| 20 | 1 | 454,570 → 454,570 |
| 21 | 5 | 188,888 → 454,573 |
| 22 | 32 | 183,075 → 183,106 |

Same pattern holds for the other large files (e.g. `german.txt`, `frankish.txt`, `italian.txt`):
sorted runs of family/range allocations concatenated as content was added.

## Deliberate high ranges (not errors)

- `1,059,xxx–1,059,9xx`: Jade-Dragon-era Tibetan/Chinese/Steppe content (`han`, `sogdian`, `tangut`, `uyghur`, `afghan`, `persian` files).
- `248,xxx`: dense late-avant-garde block shared by many small cultures (daju, kanuri, zaghawa, assyrian, manichean_church, …).
- `2,601,031` (ex kurdish max): was a typo, fixed to `261031`; kurdish now spans 3,854–261,031 like its neighbors. Global max is now `1,059,999` (tangut).
