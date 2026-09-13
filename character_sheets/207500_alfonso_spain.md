# Alfonso — character 207500

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/castillan.txt` (line 1511), block `207500 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `207500` |
| Name | `"Alfonso"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `681` |
| Religion | `"catholic"` |
| Culture | `"castillan"` |
| Father | `298` — Raymond (`characters/frankish.txt`) |
| Mother | `207660` — Urraca (`characters/castillan.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `4` | `7` | `8` | `5` | — |

## Traits (base entries, as in file)

- `"greedy"`
- `"tough_soldier"`

## Bloodline(s) (as in file)

### `alfonso_spain` — granted 1126.3.8

```text
		create_bloodline = {
			type = alfonso_spain
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `298` — Raymond (`characters/frankish.txt`)
- Mother: `207660` — Urraca (`characters/castillan.txt`)
- Spouses:
  - added 1133.1.1: `210511` — Berenguera (`characters/catalan.txt`)
  - added 1152.10.1: `221529` — Richeza (`characters/polish.txt`)
- Recorded children (11 other block(s) with `father=207500` or `mother=207500`):
  - `father=207500`: `71385` — Ramón (`characters/castillan.txt`), born 1136.4.12
  - `father=207500`: `71386` — García (`characters/castillan.txt`), born 1142.1.1
  - `father=207500`: `71387` — Alfonso (`characters/castillan.txt`), born 1144.1.1
  - `father=207500`: `71388` — Fernando (`characters/castillan.txt`), born 1153.1.1
  - `father=207500`: `71389` — Estefanía (`characters/castillan.txt`), born 1148.2.3
  - `father=207500`: `207501` — Urraca (`characters/castillan.txt`), born 1132.1.1
  - `father=207500`: `207502` — Sancha (`characters/castillan.txt`), born 1139.1.1
  - `father=207500`: `207503` — Constanza (`characters/castillan.txt`), born 1138.1.1
  - `father=207500`: `207504` — Sancha (`characters/castillan.txt`), born 1155.1.1
  - `father=207500`: `207520` — Sancho (`characters/castillan.txt`), born 1134.1.1
  - `father=207500`: `208500` — Fernando (`characters/castillan.txt`), born 1137.1.1

## Chronology (date order as in file; statements verbatim)

- **1105.3.1** — `birth="1105.3.1"`
- **1126.3.8** — `create_bloodline={ type = alfonso_spain has_dlc = "Holy Fury" }`
- **1133.1.1** — `add_spouse=210511`
- **1134.9.7** — `add_claim=k_aragon; add_claim=d_aragon; add_claim=k_navarra; add_claim=d_navarra`
- **1135.1.1** — `(see verbatim block below)`
- **1152.10.1** — `add_spouse=221529`
- **1157.8.21** — `death="1157.8.21"`

## History entries (verbatim)

### 1105.3.1

```text
	1105.3.1={
		birth="1105.3.1"
	}
```

### 1126.3.8

```text
	1126.3.8={
		capital=c_toledo
		create_bloodline = {
			type = alfonso_spain
			has_dlc = "Holy Fury"
		}
	}
```

### 1133.1.1

```text
	1133.1.1={
		add_spouse=210511
	}
```

### 1134.9.7

```text
	1134.9.7={
		add_claim = k_aragon
		add_claim = d_aragon
		add_claim = k_navarra
		add_claim = d_navarra
	}
```

### 1135.1.1

```text
	1135.1.1={
		remove_claim = k_aragon
		remove_claim = d_aragon
		remove_claim = k_navarra
		remove_claim = d_navarra
	}
```

### 1152.10.1

```text
	1152.10.1={
		add_spouse=221529
	}
```

### 1157.8.21

```text
	1157.8.21={
		death="1157.8.21"
	}
```

## Full character block (verbatim)

```text
207500 = {
	name="Alfonso" #AKA: Alfonso VII 'el Emperador'
	dynasty=681
	martial=4
	diplomacy=7
	intrigue=8
	stewardship=5
	religion="catholic"
	culture="castillan"
	trait="greedy"
	trait="tough_soldier"
	father=298
	mother= 207660
	1105.3.1={
		birth="1105.3.1"
	}
	1126.3.8={
		capital=c_toledo
		create_bloodline = {
			type = alfonso_spain
			has_dlc = "Holy Fury"
		}
	}
	1133.1.1={
		add_spouse=210511
	}
	1134.9.7={
		add_claim = k_aragon
		add_claim = d_aragon
		add_claim = k_navarra
		add_claim = d_navarra
	}
	1135.1.1={
		remove_claim = k_aragon
		remove_claim = d_aragon
		remove_claim = k_navarra
		remove_claim = d_navarra
	}
	1152.10.1={
		add_spouse=221529
	}
	1157.8.21={
		death="1157.8.21"
	}
}
```
