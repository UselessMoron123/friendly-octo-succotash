# Baibars — character 32933

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/egyptian_arabic.txt` (line 888), block `32933 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `32933` |
| Name | `"Baibars"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `7267` |
| Religion | `"sunni"` |
| Culture | `"egyptian_arabic"` |
| Father | — (no `father=` line) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

- `"brilliant_strategist"`
- `"strong"`
- `"ambitious"`
- `"deceitful"`

## Bloodline(s) (as in file)

### `baibars` — granted 1260.10.24

```text
		create_bloodline = {
			type = baibars
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: — (no `father=` line)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (3 other block(s) with `father=32933` or `mother=32933`):
  - `father=32933`: `32934` — al-Said Barakah (`characters/egyptian_arabic.txt`), born 1260.1.1
  - `father=32933`: `32949` — Solamish (`characters/egyptian_arabic.txt`), born 1272.1.1
  - `father=32933`: `32950` — Khadir (`characters/egyptian_arabic.txt`), born 1273.1.1

## Chronology (date order as in file; statements verbatim)

- **1223.7.19** — `birth="1223.7.19"`
- **1260.10.24** — `create_bloodline={ type = baibars has_dlc = "Holy Fury" }`
- **1277.7.1** — `death="1277.7.1"`

## History entries (verbatim)

### 1223.7.19

```text
	1223.7.19={
		birth="1223.7.19"
	}
```

### 1260.10.24

```text
	1260.10.24={
		create_bloodline = {
			type = baibars
			has_dlc = "Holy Fury"
		}
	}
```

### 1277.7.1

```text
	1277.7.1={
		death="1277.7.1"
	}
```

## Full character block (verbatim)

```text
32933 = {
	name="Baibars" 
	dynasty=7267
	religion="sunni"
	culture="egyptian_arabic"
	trait="brilliant_strategist"
	trait="strong" 
	trait="ambitious" 
	trait="deceitful" 
	1223.7.19={
		birth="1223.7.19"
	}
	1260.10.24={
		create_bloodline = {
			type = baibars
			has_dlc = "Holy Fury"
		}
	}
	1277.7.1={
		death="1277.7.1"
	}
}
```
