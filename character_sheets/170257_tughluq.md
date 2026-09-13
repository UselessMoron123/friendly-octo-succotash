# Tughluq — character 170257

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/turkish.txt` (line 8694), block `170257 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `170257` |
| Name | `"Tughluq"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `1040208` |
| Religion | `"sunni"` |
| Culture | `"turkish"` |
| Father | `170256` — Tughluq (`characters/turkish.txt`) |
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

### `tughluq` — granted 1320.10.1

```text
		create_bloodline = {
			type = tughluq
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `170256` — Tughluq (`characters/turkish.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=170257` or `mother=170257`):
  - `father=170257`: `170258` — Muhammad (`characters/turkish.txt`), born 1297.1.1

## Chronology (date order as in file; statements verbatim)

- **1271.1.1** — `birth="1271.1.1"`
- **1320.10.1** — `create_bloodline={ type = tughluq has_dlc = "Holy Fury" }`
- **1325.2.1** — `death="1325.2.1"`

## History entries (verbatim)

### 1271.1.1

```text
	1271.1.1={
		birth="1271.1.1"
	}
```

### 1320.10.1

```text
	1320.10.1={
		create_bloodline = {
			type = tughluq
			has_dlc = "Holy Fury"
		}
	}
```

### 1325.2.1

```text
	1325.2.1={
		death="1325.2.1"
	}
```

## Full character block (verbatim)

```text
170257 = {
	name="Tughluq" #Ghiyath al-Din Tughluq
	dynasty=1040208
	religion="sunni"
	culture="turkish"
	father=170256
	1271.1.1={
		birth="1271.1.1"
	}
	1320.10.1={
		create_bloodline = {
			type = tughluq
			has_dlc = "Holy Fury"
		}
	}
	1325.2.1={
		death="1325.2.1"
	}
}
```
