# Seljuk — character 3030

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/turkish.txt` (line 2557), block `3030 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `3030` |
| Name | `"Seljuk"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `613` |
| Religion | `"sunni"` |
| Culture | `"turkish"` |
| Father | — (no `father=` line) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `8` | `4` | `4` | `5` | `3` |

## Traits (base entries, as in file)

- `brilliant_strategist`
- `wroth`
- `cruel`
- `proud`
- `zealous`
- `ambitious`

## Other top-level fields (as in file)

- `fertility = 0.8`
- `health = 7`

## Bloodline(s) (as in file)

### `seljuk` — granted 960.1.1

```text
		create_bloodline = {
			type = seljuk
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: — (no `father=` line)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (2 other block(s) with `father=3030` or `mother=3030`):
  - `father=3030`: `3032` — Arslan (`characters/turkish.txt`), born 985.1.2
  - `father=3030`: `3034` — Mikail (`characters/turkish.txt`), born 990.1.2

## Chronology (date order as in file; statements verbatim)

- **960.1.1** — `birth=yes; create_bloodline={ type = seljuk has_dlc = "Holy Fury" }`
- **1021.1.1** — `death=yes`

## History entries (verbatim)

### 960.1.1

```text
	960.1.1={
		birth=yes
		create_bloodline = {
			type = seljuk
			has_dlc = "Holy Fury"
		}
	}
```

### 1021.1.1

```text
	1021.1.1={
		death=yes
	}
```

## Full character block (verbatim)

```text
3030 = {
	name="Seljuk"
	dynasty=613
	martial = 8
	diplomacy = 4
	stewardship = 5
	intrigue = 4
	learning = 3
	religion="sunni"
	culture="turkish"
	health = 7
	fertility = 0.8
	trait = brilliant_strategist
	trait = wroth
	trait = cruel
	trait = proud
	trait = zealous
	trait = ambitious
	960.1.1={
		birth=yes
		create_bloodline = {
			type = seljuk
			has_dlc = "Holy Fury"
		}
	}
	1021.1.1={
		death=yes
	}
}
```
