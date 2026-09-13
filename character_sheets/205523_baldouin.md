# Boudewijn — character 205523

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/dutch.txt` (line 919), block `205523 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `205523` |
| Name | `"Boudewijn"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `724` |
| Religion | `"catholic"` |
| Culture | `"dutch"` |
| Father | `205520` — Boudewijn (`characters/dutch.txt`) |
| Mother | `212589` — Margaretha (`characters/german.txt`) |
| DNA | `izdlkpmiyat` |
| Properties | `ej0000000000000000` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `5` | `4` | `7` | `6` | — |

## Traits (base entries, as in file)

_None at top level._

## Bloodline(s) (as in file)

### `baldouin` — granted 1204.5.16

```text
		create_bloodline = {
			type = baldouin
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `205520` — Boudewijn (`characters/dutch.txt`)
- Mother: `212589` — Margaretha (`characters/german.txt`)
- Spouses:
  - added 1186.1.1: `205965` — Marie (`characters/frankish.txt`)
- Recorded children (2 other block(s) with `father=205523` or `mother=205523`):
  - `father=205523`: `94021` — Johanna (`characters/dutch.txt`), born 1194.1.1
  - `father=205523`: `94024` — Margaretha (`characters/frankish.txt`), born 1202.7.1

## Chronology (date order as in file; statements verbatim)

- **1171.7.1** — `birth="1171.7.1"`
- **1186.1.1** — `add_spouse=205965`
- **1204.5.16** — `name="Baudouin"; add_claim=c_mesembria; add_claim=c_karvuna; add_claim=c_tyrnovo; add_claim=c_strymon; add_claim=d_thessalonika; add_claim=d_athens; add_claim=d_epirus; add_claim=d_achaia; add_claim=d_nikaea; add_claim=d_samos; create_bloodline={ type = baldouin has_dlc = "Holy Fury" }; dynasty=random; religion=ROOT; culture=ROOT; trait=tough_soldier; dynasty=random; religion=ROOT; culture=ROOT; trait=tough_soldier; dynasty=random; religion=ROOT; culture=ROOT; trait=tough_soldier`
- **1204.5.16** — `culture="frankish"`
- **1205.6.1** — `death="1205.6.1"`

## History entries (verbatim)

### 1171.7.1

```text
	1171.7.1={
		birth="1171.7.1"
	}
```

### 1186.1.1

```text
	1186.1.1={
		add_spouse=205965
	}
```

### 1204.5.16

```text
	1204.5.16={
		name="Baudouin" 
		add_claim = c_mesembria
		add_claim = c_karvuna
		add_claim = c_tyrnovo
		add_claim = c_strymon
		add_claim = d_thessalonika
		add_claim = d_athens
		add_claim = d_epirus
		add_claim = d_achaia
		add_claim = d_nikaea
		add_claim = d_samos
		create_bloodline = {
			type = baldouin
			has_dlc = "Holy Fury"
		}
		
		effect = {
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 23
				attributes = {
					martial = 6
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 496 # Constantinople
					owner = PREV
					troops = {
						light_infantry = { 1200 1200 }
						heavy_infantry = { 737 737 }
						pikemen = { 237 237 }
						archers = { 795 795 }
						light_cavalry = { 331 331 }
						knights = { 132 132 }
					}
				}
			}
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 30
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 496 # Constantinople
					owner = PREV
					troops = {
						light_infantry = { 1200 1200 }
						heavy_infantry = { 737 737 }
						pikemen = { 237 237 }
						archers = { 795 795 }
						light_cavalry = { 331 331 }
						knights = { 132 132 }
					}
				}
			}
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 27
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 496 # Constantinople
					owner = PREV
					troops = {
						light_infantry = { 1200 1200 }
						heavy_infantry = { 737 737 }
						pikemen = { 237 237 }
						archers = { 795 795 }
						light_cavalry = { 331 331 }
						knights = { 132 132 }
					}
				}
			}
		}
	}
```

### 1204.5.16

```text
	1204.5.16={
		culture="frankish"
	}
```

### 1205.6.1

```text
	1205.6.1={
		death="1205.6.1"
	}
```

## Full character block (verbatim)

```text
205523 = {
	name="Boudewijn" #Boudewijn IX + I
	# AKA: Baudouin
	dna = izdlkpmiyat
	properties = ej0000000000000000
	dynasty=724
	martial=5
	diplomacy=4
	intrigue=7
	stewardship=6
	religion="catholic"
	culture="dutch"
	father=205520
	mother=212589
	1171.7.1={
		birth="1171.7.1"
	}
	1186.1.1={
		add_spouse=205965
	}
	1204.5.16={
		name="Baudouin" 
		add_claim = c_mesembria
		add_claim = c_karvuna
		add_claim = c_tyrnovo
		add_claim = c_strymon
		add_claim = d_thessalonika
		add_claim = d_athens
		add_claim = d_epirus
		add_claim = d_achaia
		add_claim = d_nikaea
		add_claim = d_samos
		create_bloodline = {
			type = baldouin
			has_dlc = "Holy Fury"
		}
		
		effect = {
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 23
				attributes = {
					martial = 6
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 496 # Constantinople
					owner = PREV
					troops = {
						light_infantry = { 1200 1200 }
						heavy_infantry = { 737 737 }
						pikemen = { 237 237 }
						archers = { 795 795 }
						light_cavalry = { 331 331 }
						knights = { 132 132 }
					}
				}
			}
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 30
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 496 # Constantinople
					owner = PREV
					troops = {
						light_infantry = { 1200 1200 }
						heavy_infantry = { 737 737 }
						pikemen = { 237 237 }
						archers = { 795 795 }
						light_cavalry = { 331 331 }
						knights = { 132 132 }
					}
				}
			}
			create_character = {
				random_traits = yes
				dynasty = random
				religion = ROOT
				culture = ROOT
				female = no
				age = 27
				attributes = {
					martial = 5
				}
				trait = tough_soldier
			}
			new_character = {
				spawn_unit = {
					province = 496 # Constantinople
					owner = PREV
					troops = {
						light_infantry = { 1200 1200 }
						heavy_infantry = { 737 737 }
						pikemen = { 237 237 }
						archers = { 795 795 }
						light_cavalry = { 331 331 }
						knights = { 132 132 }
					}
				}
			}
		}
	}	
	1204.5.16={
		culture="frankish"
	}
	1205.6.1={
		death="1205.6.1"
	}
}
```
