# Bohemond — character 1140

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/norman.txt` (line 684), block `1140 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `1140` |
| Name | `"Bohemond"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `678` |
| Religion | `"catholic"` |
| Culture | `"norman"` |
| Father | `1128` — Robert (`characters/norman.txt`) |
| Mother | `10003` — Alberada (`characters/norman.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `8` | `7` | `8` | `6` | — |

## Traits (base entries, as in file)

- `"brave"`
- `"cynical"`
- `"wroth"`
- `"brilliant_strategist"`
- `"sturdy"`

## Other top-level fields (as in file)

- `disallow_random_traits = yes`

## Bloodline(s) (as in file)

### `bohemond` — granted 1098.6.3

```text
		create_bloodline = {
			type = bohemond
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `1128` — Robert (`characters/norman.txt`)
- Mother: `10003` — Alberada (`characters/norman.txt`)
- Spouses:
  - added 1105.1.1: `205511` — Constance (`characters/frankish.txt`)
- Recorded children (1 other block(s) with `father=1140` or `mother=1140`):
  - `father=1140`: `223700` — Bohemond (`characters/frankish.txt`), born 1108.1.2

## Chronology (date order as in file; statements verbatim)

- **1058.1.1** — `birth="1058.1.1"`
- **1098.6.3** — `create_bloodline={ type = bohemond has_dlc = "Holy Fury" }; add_trait=crusader`
- **1105.1.1** — `add_spouse=205511`
- **1111.3.3** — `death="1111.3.3"`

## History entries (verbatim)

### 1058.1.1

```text
	1058.1.1 = {
		birth="1058.1.1"
	}
```

### 1098.6.3

```text
	1098.6.3 = {
		create_bloodline = {
			type = bohemond
			has_dlc = "Holy Fury"
		}
		add_trait = crusader
	}
```

### 1105.1.1

```text
	1105.1.1 = {
		add_spouse=205511
	}
```

### 1111.3.3

```text
	1111.3.3 = {
		death="1111.3.3"
	}
```

## Full character block (verbatim)

```text
1140 = {
	name="Bohemond"
	dynasty=678
	martial=8
	diplomacy=7
	intrigue=8
	stewardship=6
	religion="catholic"
	culture="norman"
	trait="brave"
	trait="cynical"
	trait="wroth"
	trait="brilliant_strategist"
	trait="sturdy"
	disallow_random_traits = yes
	father=1128
	mother=10003
	1058.1.1 = {
		birth="1058.1.1"
	}
	1098.6.3 = {
		create_bloodline = {
			type = bohemond
			has_dlc = "Holy Fury"
		}
		add_trait = crusader
	}
	1105.1.1 = {
		add_spouse=205511
	}
	1111.3.3 = {
		death="1111.3.3"
	}
}
```
