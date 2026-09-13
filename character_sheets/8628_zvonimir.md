# Zvonimir — character 8628

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/croatian.txt` (line 445), block `8628 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `8628` |
| Name | `"Zvonimir"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `512` |
| Religion | `"catholic"` |
| Culture | `"croatian"` |
| Father | `8608` — Stjepan (`characters/croatian.txt`) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `4` | `8` | `5` | `8` | — |

## Traits (base entries, as in file)

- `"diligent"`
- `"zealous"`
- `"charitable"`
- `"fortune_builder"`

## Bloodline(s) (as in file)

### `zvonimir` — granted 1030.1.1

```text
		create_bloodline = {
			type = zvonimir
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `8608` — Stjepan (`characters/croatian.txt`)
- Mother: — (no `mother=` line)
- Spouses:
  - added 1064.1.1: `475` — Ilona (`characters/hungarian.txt`)
- Recorded children (2 other block(s) with `father=8628` or `mother=8628`):
  - `father=8628`: `183006` — Klaudija (`characters/croatian.txt`), born 1064.1.1
  - `father=8628`: `183007` — Radovan (`characters/croatian.txt`), born 1065.1.1

## Chronology (date order as in file; statements verbatim)

- **1030.1.1** — `birth="1030.1.1"; create_bloodline={ type = zvonimir has_dlc = "Holy Fury" }`
- **1064.1.1** — `add_spouse=475`
- **1075.1.1** — `name="Dmitar-Zvonimir"`
- **1089.4.20** — `death="1089.4.20"`

## History entries (verbatim)

### 1030.1.1

```text
	1030.1.1={
		birth="1030.1.1"
		create_bloodline = {
			type = zvonimir
			has_dlc = "Holy Fury"
		}
	}
```

### 1064.1.1

```text
	1064.1.1={
		add_spouse=475
	}
```

### 1075.1.1

```text
	1075.1.1={
		name="Dmitar-Zvonimir"
	}
```

### 1089.4.20

```text
	1089.4.20={
		death="1089.4.20"
	}
```

## Full character block (verbatim)

```text
8628 = {
	name="Zvonimir"
	# AKA: Dmitar Zvonimir
	dynasty=512
	martial=4
	diplomacy=8
	intrigue=5
	stewardship=8
	religion="catholic"
	culture="croatian"
	trait="diligent"
	trait="zealous"
	trait="charitable"
	trait="fortune_builder"
	father=8608
	#mother=538
	1030.1.1={
		birth="1030.1.1"
		create_bloodline = {
			type = zvonimir
			has_dlc = "Holy Fury"
		}
	}
	1064.1.1={
		add_spouse=475
	}
	1075.1.1={
		name="Dmitar-Zvonimir"
	}
	1089.4.20={
		death="1089.4.20"
	}
}
```
