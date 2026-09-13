# Afonso — character 209503

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/portuguese.txt` (line 383), block `209503 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `209503` |
| Name | `"Afonso"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `741` |
| Religion | `"catholic"` |
| Culture | `"portuguese"` |
| Father | `6531` — Henri (`characters/frankish.txt`) |
| Mother | `207661` — Teresa (`characters/castillan.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

- `"ambitious"`

## Bloodline(s) (as in file)

### `alfonso_portugal` — granted 1139.7.27

```text
		create_bloodline = {
			type = alfonso_portugal
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `6531` — Henri (`characters/frankish.txt`)
- Mother: `207661` — Teresa (`characters/castillan.txt`)
- Spouses:
  - added 1146.6.1: `212672` — Mathilde (`characters/frankish.txt`)
- Recorded children (11 other block(s) with `father=209503` or `mother=209503`):
  - `father=209503`: `91095` — Henrique (`characters/portuguese.txt`), born 1147.2.17
  - `father=209503`: `91096` — Mafalda (`characters/portuguese.txt`), born 1149.1.1
  - `father=209503`: `91111` — João (`characters/portuguese.txt`), born 1159.1.1
  - `father=209503`: `91112` — Sancha (`characters/portuguese.txt`), born 1153.1.1
  - `father=209503`: `142024` — Pedro (`characters/portuguese.txt`), born 1140.1.1
  - `father=209503`: `142025` — Teresa (`characters/portuguese.txt`), born 1130.1.1
  - `father=209503`: `142026` — Urraca (`characters/portuguese.txt`), born 1130.1.1
  - `father=209503`: `142132` — Fernando (`characters/portuguese.txt`), born 1135.1.1
  - `father=209503`: `209500` — Sancho (`characters/portuguese.txt`), born 1154.11.11
  - `father=209503`: `209501` — Urraca (`characters/portuguese.txt`), born 1151.1.1
  - `father=209503`: `209510` — Teresa (`characters/portuguese.txt`), born 1156.1.1

## Chronology (date order as in file; statements verbatim)

- **1109.7.25** — `birth="1109.7.25"`
- **1112.5.22** — `add_claim=d_porto; add_claim=c_porto; add_claim=c_coimbra`
- **1128.6.24** — `(see verbatim block below)`
- **1139.7.27** — `give_nickname=nick_the_conqueror; create_bloodline={ type = alfonso_portugal has_dlc = "Holy Fury" }`
- **1146.6.1** — `add_spouse=212672`
- **1185.12.6** — `death="1185.12.6"`

## History entries (verbatim)

### 1109.7.25

```text
	1109.7.25={
		birth="1109.7.25"
	}
```

### 1112.5.22

```text
	1112.5.22={
		add_claim = d_porto
		add_claim = c_porto
		add_claim = c_coimbra
	}
```

### 1128.6.24

```text
	1128.6.24={
		remove_claim = d_porto
		remove_claim = c_porto
		remove_claim = c_coimbra
	}
```

### 1139.7.27

```text
	1139.7.27={
		give_nickname=nick_the_conqueror
		create_bloodline = {
			type = alfonso_portugal
			has_dlc = "Holy Fury"
		}
	}
```

### 1146.6.1

```text
	1146.6.1={
		add_spouse=212672 #Maud of Savoy
	}
```

### 1185.12.6

```text
	1185.12.6={
		death="1185.12.6"
	}
```

## Full character block (verbatim)

```text
209503 = {
	name="Afonso" #Afonso I Henriques the Conqueror
	dynasty=741 #de Bourgogne
	religion="catholic"
	culture="portuguese"
	trait="ambitious"
	father=6531 #Henri de Bourgogne
	mother=207661 #Teresa of Leon
	1109.7.25={
		birth="1109.7.25"
	}
	1112.5.22={
		add_claim = d_porto
		add_claim = c_porto
		add_claim = c_coimbra
	}
	1128.6.24={
		remove_claim = d_porto
		remove_claim = c_porto
		remove_claim = c_coimbra
	}
	1139.7.27={
		give_nickname=nick_the_conqueror
		create_bloodline = {
			type = alfonso_portugal
			has_dlc = "Holy Fury"
		}
	}
	1146.6.1={
		add_spouse=212672 #Maud of Savoy
	}
	1185.12.6={
		death="1185.12.6"
	}
}
```
