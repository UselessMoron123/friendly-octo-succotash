# Sasan — character 159599

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/persian.txt` (line 3004), block `159599 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `159599` |
| Name | `"Sasan"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `1029100` |
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

### `sassanid` — granted 130.11.1

```text
		create_bloodline = {
			type = sassanid
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: — (no `father=` line)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=159599` or `mother=159599`):
  - `father=159599`: `159600` — Babak (`characters/persian.txt`), born 150.11.1

## Chronology (date order as in file; statements verbatim)

- **130.11.1** — `birth="130.11.1"; create_bloodline={ type = sassanid has_dlc = "Holy Fury" }`
- **200.1.1** — `death="200.1.1"`

## History entries (verbatim)

### 130.11.1

```text
	130.11.1={
		birth="130.11.1"
		create_bloodline = {
			type = sassanid
			has_dlc = "Holy Fury"
		}
	}
```

### 200.1.1

```text
	200.1.1={
		death="200.1.1"
	}
```

## Full character block (verbatim)

```text
159599 = { 
	name="Sasan" # II
	dynasty=1029100
	religion="zoroastrian"
	culture="persian"
	130.11.1={
		birth="130.11.1"
		create_bloodline = {
			type = sassanid
			has_dlc = "Holy Fury"
		}
	}
	200.1.1={
		death="200.1.1"
	}
}
```
