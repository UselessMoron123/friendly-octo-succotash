# Haraldr — character 144000

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/norse.txt` (line 2939), block `144000 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `144000` |
| Name | `"Haraldr"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `499` |
| Religion | `"norse_pagan"` |
| Culture | `norse` |
| Father | `168323` — Halfdan (`characters/norse.txt`) |
| Mother | `168649` — Rögnhildr (`characters/norse.txt`) |
| DNA | `"bhjaavafacj"` |
| Properties | `"0b00d0"` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `7` | `7` | `5` | `6` | `5` |

## Traits (base entries, as in file)

- `quick`
- `patient`
- `brave`
- `ambitious`
- `hunter`
- `"skilled_tactician"`

## Other top-level fields (as in file)

- `give_nickname = nick_fairhair`

## Bloodline(s) (as in file)

### `harald_fairhair` — granted 867.1.1

```text
		create_bloodline = {
			type = harald_fairhair
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `168323` — Halfdan (`characters/norse.txt`)
- Mother: `168649` — Rögnhildr (`characters/norse.txt`)
- Spouses:
  - added 867.1.1: `6862` — Rögnhildr (`characters/norse.txt`)
  - added 872.1.1: `166044` — Gyda (`characters/norse.txt`)
  - added 893.1.1: `161305` — Svanhildr (`characters/norse.txt`)
- Recorded children (7 other block(s) with `father=144000` or `mother=144000`):
  - `father=144000`: `102507` — Eirikr (`characters/norse.txt`), born 895.1.1
  - `father=144000`: `144001` — Hakon (`characters/norse.txt`), born 920.1.1
  - `father=144000`: `144002` — Olafr (`characters/norse.txt`), born 897.1.1
  - `father=144000`: `144005` — Björn (`characters/norse.txt`), born 894.1.1
  - `father=144000`: `144007` — Sigurdr (`characters/norse.txt`), born 895.1.1
  - `father=144000`: `166045` — Froði (`characters/norse.txt`), born 891.1.1
  - `father=144000`: `261159` — Ålov (`characters/norse.txt`), born 875.1.1

## Chronology (date order as in file; statements verbatim)

- **850.1.1** — `birth="850.1.1"`
- **867.1.1** — `create_bloodline={ type = harald_fairhair has_dlc = "Holy Fury" }; add_spouse=6862; prestige=400; dynasty=random; religion=ROOT; culture=ROOT; trait=tough_soldier; religion=ROOT; culture=ROOT; trait=tough_soldier`
- **872.1.1** — `add_spouse=166044`
- **893.1.1** — `add_spouse=161305`
- **933.1.1** — `death="933.1.1"`

## History entries (verbatim)

### 850.1.1

```text
	850.1.1={
		birth="850.1.1"
	}
```

### 867.1.1

```text
	867.1.1= {
		create_bloodline = {
			type = harald_fairhair
			has_dlc = "Holy Fury"
		}
		add_spouse = 6862
		
		prestige = 400
		
		effect = {
			spawn_unit = {
				province = 272 # Akershus
				owner = ROOT
				#leader = ROOT
				troops = {
					light_infantry = { 115 115 }
					heavy_infantry = { 6 6 }
					archers = { 34 34 }
				}
				attrition = 1.0
			}
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 29
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 272 # Akershus
					owner = PREV
					troops = {
						light_infantry = { 115 115 }
						heavy_infantry = { 6 6 }
						archers = { 34 34 }
					}
					attrition = 1.0
				}
			}
			create_character = {
				random_traits = yes
				religion = ROOT
				culture = ROOT
				female = no
				age = 25
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 272 # Akershus
					owner = PREV
					troops = {
						light_infantry = { 115 115 }
						heavy_infantry = { 6 6 }
						archers = { 34 34 }
					}
					attrition = 1.0
				}
			}
		}
	}
```

### 872.1.1

```text
	872.1.1= {
		add_spouse = 166044
	}
```

### 893.1.1

```text
	893.1.1= {
		add_spouse = 161305
	}
```

### 933.1.1

```text
	933.1.1={
		death="933.1.1"
	}
```

## Full character block (verbatim)

```text
144000 = {
	name="Haraldr" # "Fairhair"
	dynasty=499
	dna="bhjaavafacj"
	properties="0b00d0"
	religion="norse_pagan"
	culture=norse
	give_nickname = nick_fairhair
	martial = 7
	stewardship=6
	diplomacy = 7
	intrigue = 5
	learning = 5
	trait=quick
	trait=patient
	trait=brave
	trait=ambitious
	trait=hunter
	trait="skilled_tactician"
	father=168323
	mother=168649
	850.1.1={
		birth="850.1.1"
	}
	867.1.1= {
		create_bloodline = {
			type = harald_fairhair
			has_dlc = "Holy Fury"
		}
		add_spouse = 6862
		
		prestige = 400
		
		effect = {
			spawn_unit = {
				province = 272 # Akershus
				owner = ROOT
				#leader = ROOT
				troops = {
					light_infantry = { 115 115 }
					heavy_infantry = { 6 6 }
					archers = { 34 34 }
				}
				attrition = 1.0
			}
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 29
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 272 # Akershus
					owner = PREV
					troops = {
						light_infantry = { 115 115 }
						heavy_infantry = { 6 6 }
						archers = { 34 34 }
					}
					attrition = 1.0
				}
			}
			create_character = {
				random_traits = yes
				religion = ROOT
				culture = ROOT
				female = no
				age = 25
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 272 # Akershus
					owner = PREV
					troops = {
						light_infantry = { 115 115 }
						heavy_infantry = { 6 6 }
						archers = { 34 34 }
					}
					attrition = 1.0
				}
			}
		}
	}
	872.1.1= {
		add_spouse = 166044
	}
	893.1.1= {
		add_spouse = 161305
	}
	
	933.1.1={
		death="933.1.1"
	}
}
```
