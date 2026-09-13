# Alexios — character 1742

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/greek.txt` (line 1534), block `1742 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `1742` |
| Name | `"Alexios"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `634` |
| Religion | `"orthodox"` |
| Culture | `"greek"` |
| Father | `1752` — Ioannes (`characters/greek.txt`) |
| Mother | `4511` — Anna (`characters/greek.txt`) |
| DNA | `rpxfoxiongk` |
| Properties | `ai0a00000000000000` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `9` | `9` | `8` | `9` | — |

## Traits (base entries, as in file)

- `"brave"`
- `"diligent"`
- `"proud"`
- `"patient"`
- `"greedy"`
- `"zealous"`
- `"kind"`

## Bloodline(s) (as in file)

### `alexios_komnenos` — granted 1081.4.1

```text
		create_bloodline = {
			type = alexios_komnenos
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `1752` — Ioannes (`characters/greek.txt`)
- Mother: `4511` — Anna (`characters/greek.txt`)
- Spouses:
  - added 1078.1.1: `1743` — Eirene (`characters/greek.txt`)
- Recorded children (8 other block(s) with `father=1742` or `mother=1742`):
  - `father=1742`: `125704` — Maria (`characters/greek.txt`), born 1085.1.2
  - `father=1742`: `125705` — Eudokia (`characters/greek.txt`), born 1094.1.2
  - `father=1742`: `125706` — Zoe (`characters/greek.txt`), born 1098.1.2
  - `father=1742`: `125707` — Andronikos (`characters/greek.txt`), born 1090.1.2
  - `father=1742`: `215528` — Isaakios (`characters/greek.txt`), born 1093.1.16
  - `father=1742`: `215532` — Anna (`characters/greek.txt`), born 1083.12.1
  - `father=1742`: `215555` — Theodora (`characters/greek.txt`), born 1096.1.2
  - `father=1742`: `223023` — Ioannes (`characters/greek.txt`), born 1087.9.13

## Chronology (date order as in file; statements verbatim)

- **1056.1.1** — `birth=yes`
- **1071.1.1** — `trait="midas_touched"`
- **1072.8.1** — `add_claim=e_byzantium`
- **1078.1.1** — `add_spouse=1743`
- **1081.4.1** — `create_bloodline={ type = alexios_komnenos has_dlc = "Holy Fury" }`
- **1081.12.10** — `(see verbatim block below)`
- **1107.1.1** — `trait=gout`
- **1118.8.15** — `death=yes`

## History entries (verbatim)

### 1056.1.1

```text
	1056.1.1={
		birth=yes
	}
```

### 1071.1.1

```text
	1071.1.1={
		trait="midas_touched"
	}
```

### 1072.8.1

```text
	1072.8.1={
		add_claim = e_byzantium
	}
```

### 1078.1.1

```text
	1078.1.1={
		add_spouse=1743
	}
```

### 1081.4.1

```text
	1081.4.1={
		create_bloodline = {
			type = alexios_komnenos
			has_dlc = "Holy Fury"
		}
	}
```

### 1081.12.10

```text
	1081.12.10={
		remove_claim = e_byzantium
	}
```

### 1107.1.1

```text
	1107.1.1={
		trait = gout
	}
```

### 1118.8.15

```text
	1118.8.15={
		death=yes
	}
```

## Full character block (verbatim)

```text
1742 = {
	name="Alexios"
	dna = rpxfoxiongk
	properties = ai0a00000000000000
	dynasty=634
	martial=9
	diplomacy=9
	intrigue=8
	stewardship=9
	religion="orthodox"
	culture="greek"
	trait="brave"
	trait="diligent"
	trait="proud"
	trait="patient"
	trait="greedy"
	trait="zealous"
	trait="kind"
	father=1752
	mother=4511
	1056.1.1={
		birth=yes
	}
	1071.1.1={
		trait="midas_touched"
	}
	1072.8.1={
		add_claim = e_byzantium
	}
	1078.1.1={
		add_spouse=1743
	}
	1081.4.1={
		create_bloodline = {
			type = alexios_komnenos
			has_dlc = "Holy Fury"
		}
	}
	1081.12.10={
		remove_claim = e_byzantium
	}
	1107.1.1={
		trait = gout
	}
	1118.8.15={
		death=yes
	}
}
```
