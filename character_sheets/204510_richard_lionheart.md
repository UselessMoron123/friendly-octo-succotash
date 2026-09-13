# Richard — character 204510

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/english.txt` (line 746), block `204510 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `204510` |
| Name | `"Richard"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `106` |
| Religion | `"catholic"` |
| Culture | `"english"` |
| Father | `204500` — Henry (`characters/english.txt`) |
| Mother | `205730` — Aliénor (`characters/occitan.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `6` | `6` | `6` | `6` | — |

## Traits (base entries, as in file)

- `"chaste"`
- `"brave"`
- `"fair"`
- `"proud"`
- `"brilliant_strategist"`

## Bloodline(s) (as in file)

### `richard_lionheart` — granted 1187.1.1

```text
		create_bloodline = {
			type = richard_lionheart
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `204500` — Henry (`characters/english.txt`)
- Mother: `205730` — Aliénor (`characters/occitan.txt`)
- Spouses:
  - added 1191.5.1: `206501` — Berengaria (`characters/basque.txt`)
- Recorded children (1 other block(s) with `father=204510` or `mother=204510`):
  - `father=204510`: `232000` — Philip (`characters/english.txt`), born 1181.1.2

## Chronology (date order as in file; statements verbatim)

- **1157.9.8** — `birth="1157.9.8"`
- **1187.1.1** — `give_nickname=nick_the_lionheart; trait="crusader"; create_bloodline={ type = richard_lionheart has_dlc = "Holy Fury" }`
- **1191.5.1** — `add_spouse=206501`
- **1199.4.6** — `death="1199.4.6"`

## History entries (verbatim)

### 1157.9.8

```text
	1157.9.8 = {
		birth="1157.9.8"
	}
```

### 1187.1.1

```text
	1187.1.1 = {
		give_nickname=nick_the_lionheart
		trait="crusader"
		create_bloodline = {
			type = richard_lionheart
			has_dlc = "Holy Fury"
		}
	}
```

### 1191.5.1

```text
	1191.5.1 = {
		add_spouse=206501 #Berengaria de Navarra
	}
```

### 1199.4.6

```text
	1199.4.6 = {
		death="1199.4.6"
	}
```

## Full character block (verbatim)

```text
204510 = {
	name="Richard"
	# AKA: Richard the Lionheart
	dynasty=106
	martial=6
	diplomacy=6
	intrigue=6
	stewardship=6
	religion="catholic"
	culture="english"
	trait="chaste"
	trait="brave"
	trait="fair"
	trait="proud"
	trait="brilliant_strategist"
	father=204500
	mother=205730
	1157.9.8 = {
		birth="1157.9.8"
	}
	1187.1.1 = {
		give_nickname=nick_the_lionheart
		trait="crusader"
		create_bloodline = {
			type = richard_lionheart
			has_dlc = "Holy Fury"
		}
	}
	1191.5.1 = {
		add_spouse=206501 #Berengaria de Navarra
	}	
	1199.4.6 = {
		death="1199.4.6"
	}
}
```
