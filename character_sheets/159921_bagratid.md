# Bagrat — character 159921

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/armenian.txt` (line 7415), block `159921 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `159921` |
| Name | `"Bagrat"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `507` |
| Religion | `"zoroastrian"` |
| Culture | `"armenian"` |
| Father | `159920` — Smbat (`characters/armenian.txt`) |
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

### `bagratid` — granted 280.1.1

```text
		create_bloodline = {
			type = bagratid
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `159920` — Smbat (`characters/armenian.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=159921` or `mother=159921`):
  - `father=159921`: `159922` — Smbat (`characters/armenian.txt`), born 310.1.1

## Chronology (date order as in file; statements verbatim)

- **280.1.1** — `birth="280.1.1"; create_bloodline={ type = bagratid has_dlc = "Holy Fury" }`
- **343.1.1** — `death="343.1.1"`

## History entries (verbatim)

### 280.1.1

```text
	280.1.1={
		birth="280.1.1"
		create_bloodline = {
			type = bagratid
			has_dlc = "Holy Fury"
		}
	}
```

### 343.1.1

```text
	343.1.1={
		death="343.1.1"
	}
```

## Full character block (verbatim)

```text
159921 = {
	name="Bagrat" #
	dynasty=507
	religion="zoroastrian"
	culture="armenian"
	father=159920
	280.1.1={
		birth="280.1.1"
		create_bloodline = {
			type = bagratid
			has_dlc = "Holy Fury"
		}
	}
	343.1.1={
		death="343.1.1"
	}
}
```
