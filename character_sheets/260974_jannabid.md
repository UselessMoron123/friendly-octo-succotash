# Sa'id — character 260974

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/bedouin_arabic.txt` (line 15303), block `260974 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `260974` |
| Name | `"Sa'id"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `12279` |
| Religion | `qarmatian` |
| Culture | `bedouin_arabic` |
| Father | `74039` — Bahram (`characters/bedouin_arabic.txt`) |
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

### `jannabid` — granted 899.1.1

```text
		create_bloodline = {
			type = jannabid
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `74039` — Bahram (`characters/bedouin_arabic.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (2 other block(s) with `father=260974` or `mother=260974`):
  - `father=260974`: `260975` — Abu'l-Qasim (`characters/bedouin_arabic.txt`), born 902.1.1
  - `father=260974`: `260976` — Abu Tahir (`characters/bedouin_arabic.txt`), born 906.1.1

## Chronology (date order as in file; statements verbatim)

- **855.1.1** — `birth=yes`
- **899.1.1** — `create_bloodline={ type = jannabid has_dlc = "Holy Fury" }`
- **913.1.1** — `death=yes`

## History entries (verbatim)

### 855.1.1

```text
	855.1.1 = {
		birth = yes
	}
```

### 899.1.1

```text
	899.1.1 = {
		create_bloodline = {
			type = jannabid
			has_dlc = "Holy Fury"
		}
	}
```

### 913.1.1

```text
	913.1.1 = {
		death = yes
	}
```

## Full character block (verbatim)

```text
260974 = {
	name = "Sa'id"
	dynasty = 12279
	culture = bedouin_arabic
	religion = qarmatian
	father = 74039
	855.1.1 = {
		birth = yes
	}
	899.1.1 = {
		create_bloodline = {
			type = jannabid
			has_dlc = "Holy Fury"
		}
	}
	913.1.1 = {
		death = yes
	}
}
```
