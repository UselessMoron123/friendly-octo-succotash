# Temüjin — character 125501

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/mongol.txt` (line 247), block `125501 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `125501` |
| Name | `"Temüjin"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `11100` |
| Religion | `"tengri_pagan"` |
| Culture | `"mongol"` |
| Father | `93055` — Yesügei (`characters/mongol.txt`) |
| Mother | `172003` — Hoelun (`characters/mongol.txt`) |
| DNA | `"bfimkolbecc"` |
| Properties | `"ge0af0000000"` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `10` | `8` | `8` | `9` | — |

## Traits (base entries, as in file)

- `"brave"`
- `"ambitious"`
- `"diligent"`
- `"cruel"`
- `"hunter"`
- `"cavalry_leader"`
- `"brilliant_strategist"`
- `"sympathy_christendom"`
- `"sympathy_islam"`
- `"sympathy_zoroastrianism"`
- `"sympathy_judaism"`
- `"sympathy_indian"`

## Bloodline(s) (as in file)

### `genghis_khan` — granted 1206.1.1

```text
	 create_bloodline = {
	 	type = genghis_khan
	 	has_dlc = "Holy Fury"
	 }
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `93055` — Yesügei (`characters/mongol.txt`)
- Mother: `172003` — Hoelun (`characters/mongol.txt`)
- Spouses:
  - added 1178.1.1: `172004` — Börte (`characters/mongol.txt`)
  - removed 1180.1.1: `172004` — Börte (`characters/mongol.txt`)
  - added 1181.1.1: `172004` — Börte (`characters/mongol.txt`)
- Recorded children (11 other block(s) with `father=125501` or `mother=125501`):
  - `father=125501`: `93062` — Chagatai (`characters/mongol.txt`), born 1183.1.1
  - `father=125501`: `125502` — Jochi (`characters/mongol.txt`), born 1181.1.1
  - `father=125501`: `125520` — Tolui (`characters/mongol.txt`), born 1192.1.1
  - `father=125501`: `166865` — Gelejian (`characters/mongol.txt`), born 1195.1.1
  - `father=125501`: `166871` — Khochen (`characters/mongol.txt`), born 1184.1.1
  - `father=125501`: `166872` — Alakhai (`characters/mongol.txt`), born 1193.1.1
  - `father=125501`: `166873` — Tümelün (`characters/mongol.txt`), born 1189.1.1
  - `father=125501`: `166874` — Checheikhen (`characters/mongol.txt`), born 1188.1.1
  - `father=125501`: `166875` — Altun Begi (`characters/mongol.txt`), born 1194.1.1
  - `father=125501`: `166876` — Altalün (`characters/mongol.txt`), born 1198.1.1
  - `father=125501`: `172005` — Ögedei (`characters/mongol.txt`), born 1186.11.7

## Chronology (date order as in file; statements verbatim)

- **1162.1.1** — `birth=yes`
- **1172.1.1** — `(see verbatim block below)`
- **1178.1.1** — `add_spouse=172004`
- **1180.1.1** — `remove_spouse=172004`
- **1181.1.1** — `add_spouse=172004`
- **1201.1.1** — `(see verbatim block below)`
- **1202.1.1** — `(see verbatim block below)`
- **1206.1.1** — `create_bloodline={ type = genghis_khan has_dlc = "Holy Fury" }`
- **1220.2.1** — `(see verbatim block below)`
- **1227.12.2** — `death=yes`

## History entries (verbatim)

### 1162.1.1

```text
   1162.1.1={
		birth=yes
		effect = {
		set_character_flag = is_temujin
		set_global_flag = temujin_born
		}
   }
```

### 1172.1.1

```text
   1172.1.1={
     effect = {add_friend = 166796 } #Becomes blood brothers with Jamukha
     effect = {add_friend = 166890} #Wang Khan gives patronage to Temüjin
     effect = {add_friend = 166894} #Jakha Khambu befriends Temüjin
   }
```

### 1178.1.1

```text
   1178.1.1={
     add_spouse=172004
   }
```

### 1180.1.1

```text
   1180.1.1={
     effect = {add_rival = 166906} #Chilger Bökh abducts Börte
     remove_spouse=172004
   }
```

### 1181.1.1

```text
   1181.1.1={
     add_spouse=172004
     effect={add_consort=166864}
     effect={add_lover=166864}
   }
```

### 1201.1.1

```text
   1201.1.1={
     effect = {remove_friend = 166796 }
     effect = {add_rival = 166796 } #Becomes rivals with Jamukha
     effect = {add_rival = 166890 } #Becomes rivals with Wang Khan
   }
```

### 1202.1.1

```text
   1202.1.1={
     effect={add_consort=166869}
     effect={add_consort=166870}
   }
```

### 1206.1.1

```text
   1206.1.1 = {
     effect_even_if_dead = {
       set_special_character_title = GENGHIS_KHAN
       set_global_flag = mongol_horde_united
       add_character_modifier = { modifier = greatest_of_khans duration = -1 }
     }
	 create_bloodline = {
	 	type = genghis_khan
	 	has_dlc = "Holy Fury"
	 }
   }
```

### 1220.2.1

```text
   1220.2.1 = {
     effect = {
       wealth = 200
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 34852
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 125502
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 93062
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 34850
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 172005
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 125520
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 125501
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 34851
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 172002
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 172000
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 93100
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 93103
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
     }
   }
```

### 1227.12.2

```text
   1227.12.2={
     death=yes
   }
```

## Full character block (verbatim)

```text
125501 = {
   name="Temüjin"
   # AKA: Genghis Khan
   dynasty=11100
   dna="bfimkolbecc"
   properties="ge0af0000000"
   martial=10
   diplomacy=8
   intrigue=8
   stewardship=9
   religion="tengri_pagan"
   culture="mongol"
   add_trait="brave"
   add_trait="ambitious"
   add_trait="diligent"
   add_trait="cruel"
   add_trait="hunter"
   add_trait="cavalry_leader"
   add_trait="brilliant_strategist"
   add_trait="sympathy_christendom"
   add_trait="sympathy_islam"
   add_trait="sympathy_zoroastrianism"
   add_trait="sympathy_judaism"
   add_trait="sympathy_indian"
   father=93055
   mother=172003
   1162.1.1={
		birth=yes
		effect = {
		set_character_flag = is_temujin
		set_global_flag = temujin_born
		}
   }
   1172.1.1={
     effect = {add_friend = 166796 } #Becomes blood brothers with Jamukha
     effect = {add_friend = 166890} #Wang Khan gives patronage to Temüjin
     effect = {add_friend = 166894} #Jakha Khambu befriends Temüjin
   }
   1178.1.1={
     add_spouse=172004
   }
   1180.1.1={
     effect = {add_rival = 166906} #Chilger Bökh abducts Börte
     remove_spouse=172004
   }
   1181.1.1={
     add_spouse=172004
     effect={add_consort=166864}
     effect={add_lover=166864}
   }#recaptures Börte and marries Khulan Khatun
   1201.1.1={
     effect = {remove_friend = 166796 }
     effect = {add_rival = 166796 } #Becomes rivals with Jamukha
     effect = {add_rival = 166890 } #Becomes rivals with Wang Khan
   }
   1202.1.1={
     effect={add_consort=166869}
     effect={add_consort=166870}
   }# Conquers the Tatars
   1206.1.1 = {
     effect_even_if_dead = {
       set_special_character_title = GENGHIS_KHAN
       set_global_flag = mongol_horde_united
       add_character_modifier = { modifier = greatest_of_khans duration = -1 }
     }
	 create_bloodline = {
	 	type = genghis_khan
	 	has_dlc = "Holy Fury"
	 }
   }
   1220.2.1 = {
     effect = {
       wealth = 200
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 34852
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 125502
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 93062
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 34850
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 172005
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 125520
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 125501
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 34851
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 172002
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 172000
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 93100
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
       spawn_unit = {
         province = 904 #Balkh
         owner = ROOT
         #leader = 93103
         troops =
         {
           horse_archers = { 2200 2300 }
           light_cavalry = { 1366 1366 }
           light_infantry = { 455 455 }
           heavy_infantry = { 177 177 }
           knights = { 40 40 }
         }
       }
     }
   }
   1227.12.2={
     death=yes
   }
}
```
