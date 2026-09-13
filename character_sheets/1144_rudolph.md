# Rudolf — character 1144

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/german.txt` (line 1659), block `1144 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `1144` |
| Name | `"Rudolf"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `650` |
| Religion | `"catholic"` |
| Culture | `"german"` |
| Father | `7984` — Rudolf (`characters/german.txt`) |
| Mother | `7983` — Willa (`characters/frankish.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `6` | `6` | `8` | `6` | — |

## Traits (base entries, as in file)

- `"slothful"`
- `"honest"`
- `"patient"`
- `"flamboyant_schemer"`

## Bloodline(s) (as in file)

### `rudolph` — granted 933.1.1

```text
		create_bloodline = {
			type = rudolph
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `7984` — Rudolf (`characters/german.txt`)
- Mother: `7983` — Willa (`characters/frankish.txt`)
- Spouses:
  - added 922.1.1: `7958` — Bertha (`characters/german.txt`)
- Recorded children (2 other block(s) with `father=1144` or `mother=1144`):
  - `father=1144`: `1146` — Konrad (`characters/german.txt`), born 925.1.1
  - `father=1144`: `1159` — Adelheid (`characters/german.txt`), born 930.1.1

## Chronology (date order as in file; statements verbatim)

- **890.1.1** — `birth="890.1.1"`
- **922.1.1** — `add_spouse=7958`
- **933.1.1** — `create_bloodline={ type = rudolph has_dlc = "Holy Fury" }`
- **937.12.1** — `death="937.12.1"`

## History entries (verbatim)

### 890.1.1

```text
	890.1.1={
		birth="890.1.1"
	}
```

### 922.1.1

```text
	922.1.1={
		add_spouse = 7958
	}
```

### 933.1.1

```text
	933.1.1 = {
		create_bloodline = {
			type = rudolph
			has_dlc = "Holy Fury"
		}
	}
```

### 937.12.1

```text
	937.12.1={
		death="937.12.1"
	}
```

## Full character block (verbatim)

```text
1144 = {
	name="Rudolf"
	dynasty=650
	martial=6
	diplomacy=6
	intrigue=8
	stewardship=6
	religion="catholic"
	culture="german"
	trait="slothful"
	trait="honest"
	trait="patient"
	trait="flamboyant_schemer"
	father = 7984
	mother = 7983 
	890.1.1={
		birth="890.1.1"
	}
	922.1.1={
		add_spouse = 7958
	}
	933.1.1 = {
		create_bloodline = {
			type = rudolph
			has_dlc = "Holy Fury"
		}
	}
	937.12.1={
		death="937.12.1"
	}
}
```
