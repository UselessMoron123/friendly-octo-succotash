# Ragnarr — character 163109

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/norse.txt` (line 3665), block `163109 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `163109` |
| Name | `"Ragnarr"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `502` |
| Religion | `"norse_pagan"` |
| Culture | `"norse"` |
| Father | `194004` — Sigurdr (`characters/norse.txt`) |
| Mother | `194056` — Alfhildr (`characters/norse.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `9` | `5` | `5` | `7` | `3` |

## Traits (base entries, as in file)

_None at top level._

## Bloodline(s) (as in file)

### `ragnarr_lodbrok` — granted 818.1.1

```text
		create_bloodline = {
			type = ragnarr_lodbrok
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `194004` — Sigurdr (`characters/norse.txt`)
- Mother: `194056` — Alfhildr (`characters/norse.txt`)
- Spouses:
  - added 818.1.1: `6836` — Aslaug (`characters/norse.txt`)
- Recorded children (5 other block(s) with `father=163109` or `mother=163109`):
  - `father=163109`: `163108` — Björn (`characters/norse.txt`), born 821.1.1
  - `father=163109`: `163110` — Sigurdr (`characters/norse.txt`), born 840.1.1
  - `father=163109`: `163111` — Ivar (`characters/norse.txt`), born 818.2.7
  - `father=163109`: `163112` — Halfdan (`characters/norse.txt`), born 825.1.1
  - `father=163109`: `163119` — Ubbe (`characters/norse.txt`), born 827.1.1

## Chronology (date order as in file; statements verbatim)

- **766.6.6** — `birth=yes`
- **800.1.1** — `add_trait=wroth; add_trait=hunter; add_trait=strong; add_trait=brave; add_trait=viking; add_trait=skilled_tactician`
- **818.1.1** — `add_spouse=6836; give_nickname=nick_lodbrok; create_bloodline={ type = ragnarr_lodbrok has_dlc = "Holy Fury" }`
- **860.1.1** — `death={ death_reason = death_execution killer = 163103 }`

## History entries (verbatim)

### 766.6.6

```text
	766.6.6 = {
		birth = yes
		effect = { set_character_flag = is_ragnar_lodbrok }
	}
```

### 800.1.1

```text
	800.1.1 = {
		add_trait=wroth
		add_trait=hunter
		add_trait=strong
		add_trait=brave
		add_trait=viking
		add_trait=skilled_tactician
	}
```

### 818.1.1

```text
	818.1.1={
		add_spouse=6836
		give_nickname = nick_lodbrok
		create_bloodline = {
			type = ragnarr_lodbrok
			has_dlc = "Holy Fury"
		}
	}
```

### 860.1.1

```text
	860.1.1={
		death = {
			death_reason = death_execution
			killer = 163103 # Aella of Northumberland
		}
	}
```

## Full character block (verbatim)

```text
163109 = {
	name="Ragnarr" # Lodbrok
	dynasty=502
	father = 194004 # Sigurd Ring
	mother = 194056 # Alfhild of Alfheim
	religion="norse_pagan"
	culture="norse"
	martial=9
	stewardship=7
	diplomacy=5
	intrigue=5
	learning=3
	
	766.6.6 = {
		birth = yes
		effect = { set_character_flag = is_ragnar_lodbrok }
	}
	800.1.1 = {
		add_trait=wroth
		add_trait=hunter
		add_trait=strong
		add_trait=brave
		add_trait=viking
		add_trait=skilled_tactician
	}
	818.1.1={
		add_spouse=6836
		give_nickname = nick_lodbrok
		create_bloodline = {
			type = ragnarr_lodbrok
			has_dlc = "Holy Fury"
		}
	}
	860.1.1={
		death = {
			death_reason = death_execution
			killer = 163103 # Aella of Northumberland
		}
	}
}
```
