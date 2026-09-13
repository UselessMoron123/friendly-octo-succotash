# Sabuktigin — character 144123

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/turkish.txt` (line 989), block `144123 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `144123` |
| Name | `"Sabuktigin"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `790` |
| Religion | `"sunni"` |
| Culture | `"turkish"` |
| Father | — (no `father=` line) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `12` | `8` | `9` | `9` | `6` |

## Traits (base entries, as in file)

- `brilliant_strategist`
- `diligent`
- `ambitious`
- `proud`
- `quick`
- `adventurer`

## Other top-level fields (as in file)

- `fertility = 0.8`
- `health = 6`

## Bloodline(s) (as in file)

### `ghaznavid` — granted 942.1.1

```text
		create_bloodline = {
			type = ghaznavid
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: — (no `father=` line)
- Mother: — (no `mother=` line)
- Spouses:
  - added 968.1.1: `170305` — Sibel (`characters/turkish.txt`)
- Recorded children (2 other block(s) with `father=144123` or `mother=144123`):
  - `father=144123`: `144124` — Ismail (`characters/turkish.txt`), born 970.1.1
  - `father=144123`: `144125` — Mahmud (`characters/turkish.txt`), born 971.1.1

## Chronology (date order as in file; statements verbatim)

- **942.1.1** — `birth=yes; create_bloodline={ type = ghaznavid has_dlc = "Holy Fury" }`
- **968.1.1** — `add_spouse=170305`
- **997.1.1** — `death=yes`

## History entries (verbatim)

### 942.1.1

```text
	942.1.1={
		birth=yes
		create_bloodline = {
			type = ghaznavid
			has_dlc = "Holy Fury"
		}
	}
```

### 968.1.1

```text
	968.1.1={
		add_spouse=170305
	}
```

### 997.1.1

```text
	997.1.1={
		death=yes
	}
```

## Full character block (verbatim)

```text
144123 = {
	name="Sabuktigin" # Founder of the Ghaznavids
	dynasty=790
	religion="sunni"
	culture="turkish"
	
	martial = 12
	diplomacy = 8
	stewardship = 9
	intrigue = 9
	learning = 6
	
	health = 6
	fertility = 0.8
	
	trait = brilliant_strategist
	trait = diligent
	trait = ambitious
	trait = proud
	trait = quick
	trait = adventurer
	
	942.1.1={
		birth=yes
		create_bloodline = {
			type = ghaznavid
			has_dlc = "Holy Fury"
		}
	}
	968.1.1={
		add_spouse=170305
	}
	997.1.1={
		death=yes
	}
}
```
