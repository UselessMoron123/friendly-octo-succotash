# Abu Ya'qub — character 32980

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/maghreb_arabic.txt` (line 2765), block `32980 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `32980` |
| Name | `"Abu Ya'qub"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `101875` |
| Religion | `"sunni"` |
| Culture | `"maghreb_arabic"` |
| Father | `224000` — Yusuf (`characters/maghreb_arabic.txt`) |
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

### `almohad` — granted 1184.7.29

```text
		create_bloodline = {
			type = almohad
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `224000` — Yusuf (`characters/maghreb_arabic.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (5 other block(s) with `father=32980` or `mother=32980`):
  - `father=32980`: `32983` — Abdallah (`characters/maghreb_arabic.txt`), born 1175.1.1
  - `father=32980`: `32985` — Idris (`characters/maghreb_arabic.txt`), born 1174.1.1
  - `father=32980`: `32988` — Ishaq (`characters/maghreb_arabic.txt`), born 1180.1.1
  - `father=32980`: `32992` — Mussa (`characters/maghreb_arabic.txt`), born 1173.1.1
  - `father=32980`: `224005` — an-Nassir (`characters/maghreb_arabic.txt`), born 1176.1.1

## Chronology (date order as in file; statements verbatim)

- **1155.1.1** — `birth="1155.1.1"`
- **1184.7.29** — `create_bloodline={ type = almohad has_dlc = "Holy Fury" }`
- **1199.1.23** — `death="1199.1.23"`

## History entries (verbatim)

### 1155.1.1

```text
	1155.1.1 = {
		birth="1155.1.1"
	}
```

### 1184.7.29

```text
	1184.7.29 = {
		create_bloodline = {
			type = almohad
			has_dlc = "Holy Fury"
		}
	}
```

### 1199.1.23

```text
	1199.1.23 = {
		death="1199.1.23"
	}
```

## Full character block (verbatim)

```text
32980 = {
	name="Abu Ya'qub" #1184-1199
	dynasty=101875
	religion="sunni"
	culture="maghreb_arabic"
	father=224000
	1155.1.1 = {
		birth="1155.1.1"
	}
	1184.7.29 = {
		create_bloodline = {
			type = almohad
			has_dlc = "Holy Fury"
		}
	}
	1199.1.23 = {
		death="1199.1.23"
	}
}
```
