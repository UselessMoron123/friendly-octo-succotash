# William — character 140

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/norman.txt` (line 1033), block `140 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `140` |
| Name | `"William"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `752` |
| Religion | `"catholic"` |
| Culture | `"norman"` |
| Father | `252` — Robert (`characters/norman.txt`) |
| Mother | `41001` — Herleva (`characters/norman.txt`) |
| DNA | `cagfktibaal` |
| Properties | `fj0dcd000000` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `7` | `7` | `10` | `6` | — |

## Traits (base entries, as in file)

- `"ambitious"`
- `"diligent"`
- `"proud"`
- `"cynical"`
- `"brave"`
- `"temperate"`
- `"patient"`
- `"legit_bastard"`
- `"brilliant_strategist"`

## Bloodline(s) (as in file)

### `william_the_conqueror` — granted 1066.12.25

```text
		create_bloodline = {
			type = william_the_conqueror
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `252` — Robert (`characters/norman.txt`)
- Mother: `41001` — Herleva (`characters/norman.txt`)
- Spouses:
  - added 1053.1.1: `367` — Mathilde (`characters/dutch.txt`)
- Recorded children (8 other block(s) with `father=140` or `mother=140`):
  - `father=140`: `141` — Agathe (`characters/norman.txt`), born 1064.1.1
  - `father=140`: `142` — Robert (`characters/norman.txt`), born 1054.1.1
  - `father=140`: `143` — Constance (`characters/norman.txt`), born 1061.1.1
  - `father=140`: `144` — Richard (`characters/norman.txt`), born 1055.1.1
  - `father=140`: `146` — William (`characters/norman.txt`), born 1056.1.1
  - `father=140`: `147` — Cecilia (`characters/norman.txt`), born 1057.1.1
  - `father=140`: `202992` — Henry (`characters/norman.txt`), born 1068.9.1
  - `father=140`: `205898` — Adele (`characters/norman.txt`), born 1067.1.1

## Chronology (date order as in file; statements verbatim)

- **1027.1.15** — `birth=yes`
- **1035.7.3** — `give_nickname=nick_the_bastard`
- **1053.1.1** — `add_spouse=367`
- **1066.1.5** — `add_claim=k_england`
- **1066.9.14** — `(see verbatim block below)`
- **1066.10.14** — `(see verbatim block below)`
- **1066.12.25** — `give_nickname=nick_the_conqueror; create_bloodline={ type = william_the_conqueror has_dlc = "Holy Fury" }`
- **1087.9.9** — `death=yes`

## History entries (verbatim)

### 1027.1.15

```text
	1027.1.15 = {
		birth=yes
	}
```

### 1035.7.3

```text
	1035.7.3 = {
		give_nickname=nick_the_bastard
	}
```

### 1053.1.1

```text
	1053.1.1 = {
		add_spouse=367 # Mathilda of Flanders
	}
```

### 1066.1.5

```text
	1066.1.5 = {
		add_claim=k_england
	}
```

### 1066.9.14

```text
	1066.9.14 = {
		wealth=1000
		
		raise_levies = {
			location=97 # Rouen
			force_mult=1.0
		}
		
		effect = {
			set_global_flag = williams_invasion_of_england
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = ROOT
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
			}
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = 148 # Odo of Bayeux
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
			}
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = 6818 # William of Eu
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
			}
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = 150 # Robert of Mortain
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
				merge = yes # Merge all armies in this province
			}
			spawn_fleet = {
				province = 97 # Rouen
				owner = ROOT
				earmark = williams_invasion_fleet
				disband_on_peace = yes
				troops =
				{
					galleys = { 180 180 }
				}
			}
		}
	}
```

### 1066.10.14

```text
	1066.10.14 = {
		raise_levies = {
			dismiss=yes
			location=97 # Rouen
			force_mult=1.0
		}
		effect = {
			clr_global_flag = williams_invasion_of_england
			disband_event_forces = yes
		}
	}
```

### 1066.12.25

```text
	1066.12.25  = {
		remove_claim=k_england
		give_nickname=nick_the_conqueror
		create_bloodline = {
			type = william_the_conqueror
			has_dlc = "Holy Fury"
		}
	}
```

### 1087.9.9

```text
	1087.9.9 = {
		death=yes
	}
```

## Full character block (verbatim)

```text
140 = {
	name="William"
	# AKA: William 'the Conqueror'
	dynasty=752
	dna = cagfktibaal
	properties = fj0dcd000000
	martial=7
	diplomacy=7
	intrigue=10
	stewardship=6
	religion="catholic"
	culture="norman"
	trait="ambitious"
	trait="diligent"
	trait="proud"
	trait="cynical"
	trait="brave"
	trait="temperate"
	trait="patient"
	trait="legit_bastard"
	trait="brilliant_strategist"
	father=252
	mother=41001
	1027.1.15 = {
		birth=yes
	}
	1035.7.3 = {
		give_nickname=nick_the_bastard
	}
	1053.1.1 = {
		add_spouse=367 # Mathilda of Flanders
	}
	1066.1.5 = {
		add_claim=k_england
	}
	1066.9.14 = {
		wealth=1000
		
		raise_levies = {
			location=97 # Rouen
			force_mult=1.0
		}
		
		effect = {
			set_global_flag = williams_invasion_of_england
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = ROOT
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
			}
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = 148 # Odo of Bayeux
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
			}
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = 6818 # William of Eu
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
			}
			spawn_unit = {
				province = 97 # Rouen
				owner = ROOT
				#leader = 150 # Robert of Mortain
				troops = {
					light_infantry = { 767 767 }
					heavy_infantry = { 766 766 }
					pikemen = { 152 152 }
					light_cavalry = { 285 285 }
					knights = { 114 114 }
					archers = { 439 439 }
				}
				attrition = 1.0
				merge = yes # Merge all armies in this province
			}
			spawn_fleet = {
				province = 97 # Rouen
				owner = ROOT
				earmark = williams_invasion_fleet
				disband_on_peace = yes
				troops =
				{
					galleys = { 180 180 }
				}
			}
		}
	}
	1066.10.14 = {
		raise_levies = {
			dismiss=yes
			location=97 # Rouen
			force_mult=1.0
		}
		effect = {
			clr_global_flag = williams_invasion_of_england
			disband_event_forces = yes
		}
	}
	1066.12.25  = {
		remove_claim=k_england
		give_nickname=nick_the_conqueror
		create_bloodline = {
			type = william_the_conqueror
			has_dlc = "Holy Fury"
		}
	}
	1087.9.9 = {
		death=yes
	}
}
```
