# Basileios — character 1700

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/greek.txt` (line 1), block `1700 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `1700` |
| Name | `"Basileios"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `644` |
| Religion | `"orthodox"` |
| Culture | `"greek"` |
| Father | `145129` — Bardas (`characters/greek.txt`) |
| Mother | — (no `mother=` line) |
| DNA | `dageigbabbe` |
| Properties | `am0aj0000000` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `6` | `8` | `8` | `6` | — |

## Traits (base entries, as in file)

- `"tough_soldier"`
- `"strong"`
- `"brave"`
- `"deceitful"`
- `"ambitious"`

## Bloodline(s) (as in file)

### `basil` — granted 836.5.25

```text
		create_bloodline = {
			type = basil
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `145129` — Bardas (`characters/greek.txt`)
- Mother: — (no `mother=` line)
- Spouses:
  - added 860.1.1: `145131` — Maria (`characters/greek.txt`)
  - removed 864.12.31: `145131` — Maria (`characters/greek.txt`)
  - added 865.1.1: `1761` — Eudokia (`characters/norse.txt`)
- Recorded children (5 other block(s) with `father=1700` or `mother=1700`):
  - `father=1700`: `1702` — Leon (`characters/greek.txt`), born 866.9.29
  - `father=1700`: `1704` — Alexandros (`characters/greek.txt`), born 872.11.1
  - `father=1700`: `70553` — Stephanos (`characters/greek.txt`), born 867.11.1
  - `father=1700`: `145132` — Anastasia (`characters/greek.txt`), born 862.1.1
  - `father=1700`: `145133` — Konstantinos (`characters/greek.txt`), born 864.1.1

## Chronology (date order as in file; statements verbatim)

- **836.5.25** — `birth="836.5.25"; create_bloodline={ type = basil has_dlc = "Holy Fury" }`
- **860.1.1** — `add_spouse=145131`
- **864.12.31** — `remove_spouse=145131`
- **865.1.1** — `add_spouse=1761`
- **886.8.29** — `death="886.8.29"`

## History entries (verbatim)

### 836.5.25

```text
	836.5.25={
		birth="836.5.25"
		create_bloodline = {
			type = basil
			has_dlc = "Holy Fury"
		}
	}
```

### 860.1.1

```text
	860.1.1={
		add_spouse=145131
	}
```

### 864.12.31

```text
	864.12.31={
		remove_spouse=145131
	}
```

### 865.1.1

```text
	865.1.1={
		add_spouse=1761
	}
```

### 886.8.29

```text
	886.8.29={
		death="886.8.29"
	}
```

## Full character block (verbatim)

```text
1700 = {
	name="Basileios"
	dynasty=644
	dna = dageigbabbe
	properties = am0aj0000000
	martial=6
	diplomacy=8
	intrigue=8
	stewardship=6
	religion="orthodox"
	culture="greek"
	trait="tough_soldier"
	trait="strong"
	trait="brave"
	trait="deceitful"
	trait="ambitious"
	father=145129
	836.5.25={
		birth="836.5.25"
		create_bloodline = {
			type = basil
			has_dlc = "Holy Fury"
		}
	}
	860.1.1={
		add_spouse=145131
	}
	864.12.31={
		remove_spouse=145131
	}
	865.1.1={
		add_spouse=1761
	}
	886.8.29={
		death="886.8.29"
	}
}
```
