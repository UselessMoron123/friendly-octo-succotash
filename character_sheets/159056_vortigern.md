# Gwrtheyrn — character 159056

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/welsh.txt` (line 3876), block `159056 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `159056` |
| Name | `"Gwrtheyrn"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `1029003` |
| Religion | `"catholic"` |
| Culture | `"welsh"` |
| Father | `159945` — Gwydolin (`characters/welsh.txt`) |
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

### `vortigern` — granted 350.1.1

```text
		create_bloodline = {
			type = vortigern
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `159945` — Gwydolin (`characters/welsh.txt`)
- Mother: — (no `mother=` line)
- Spouses:
  - added 375.1.1: `159810` — Severa (`characters/welsh.txt`)
- Recorded children (4 other block(s) with `father=159056` or `mother=159056`):
  - `father=159056`: `159057` — Cadeyrn (`characters/welsh.txt`), born 375.1.1
  - `father=159056`: `159836` — Gwerthefyr (`characters/welsh.txt`), born 376.1.1
  - `father=159056`: `159949` — Brydw (`characters/welsh.txt`), born 390.1.1
  - `father=159056`: `252353` — Pasgen (`characters/welsh.txt`), born 378.1.1

## Chronology (date order as in file; statements verbatim)

- **350.1.1** — `birth="350.1.1"; create_bloodline={ type = vortigern has_dlc = "Holy Fury" }`
- **375.1.1** — `add_spouse=159810`
- **441.1.1** — `death="441.1.1"`

## History entries (verbatim)

### 350.1.1

```text
	350.1.1={
		birth="350.1.1"
		create_bloodline = {
			type = vortigern
			has_dlc = "Holy Fury"
		}
	}
```

### 375.1.1

```text
	375.1.1={
		add_spouse=159810
	}
```

### 441.1.1

```text
	441.1.1={
		death="441.1.1"
	}
```

## Full character block (verbatim)

```text
159056 = {
	name="Gwrtheyrn" # Vortigern
	dynasty=1029003 # Gwerthrynion
	religion="catholic"
	culture="welsh"
	father=159945
	350.1.1={
		birth="350.1.1"
		create_bloodline = {
			type = vortigern
			has_dlc = "Holy Fury"
		}
	}
	375.1.1={
		add_spouse=159810
	}
	441.1.1={
		death="441.1.1"
	}
}
```
