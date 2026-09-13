# Enrico — character 213601

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/italian.txt` (line 2047), block `213601 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `213601` |
| Name | `"Enrico"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `13027` |
| Religion | `"catholic"` |
| Culture | `"italian"` |
| Father | `170044` — Vitale (`characters/italian.txt`) |
| Mother | — (no `mother=` line) |
| DNA | `fhxirzswvcj` |
| Properties | `le0e0k0000a0000000` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `6` | `6` | `8` | `7` | — |

## Traits (base entries, as in file)

- `"cynical"`
- `"wroth"`
- `"grey_eminence"`

## Bloodline(s) (as in file)

### `dandolo` — granted 1202.10.1

```text
		create_bloodline = {
			type = dandolo
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `170044` — Vitale (`characters/italian.txt`)
- Mother: — (no `mother=` line)
- Spouses:
  - added 1150.1.2: `170047` — Contessa (`characters/italian.txt`)
- Recorded children (2 other block(s) with `father=213601` or `mother=213601`):
  - `father=213601`: `32121` — Raniero (`characters/italian.txt`), born 1152.1.2
  - `father=213601`: `32123` — Fantino (`characters/italian.txt`), born 1151.1.2

## Chronology (date order as in file; statements verbatim)

- **1107.1.2** — `birth="1107.1.2"`
- **1150.1.2** — `add_spouse=170047`
- **1176.10.1** — `trait="blinded"`
- **1202.10.1** — `trait="crusader"; create_bloodline={ type = dandolo has_dlc = "Holy Fury" }`
- **1205.6.21** — `death="1205.6.21"`

## History entries (verbatim)

### 1107.1.2

```text
	1107.1.2 = {
		birth="1107.1.2"
	}
```

### 1150.1.2

```text
	1150.1.2 = {
		add_spouse=170047 #Contessa Minotto
	}
```

### 1176.10.1

```text
	1176.10.1 = {
		trait="blinded"
	}
```

### 1202.10.1

```text
	1202.10.1 = {
		trait="crusader"
		create_bloodline = {
			type = dandolo
			has_dlc = "Holy Fury"
		}
	}
```

### 1205.6.21

```text
	1205.6.21 = {
		death="1205.6.21"
	}
```

## Full character block (verbatim)

```text
213601 = {
	name="Enrico"
	dna = fhxirzswvcj
	properties = le0e0k0000a0000000
	dynasty=13027
	martial=6
	diplomacy=6
	intrigue=8
	stewardship=7
	religion="catholic"
	culture="italian"
	trait="cynical"
	trait="wroth"
	trait="grey_eminence"
	father=170044
	1107.1.2 = {
		birth="1107.1.2"
	}
	1150.1.2 = {
		add_spouse=170047 #Contessa Minotto
	}
	1176.10.1 = {
		trait="blinded"
	}
	1202.10.1 = {
		trait="crusader"
		create_bloodline = {
			type = dandolo
			has_dlc = "Holy Fury"
		}
	}
	1205.6.21 = {
		death="1205.6.21"
	}
}
```
