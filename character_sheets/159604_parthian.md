# Mirian — character 159604

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/georgian.txt` (line 2057), block `159604 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `159604` |
| Name | `"Mirian"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `100680` |
| Religion | `"miaphysite"` |
| Culture | `"georgian"` |
| Father | `159603` — Khosro (`characters/georgian.txt`) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

_None at top level._

## Bloodline(s) (as in file)

### `parthian` — granted 265.11.1

```text
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `159603` — Khosro (`characters/georgian.txt`)
- Mother: — (no `mother=` line)
- Spouses:
  - added 285.11.1: `159598` — Abeshura (`characters/georgian.txt`)
- Recorded children (3 other block(s) with `father=159604` or `mother=159604`):
  - `father=159604`: `159605` — Varaz-Bakur (`characters/georgian.txt`), born 292.1.1
  - `father=159604`: `159606` — Rev (`characters/georgian.txt`), born 300.1.1
  - `father=159604`: `159759` — Varaz-Bakur (`characters/georgian.txt`), born 305.1.1

## Chronology (date order as in file; statements verbatim)

- **265.11.1** — `birth="265.11.1"; create_bloodline={ type = parthian has_dlc = "Holy Fury" }`
- **285.11.1** — `add_spouse=159598`
- **361.1.1** — `death="361.1.1"`

## History entries (verbatim)

### 265.11.1

```text
	265.11.1={
		birth="265.11.1"
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
	}
```

### 285.11.1

```text
	285.11.1={
		add_spouse = 159598
	}
```

### 361.1.1

```text
	361.1.1={
		death="361.1.1"
	}
```

## Full character block (verbatim)

```text
159604 = { 
	name="Mirian" # III of Kartli/Iberia
	dynasty=100680
	religion="miaphysite"
	culture="georgian"
	father=159603
	265.11.1={
		birth="265.11.1"
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
	}
	285.11.1={
		add_spouse = 159598
	}
	361.1.1={
		death="361.1.1"
	}
}
```
