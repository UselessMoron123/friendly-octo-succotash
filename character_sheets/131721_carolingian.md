# Karl — character 131721

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/old_frankish.txt` (line 3830), block `131721 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `131721` |
| Name | `"Karl"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `25061` |
| Religion | `"catholic"` |
| Culture | `"old_frankish"` |
| Father | `131720` — Pepin (`characters/old_frankish.txt`) |
| Mother | `190420` — Chalpais (`characters/old_frankish.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `10` | `10` | `9` | `10` | `8` |

## Traits (base entries, as in file)

- `"brilliant_strategist"`
- `"quick"`
- `"brave"`
- `"strong"`
- `"ambitious"`

## Bloodline(s) (as in file)

### `carolingian` — granted 732.11.1

```text
		create_bloodline = {
			type = carolingian
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `131720` — Pepin (`characters/old_frankish.txt`)
- Mother: `190420` — Chalpais (`characters/old_frankish.txt`)
- Spouses:
  - added 707.1.1: `190425` — Chrothrudis (`characters/old_frankish.txt`)
  - removed 725.1.1: `190425` — Chrothrudis (`characters/old_frankish.txt`)
  - added 725.2.1: `190426` — Suanachildis (`characters/german.txt`)
- Recorded children (9 other block(s) with `father=131721` or `mother=131721`):
  - `father=131721`: `131722` — Pepin (`characters/old_frankish.txt`), born 714.1.1
  - `father=131721`: `144989` — Grifo (`characters/old_frankish.txt`), born 726.1.1
  - `father=131721`: `168128` — Aldana (`characters/old_frankish.txt`), born 735.1.1
  - `father=131721`: `168161` — Jérôme (`characters/old_frankish.txt`), born 705.1.1
  - `father=131721`: `168624` — Bernard (`characters/old_frankish.txt`), born 732.1.1
  - `father=131721`: `190427` — Karloman (`characters/old_frankish.txt`), born 706.1.1
  - `father=131721`: `190433` — Chiltrudis (`characters/old_frankish.txt`), born 725.1.1
  - `father=131721`: `190436` — Landrada (`characters/old_frankish.txt`), born 729.1.1
  - `father=131721`: `190449` — Remigius (`characters/old_frankish.txt`), born 740.1.1

## Chronology (date order as in file; statements verbatim)

- **686.8.23** — `birth="686.8.23"`
- **707.1.1** — `add_spouse=190425`
- **725.1.1** — `remove_spouse=190425`
- **725.2.1** — `add_spouse=190426`
- **732.11.1** — `give_nickname=nick_the_hammer; create_bloodline={ type = carolingian has_dlc = "Holy Fury" }`
- **741.1.23** — `death="741.1.23"`

## History entries (verbatim)

### 686.8.23

```text
	686.8.23 = {
		birth="686.8.23"
	}
```

### 707.1.1

```text
	707.1.1={
		add_spouse=190425
	}
```

### 725.1.1

```text
	725.1.1={
		remove_spouse=190425
	}
```

### 725.2.1

```text
	725.2.1={
		add_spouse=190426
	}
```

### 732.11.1

```text
	732.11.1 = {
		give_nickname = nick_the_hammer
		create_bloodline = {
			type = carolingian
			has_dlc = "Holy Fury"
		}
	}
```

### 741.1.23

```text
	741.1.23 = {
		death="741.1.23"
	}
```

## Full character block (verbatim)

```text
131721 = {
	name="Karl"
	# AKA: Charles 'Martel'
	dynasty=25061
	religion="catholic"
	culture="old_frankish"
	martial=10
	diplomacy=10
	intrigue=9
	stewardship=10
	learning=8
	trait="brilliant_strategist"
	trait="quick"
	trait="brave"
	trait="strong"
	trait="ambitious"
	father=131720
	mother=190420
	686.8.23 = {
		birth="686.8.23"
	}
	707.1.1={
		add_spouse=190425
	}
	725.1.1={
		remove_spouse=190425
	}
	725.2.1={
		add_spouse=190426
	}
	732.11.1 = {
		give_nickname = nick_the_hammer
		create_bloodline = {
			type = carolingian
			has_dlc = "Holy Fury"
		}
	}
	741.1.23 = {
		death="741.1.23"
	}
}
```
