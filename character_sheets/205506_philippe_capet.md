# Philippe — character 205506

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/frankish.txt` (line 3144), block `205506 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `205506` |
| Name | `"Philippe"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `743` |
| Religion | `"catholic"` |
| Culture | `"frankish"` |
| Father | `205500` — Louis (`characters/frankish.txt`) |
| Mother | `205505` — Adelaide (`characters/frankish.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `8` | `7` | `7` | `9` | — |

## Traits (base entries, as in file)

- `"ambitious"`
- `"quick"`
- `"brave"`
- `"honest"`
- `"just"`
- `"cynical"`

## Bloodline(s) (as in file)

### `philippe_capet` — granted 1190.6.24

```text
		create_bloodline = {
			type = philippe_capet
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `205500` — Louis (`characters/frankish.txt`)
- Mother: `205505` — Adelaide (`characters/frankish.txt`)
- Spouses:
  - added 1180.4.28: `205522` — Isabella (`characters/frankish.txt`)
  - added 1193.8.14: `201505` — Ingeborg (`characters/danish.txt`)
  - removed 1193.11.5: `201505` — Ingeborg (`characters/danish.txt`)
  - added 1196.6.1: `212944` — Agnes (`characters/german.txt`)
  - removed 1199.12.6: `212944` — Agnes (`characters/german.txt`)
  - added 1201.7.1: `201505` — Ingeborg (`characters/danish.txt`)
- Recorded children (7 other block(s) with `father=205506` or `mother=205506`):
  - `father=205506`: `91026` — Philippe (`characters/frankish.txt`), born 1190.3.15
  - `father=205506`: `91027` — Hugues (`characters/frankish.txt`), born 1190.3.15
  - `father=205506`: `91028` — Marie (`characters/frankish.txt`), born 1198.1.1
  - `father=205506`: `91029` — Jean (`characters/frankish.txt`), born 1200.1.1
  - `father=205506`: `91030` — Philippe (`characters/frankish.txt`), born 1200.7.1
  - `father=205506`: `91031` — Pierre (`characters/frankish.txt`), born 1205.1.1
  - `father=205506`: `455402` — Louis (`characters/frankish.txt`), born 1187.9.3

## Chronology (date order as in file; statements verbatim)

- **1165.8.21** — `birth="1165.8.21"`
- **1179.1.1** — `trait="wounded"`
- **1179.10.1** — `remove_trait="wounded"`
- **1180.4.28** — `add_spouse=205522`
- **1190.6.24** — `trait="crusader"; create_bloodline={ type = philippe_capet has_dlc = "Holy Fury" }`
- **1191.4.21** — `trait="ill"`
- **1191.7.3** — `remove_trait="ill"`
- **1191.12.27** — `remove_trait="crusader"`
- **1193.8.14** — `add_spouse=201505`
- **1193.11.5** — `remove_spouse=201505`
- **1196.6.1** — `add_spouse=212944`
- **1199.12.6** — `remove_spouse=212944`
- **1200.1.13** — `trait="excommunicated"`
- **1200.9.7** — `remove_trait="excommunicated"`
- **1201.7.1** — `add_spouse=201505`
- **1204.1.1** — `add_claim=d_poitou; add_claim=c_poitiers; add_claim=c_thouars; give_nickname=nick_the_great`
- **1222.9.1** — `trait="ill"`
- **1223.7.14** — `death="1223.7.14"`

## History entries (verbatim)

### 1165.8.21

```text
	1165.8.21 = {
		birth="1165.8.21"
	}
```

### 1179.1.1

```text
	1179.1.1 = {
		trait="wounded"
	}
```

### 1179.10.1

```text
	1179.10.1 = {
		remove_trait="wounded"
	}
```

### 1180.4.28

```text
	1180.4.28 = {
		add_spouse=205522 #Isabelle de Hainaut
	}
```

### 1190.6.24

```text
	1190.6.24 = {
		trait="crusader"
		create_bloodline = {
			type = philippe_capet
			has_dlc = "Holy Fury"
		}
	}
```

### 1191.4.21

```text
	1191.4.21 = {
		trait="ill"
	}
```

### 1191.7.3

```text
	1191.7.3 = {
		remove_trait="ill"
	}
```

### 1191.12.27

```text
	1191.12.27 = {
		remove_trait="crusader"
	}
```

### 1193.8.14

```text
	1193.8.14 = {
		add_spouse=201505 #Ingeburge de Danemark
	}
```

### 1193.11.5

```text
	1193.11.5 = {
		remove_spouse=201505 #Ingeburge de Danemark
	}
```

### 1196.6.1

```text
	1196.6.1 = {
		add_spouse=212944 #Agnès de Méranie
	}
```

### 1199.12.6

```text
	1199.12.6 = {
		remove_spouse=212944 #Agnès de Méranie
	}
```

### 1200.1.13

```text
	1200.1.13 = {
		trait="excommunicated"
	}
```

### 1200.9.7

```text
	1200.9.7 = {
		remove_trait="excommunicated"
	}
```

### 1201.7.1

```text
	1201.7.1 = {
		add_spouse=201505 #Ingeborg of Denmark
	}
```

### 1204.1.1

```text
	1204.1.1={
		add_claim = d_poitou
		add_claim = c_poitiers
		add_claim = c_thouars
		give_nickname=nick_the_great
	}
```

### 1222.9.1

```text
	1222.9.1 = {
		trait="ill"
	}
```

### 1223.7.14

```text
	1223.7.14 = {
		death="1223.7.14"
	}
```

## Full character block (verbatim)

```text
205506 = {
	name="Philippe" #Philippe II Auguste
	# AKA: Philippe Auguste
	dynasty=743 #Capetian
	martial=8
	diplomacy=7
	intrigue=7
	stewardship=9
	religion="catholic"
	culture="frankish"
	trait="ambitious"
	trait="quick"
	trait="brave"
	trait="honest"
	trait="just"
	trait="cynical"
	father=205500 #Louis VII le Jeune
	mother=205505 #Adèle de Champagne
	1165.8.21 = {
		birth="1165.8.21"
	}
	1179.1.1 = {
		trait="wounded"
	}
	1179.10.1 = {
		remove_trait="wounded"
	}
	1180.4.28 = {
		add_spouse=205522 #Isabelle de Hainaut
	}
	1190.6.24 = {
		trait="crusader"
		create_bloodline = {
			type = philippe_capet
			has_dlc = "Holy Fury"
		}
	}
	1191.4.21 = {
		trait="ill"
	}
	1191.7.3 = {
		remove_trait="ill"
	}
	1191.12.27 = {
		remove_trait="crusader"
	}
	1193.8.14 = {
		add_spouse=201505 #Ingeburge de Danemark
	}
	1193.11.5 = {
		remove_spouse=201505 #Ingeburge de Danemark
	}
	1196.6.1 = {
		add_spouse=212944 #Agnès de Méranie
	}
	1199.12.6 = {
		remove_spouse=212944 #Agnès de Méranie
	}
	1200.1.13 = {
		trait="excommunicated"
	}
	1200.9.7 = {
		remove_trait="excommunicated"
	}
	1201.7.1 = {
		add_spouse=201505 #Ingeborg of Denmark
	}
	1204.1.1={
		add_claim = d_poitou
		add_claim = c_poitiers
		add_claim = c_thouars
		give_nickname=nick_the_great
	}
	1222.9.1 = {
		trait="ill"
	}
	1223.7.14 = {
		death="1223.7.14"
	}
}
```
