# Bahram — character 180645

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/persian.txt` (line 3790), block `180645 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `180645` |
| Name | `"Bahram"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `1042070` |
| Religion | `"zoroastrian"` |
| Culture | `"persian"` |
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

### `parthian` — granted 553.1.1

```text
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: — (no `father=` line)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=180645` or `mother=180645`):
  - `father=180645`: `188634` — Noshrad (`characters/persian.txt`), born 590.1.1

## Chronology (date order as in file; statements verbatim)

- **553.1.1** — `birth="553.1.1"; create_bloodline={ type = parthian has_dlc = "Holy Fury" }`
- **592.1.1** — `death="592.1.1"`

## History entries (verbatim)

### 553.1.1

```text
	553.1.1={
		birth="553.1.1"
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
	}
```

### 592.1.1

```text
	592.1.1={
		death="592.1.1"
	}
```

## Full character block (verbatim)

```text
180645 = {
	name="Bahram"
	# Bahram VI, Emperor of Persia
	dynasty=1042070
	religion="zoroastrian"
	culture="persian"
	553.1.1={
		birth="553.1.1"
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
	}
	592.1.1={
		death="592.1.1"
	}
}
```
