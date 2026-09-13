# Erdewan — character 159551

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/kurdish.txt` (line 1437), block `159551 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `159551` |
| Name | `"Erdewan"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `1029098` |
| Religion | `"zoroastrian"` |
| Culture | `"kurdish"` |
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

### `parthian` — granted 70.11.1

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
- Recorded children (1 other block(s) with `father=159551` or `mother=159551`):
  - `father=159551`: `159552` — Karen (`characters/kurdish.txt`), born 90.11.1

## Chronology (date order as in file; statements verbatim)

- **70.11.1** — `birth="70.11.1"; create_bloodline={ type = parthian has_dlc = "Holy Fury" }`
- **140.8.29** — `death="140.8.29"`

## History entries (verbatim)

### 70.11.1

```text
	70.11.1={
		birth="70.11.1"
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
	}
```

### 140.8.29

```text
	140.8.29={
		death="140.8.29"
	}
```

## Full character block (verbatim)

```text
159551 = {
	name="Erdewan" #Ardavan
	dynasty=1029098
	religion="zoroastrian"
	culture="kurdish"
	# father=159547 no source
	70.11.1={
		birth="70.11.1"
		create_bloodline = {
			type = parthian
			has_dlc = "Holy Fury"
		}
	}
	140.8.29={
		death="140.8.29"
	}
}
```
