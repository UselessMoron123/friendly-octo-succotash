# Friedrich — character 212501

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/german.txt` (line 8655), block `212501 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `212501` |
| Name | `"Friedrich"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `529` |
| Religion | `"catholic"` |
| Culture | `"german"` |
| Father | `212495` — Friedrich (`characters/german.txt`) |
| Mother | `212498` — Jutta (`characters/german.txt`) |
| DNA | `"ikigifjeicn"` |
| Properties | `"0b00b00000"` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `7` | `7` | `7` | `4` | — |

## Traits (base entries, as in file)

- `"wroth"`
- `"proud"`
- `"diligent"`
- `"cynical"`
- `"grey_eminence"`

## Bloodline(s) (as in file)

### `barbarossa` — granted 1152.1.1

```text
		create_bloodline = {
			type = barbarossa
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `212495` — Friedrich (`characters/german.txt`)
- Mother: `212498` — Jutta (`characters/german.txt`)
- Spouses:
  - added 1147.1.1: `31519` — Adelheid (`characters/german.txt`)
  - removed 1153.3.1: `31519` — Adelheid (`characters/german.txt`)
  - added 1156.1.1: `205599` — Béatrix (`characters/frankish.txt`)
- Recorded children (9 other block(s) with `father=212501` or `mother=212501`):
  - `father=212501`: `7905` — Friedrich (`characters/german.txt`), born 1164.1.1
  - `father=212501`: `30778` — Sophia (`characters/german.txt`), born 1166.1.1
  - `father=212501`: `212500` — Friedrich (`characters/german.txt`), born 1167.1.1
  - `father=212501`: `212505` — Konrad (`characters/german.txt`), born 1173.1.1
  - `father=212501`: `212506` — Philipp (`characters/german.txt`), born 1177.1.1
  - `father=212501`: `212507` — Heinrich (`characters/german.txt`), born 1165.1.1
  - `father=212501`: `212509` — Beatrix (`characters/german.txt`), born 1157.1.1
  - `father=212501`: `212510` — Agnes (`characters/german.txt`), born 1170.1.1
  - `father=212501`: `212511` — Otto (`characters/german.txt`), born 1167.1.1

## Chronology (date order as in file; statements verbatim)

- **1122.1.1** — `birth="1122.1.1"`
- **1147.1.1** — `add_spouse=31519`
- **1152.1.1** — `create_bloodline={ type = barbarossa has_dlc = "Holy Fury" }`
- **1153.3.1** — `remove_spouse=31519`
- **1156.1.1** — `add_spouse=205599`
- **1190.6.2** — `death="1190.6.2"`

## History entries (verbatim)

### 1122.1.1

```text
	1122.1.1 = {
		birth="1122.1.1"
	}
```

### 1147.1.1

```text
	1147.1.1 = {
		add_spouse = 31519 #Adelheid Ratoponen
	}
```

### 1152.1.1

```text
	1152.1.1 = {
		create_bloodline = {
			type = barbarossa
			has_dlc = "Holy Fury"
		}
	}
```

### 1153.3.1

```text
	1153.3.1 = {
		remove_spouse = 31519 #Adelheid Ratoponen
	}
```

### 1156.1.1

```text
	1156.1.1 = {
		add_spouse = 205599 #Beatrice of Burgundy
	}
```

### 1190.6.2

```text
	1190.6.2 = {
		death="1190.6.2"
	}
```

## Full character block (verbatim)

```text
212501 = {
	name="Friedrich" #III of Swabia (1147-1152), E. of HRE (1152-1190)
	# AKA: Friedrich Barbarossa
	dynasty=529
	dna="ikigifjeicn"
	properties="0b00b00000"
	martial=7
	diplomacy=7
	intrigue=7
	stewardship=4
	religion="catholic"
	culture="german"
	trait="wroth"
	trait="proud"
	trait="diligent"
	trait="cynical"
	trait="grey_eminence"
	father=212495
	mother=212498
	1122.1.1 = {
		birth="1122.1.1"
	}
	1147.1.1 = {
		add_spouse = 31519 #Adelheid Ratoponen
	}
	1152.1.1 = {
		create_bloodline = {
			type = barbarossa
			has_dlc = "Holy Fury"
		}
	}
	1153.3.1 = {
		remove_spouse = 31519 #Adelheid Ratoponen
	}	
	1156.1.1 = {
		add_spouse = 205599 #Beatrice of Burgundy
	}
	1190.6.2 = {
		death="1190.6.2"
	}
}
```
