# Boleslaw — character 756

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/polish.txt` (line 2326), block `756 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `756` |
| Name | `"Boleslaw"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `699` |
| Religion | `"catholic"` |
| Culture | `"polish"` |
| Father | `754` — Mieszko (`characters/polish.txt`) |
| Mother | `509` — Doubravka (`characters/bohemian.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `8` | `7` | `8` | `7` | — |

## Traits (base entries, as in file)

- `"brave"`
- `"skilled_tactician"`

## Other top-level fields (as in file)

- `give_nickname = "nick_the_brave"`

## Bloodline(s) (as in file)

### `boleslaw_the_brave` — granted 967.1.2

```text
		create_bloodline = {
			type = boleslaw_the_brave
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `754` — Mieszko (`characters/polish.txt`)
- Mother: `509` — Doubravka (`characters/bohemian.txt`)
- Spouses:
  - added 985.1.2: `463` — Judit (`characters/hungarian.txt`)
  - removed 987.1.2: `463` — Judit (`characters/hungarian.txt`)
  - added 987.1.2: `757` — Emnilde (`characters/polish.txt`)
- Recorded children (2 other block(s) with `father=756` or `mother=756`):
  - `father=756`: `758` — Mieszko (`characters/polish.txt`), born 990.1.2
  - `father=756`: `766` — Bezprym (`characters/polish.txt`), born 986.1.2

## Chronology (date order as in file; statements verbatim)

- **967.1.2** — `birth="967.1.2"; create_bloodline={ type = boleslaw_the_brave has_dlc = "Holy Fury" }`
- **985.1.2** — `add_spouse=463`
- **987.1.2** — `remove_spouse=463`
- **987.1.2** — `add_spouse=757`
- **1025.6.17** — `death="1025.6.17"`

## History entries (verbatim)

### 967.1.2

```text
	967.1.2={
		birth="967.1.2"
		create_bloodline = {
			type = boleslaw_the_brave
			has_dlc = "Holy Fury"
		}
	}
```

### 985.1.2

```text
	985.1.2={
		add_spouse=463
	}
```

### 987.1.2

```text
	987.1.2={
	remove_spouse=463
	}
```

### 987.1.2

```text
	987.1.2={
		add_spouse=757
	}
```

### 1025.6.17

```text
	1025.6.17={
		death="1025.6.17"
	}
```

## Full character block (verbatim)

```text
756 = {
	name="Boleslaw"
	dynasty=699
	martial=8
	diplomacy=7
	intrigue=8
	stewardship=7
	religion="catholic"
	culture="polish"
	trait="brave"
	trait="skilled_tactician"
	give_nickname="nick_the_brave"
	father=754
	mother=509
	967.1.2={
		birth="967.1.2"
		create_bloodline = {
			type = boleslaw_the_brave
			has_dlc = "Holy Fury"
		}
	}
	985.1.2={
		add_spouse=463
	}
	987.1.2={
	remove_spouse=463
	}
	987.1.2={
		add_spouse=757
	}
	1025.6.17={
		death="1025.6.17"
	}
}
```
