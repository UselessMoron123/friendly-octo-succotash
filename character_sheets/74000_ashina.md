# Muhan — character 74000

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/khazar.txt` (line 1), block `74000 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `74000` |
| Name | `"Muhan"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `12269` |
| Religion | `"tengri_pagan"` |
| Culture | `"khazar"` |
| Father | — (no `father=` line) |
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

### `ashina` — granted 560.1.1

```text
		create_bloodline = {
			type = ashina
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: — (no `father=` line)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (2 other block(s) with `father=74000` or `mother=74000`):
  - `father=74000`: `74001` — Tun-Yagbu (`characters/khazar.txt`), born 580.1.1
  - `father=74000`: `74002` — Bagha-Shad (`characters/khazar.txt`), born 582.1.1

## Chronology (date order as in file; statements verbatim)

- **560.1.1** — `birth="560.1.1"; create_bloodline={ type = ashina has_dlc = "Holy Fury" }`
- **611.1.1** — `death="611.1.1"`

## History entries (verbatim)

### 560.1.1

```text
	560.1.1={
		birth="560.1.1"
		create_bloodline = {
			type = ashina
			has_dlc = "Holy Fury"
		}
	}
```

### 611.1.1

```text
	611.1.1={
		death="611.1.1"
	}
```

## Full character block (verbatim)

```text
74000 = {
	name="Muhan"
	dynasty=12269

	culture="khazar"
	religion="tengri_pagan"

	560.1.1={
		birth="560.1.1"
		create_bloodline = {
			type = ashina
			has_dlc = "Holy Fury"
		}
	}
	611.1.1={
		death="611.1.1"
	}
}
```
