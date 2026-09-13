# Aliénor — character 205730

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/occitan.txt` (line 1279), block `205730 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `205730` |
| Name | `"Aliénor"` |
| Sex | female (`female = yes`) |
| Dynasty | `413` |
| Religion | `"catholic"` |
| Culture | `"occitan"` |
| Father | `205731` — Guilhèm (`characters/occitan.txt`) |
| Mother | `205732` — Aliénor (`characters/occitan.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `5` | `8` | `7` | `7` | — |

## Traits (base entries, as in file)

- `fair`
- `"diligent"`
- `"just"`
- `"proud"`
- `"patient"`
- `"brave"`
- `"charismatic_negotiator"`

## Bloodline(s) (as in file)

### `alienor_of_aquitaine` — granted 1122.1.1

```text
		create_bloodline = {
			type = alienor_of_aquitaine
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `205731` — Guilhèm (`characters/occitan.txt`)
- Mother: `205732` — Aliénor (`characters/occitan.txt`)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (10 other block(s) with `father=205730` or `mother=205730`):
  - `mother=205730`: `204507` — William (`characters/english.txt`), born 1153.8.17
  - `mother=205730`: `204508` — Henry (`characters/english.txt`), born 1155.2.28
  - `mother=205730`: `204509` — Matilda (`characters/english.txt`), born 1156.1.2
  - `mother=205730`: `204510` — Richard (`characters/english.txt`), born 1157.9.8
  - `mother=205730`: `204511` — Geoffrey (`characters/english.txt`), born 1158.9.23
  - `mother=205730`: `204512` — Eleanor (`characters/english.txt`), born 1162.1.14
  - `mother=205730`: `204513` — Joan (`characters/english.txt`), born 1165.1.2
  - `mother=205730`: `204514` — John (`characters/english.txt`), born 1166.12.24
  - `mother=205730`: `205504` — Alix (`characters/frankish.txt`), born 1151.1.1
  - `mother=205730`: `205512` — Marie (`characters/frankish.txt`), born 1145.1.1

## Chronology (date order as in file; statements verbatim)

- **1122.1.1** — `birth="1122.1.1"; create_bloodline={ type = alienor_of_aquitaine has_dlc = "Holy Fury" }`
- **1204.4.1** — `death="1204.4.1"`

## History entries (verbatim)

### 1122.1.1

```text
	1122.1.1 = {
		birth="1122.1.1"
		create_bloodline = {
			type = alienor_of_aquitaine
			has_dlc = "Holy Fury"
		}
	}
```

### 1204.4.1

```text
	1204.4.1 = {
		death="1204.4.1"
	}
```

## Full character block (verbatim)

```text
205730 = {
	name="Aliénor" #d'Aquitaine
	female=yes
	dynasty=413
	martial=5
	diplomacy=8
	intrigue=7
	stewardship=7
	religion="catholic"
	culture="occitan"
	trait=fair
	trait="diligent"
	trait="just"
	trait="proud"
	trait="patient"
	trait="brave"
	trait="charismatic_negotiator"
	father=205731
	mother=205732
	1122.1.1 = {
		birth="1122.1.1"
		create_bloodline = {
			type = alienor_of_aquitaine
			has_dlc = "Holy Fury"
		}
	}
	1204.4.1 = {
		death="1204.4.1"
	}
}
```
