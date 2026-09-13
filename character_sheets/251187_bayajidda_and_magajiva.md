# Magajiva — character 251187

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/hausa.txt` (line 191), block `251187 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `251187` |
| Name | `"Magajiva"` |
| Sex | female (`female = yes`) |
| Dynasty | `1060028` |
| Religion | `"west_african_pagan"` |
| Culture | `"hausa"` |
| Father | — (no `father=` line) |
| Mother | `251203` — Shawata (`characters/hausa.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

_None at top level._

## Bloodline(s) (as in file)

### `bayajidda_and_magajiva` — granted 867.1.1

```text
		create_bloodline = {
			type = bayajidda_and_magajiva
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: — (no `father=` line)
- Mother: `251203` — Shawata (`characters/hausa.txt`)
- Spouses:
  - added 866.2.2: `251180` — Bayajidda (`characters/hausa.txt`)
- Recorded children (2 other block(s) with `father=251187` or `mother=251187`):
  - `mother=251187`: `251181` — Bawo (`characters/hausa.txt`), born 890.1.1
  - `mother=251187`: `251251` — Shawata (`characters/hausa.txt`), born 865.1.1

## Chronology (date order as in file; statements verbatim)

- **846.1.1** — `birth=yes`
- **866.2.2** — `add_spouse=251180`
- **867.1.1** — `create_bloodline={ type = bayajidda_and_magajiva has_dlc = "Holy Fury" }`
- **910.1.1** — `death=yes`

## History entries (verbatim)

### 846.1.1

```text
	846.1.1 = {
		birth=yes
	}
```

### 866.2.2

```text
	866.2.2={
		add_spouse=251180
	}
```

### 867.1.1

```text
	867.1.1 = {
		create_bloodline = {
			type = bayajidda_and_magajiva
			has_dlc = "Holy Fury"
		}
	}
```

### 910.1.1

```text
	910.1.1 = {
		death=yes
	}
```

## Full character block (verbatim)

```text
251187 = {
	name="Magajiva" #Queen of Daura and second wife of Bayajiddah
	female=yes
	dynasty=1060028 #Daura
	religion="west_african_pagan"
	culture="hausa"
	mother = 251203
	846.1.1 = {
		birth=yes
	}
	866.2.2={
		add_spouse=251180
	}
	867.1.1 = {
		create_bloodline = {
			type = bayajidda_and_magajiva
			has_dlc = "Holy Fury"
		}
	}
	910.1.1 = {
		death=yes
	}
}
```
