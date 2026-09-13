# Alexandr — character 472844

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/russian.txt` (line 8961), block `472844 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `472844` |
| Name | `"Alexandr"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `705` |
| Religion | `"orthodox"` |
| Culture | `"russian"` |
| Father | `472885` — Yaroslav (`characters/russian.txt`) |
| Mother | `125149` — Rostislava (`characters/russian.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `9` | `6` | `7` | `7` | — |

## Traits (base entries, as in file)

- `"brave"`
- `"proud"`
- `"cynical"`
- `"diligent"`
- `"brilliant_strategist"`

## Bloodline(s) (as in file)

### `alexander_nevsky` — granted 1220.5.30

```text
		create_bloodline = {
			type = alexander_nevsky
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `472885` — Yaroslav (`characters/russian.txt`)
- Mother: `125149` — Rostislava (`characters/russian.txt`)
- Spouses:
  - added 1239.1.2: `472845` — Alexandra (`characters/russian.txt`)
- Recorded children (4 other block(s) with `father=472844` or `mother=472844`):
  - `father=472844`: `125210` — Vasiliy (`characters/russian.txt`), born 1240.1.2
  - `father=472844`: `125211` — Dmitriy (`characters/russian.txt`), born 1250.1.2
  - `father=472844`: `472843` — Daniil (`characters/russian.txt`), born 1261.1.2
  - `father=472844`: `472846` — Andrei (`characters/russian.txt`), born 1255.1.2

## Chronology (date order as in file; statements verbatim)

- **1220.5.30** — `birth="1220.5.30"; create_bloodline={ type = alexander_nevsky has_dlc = "Holy Fury" }`
- **1239.1.2** — `add_spouse=472845`
- **1263.11.14** — `death="1263.11.14"`

## History entries (verbatim)

### 1220.5.30

```text
	1220.5.30={
		birth="1220.5.30"
		create_bloodline = {
			type = alexander_nevsky
			has_dlc = "Holy Fury"
		}
	}
```

### 1239.1.2

```text
	1239.1.2={
		add_spouse=472845
	}
```

### 1263.11.14

```text
	1263.11.14={
		death="1263.11.14"
	}
```

## Full character block (verbatim)

```text
472844 = {
	name="Alexandr"
	# AKA: Alexander Nevsky
	dynasty=705
	martial=9
	diplomacy=6
	intrigue=7
	stewardship=7
	religion="orthodox"
	culture="russian"
	father=472885
	mother=125149
	trait="brave"
	trait="proud"
	trait="cynical"
	trait="diligent"
	trait="brilliant_strategist"
	1220.5.30={
		birth="1220.5.30"
		create_bloodline = {
			type = alexander_nevsky
			has_dlc = "Holy Fury"
		}
	}
	1239.1.2={
		add_spouse=472845
	}
	1263.11.14={
		death="1263.11.14"
	}
}
```
