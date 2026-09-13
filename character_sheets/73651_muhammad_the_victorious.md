# Muhammad — character 73651

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/andalusian_arabic.txt` (line 3043), block `73651 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `73651` |
| Name | `"Muhammad"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `101904` |
| Religion | `"sunni"` |
| Culture | `"andalusian_arabic"` |
| Father | `73653` — Nasr (`characters/andalusian_arabic.txt`) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

_None at top level._

## Bloodline(s) (as in file)

### `muhammad_the_victorious` — granted 1266.1.1

```text
		create_bloodline = {
			type = muhammad_the_victorious
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `73653` — Nasr (`characters/andalusian_arabic.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (2 other block(s) with `father=73651` or `mother=73651`):
  - `father=73651`: `73650` — Muhammad (`characters/andalusian_arabic.txt`), born 1235.1.1
  - `father=73651`: `73652` — Yusuf (`characters/andalusian_arabic.txt`), born 1238.1.1

## Chronology (date order as in file; statements verbatim)

- **1194.1.1** — `birth="1194.1.1"`
- **1232.1.1** — `add_claim=d_granada`
- **1237.1.1** — `add_claim=d_murcia; add_claim=d_sevilla`
- **1238.1.1** — `(see verbatim block below)`
- **1266.1.1** — `create_bloodline={ type = muhammad_the_victorious has_dlc = "Holy Fury" }`
- **1273.1.1** — `death="1273.1.1"`

## History entries (verbatim)

### 1194.1.1

```text
	1194.1.1={
		birth="1194.1.1"
	}
```

### 1232.1.1

```text
	1232.1.1 = {
		add_claim = d_granada
	}
```

### 1237.1.1

```text
	1237.1.1={
		remove_claim = d_granada
		add_claim = d_murcia
		add_claim = d_sevilla
	}
```

### 1238.1.1

```text
	1238.1.1={
		remove_claim = d_sevilla
	}
```

### 1266.1.1

```text
	1266.1.1={
		remove_claim = d_murcia
		create_bloodline = {
			type = muhammad_the_victorious
			has_dlc = "Holy Fury"
		}
	}
```

### 1273.1.1

```text
	1273.1.1={
		death="1273.1.1"
	}
```

## Full character block (verbatim)

```text
73651={
	name="Muhammad"
	dynasty = 101904
	religion="sunni"
	culture="andalusian_arabic"
	father=73653
	1194.1.1={
		birth="1194.1.1"
	}
	1232.1.1 = {
		add_claim = d_granada
	}
	1237.1.1={
		remove_claim = d_granada
		add_claim = d_murcia
		add_claim = d_sevilla
	}
	1238.1.1={
		remove_claim = d_sevilla
	}
	1266.1.1={
		remove_claim = d_murcia
		create_bloodline = {
			type = muhammad_the_victorious
			has_dlc = "Holy Fury"
		}
	}
	1273.1.1={
		death="1273.1.1"
	}
}
```
