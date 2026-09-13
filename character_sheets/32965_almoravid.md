# Yusuf — character 32965

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/maghreb_arabic.txt` (line 2429), block `32965 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `32965` |
| Name | `"Yusuf"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `7274` |
| Religion | `"sunni"` |
| Culture | `"maghreb_arabic"` |
| Father | `32962` — Tashfin (`characters/maghreb_arabic.txt`) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `9` | `8` | `5` | `7` | — |

## Traits (base entries, as in file)

- `"zealous"`
- `"diligent"`
- `"brave"`
- `"deceitful"`
- `"proud"`
- `"skilled_tactician"`

## Bloodline(s) (as in file)

### `almoravid` — granted 1071.1.1

```text
		create_bloodline = {
			type = almoravid
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `32962` — Tashfin (`characters/maghreb_arabic.txt`)
- Mother: — (no `mother=` line)
- Spouses:
  - added 1071.1.1: `3856` — Zainab (`characters/maghreb_arabic.txt`)
- Recorded children (5 other block(s) with `father=32965` or `mother=32965`):
  - `father=32965`: `32966` — al-Mu'izz (`characters/maghreb_arabic.txt`), born 1072.1.1
  - `father=32965`: `32967` — Fadl (`characters/maghreb_arabic.txt`), born 1075.1.1
  - `father=32965`: `32968` — Abu-Bakr (`characters/maghreb_arabic.txt`), born 1060.1.1
  - `father=32965`: `32969` — Ali (`characters/maghreb_arabic.txt`), born 1080.1.1
  - `father=32965`: `224013` — Yahya (`characters/maghreb_arabic.txt`), born 1080.1.1

## Chronology (date order as in file; statements verbatim)

- **1040.1.1** — `birth="1040.1.1"`
- **1060.1.1** — `add_claim=k_mauretania; add_claim=d_tangiers; add_claim=d_fes; add_claim=d_tlemcen`
- **1071.1.1** — `add_spouse=3856; add_claim=d_sevilla; add_claim=d_granada; add_claim=d_murcia; create_bloodline={ type = almoravid has_dlc = "Holy Fury" }`
- **1078.10.8** — `add_claim=d_zaragoza; add_claim=d_valencia; add_claim=d_mallorca; add_claim=d_murcia; add_claim=d_toledo; add_claim=d_cordoba; add_claim=d_badajoz; add_claim=d_sevilla; add_claim=d_granada`
- **1106.1.1** — `death="1106.1.1"`

## History entries (verbatim)

### 1040.1.1

```text
	1040.1.1 = {
		birth="1040.1.1"
	}
```

### 1060.1.1

```text
	1060.1.1 = {
		add_claim = k_mauretania
		add_claim = d_tangiers
		add_claim = d_fes
		add_claim = d_tlemcen
	}
```

### 1071.1.1

```text
	1071.1.1 = {
		add_spouse=3856
		add_claim = d_sevilla
		add_claim = d_granada
		add_claim = d_murcia
		remove_claim = k_mauretania
		create_bloodline = {
			type = almoravid
			has_dlc = "Holy Fury"
		}
	}
```

### 1078.10.8

```text
	1078.10.8 = {
		add_claim = d_zaragoza
		add_claim = d_valencia
		add_claim = d_mallorca
		add_claim = d_murcia
		add_claim = d_toledo
		add_claim = d_cordoba
		add_claim = d_badajoz
		add_claim = d_sevilla
		add_claim = d_granada
	}
```

### 1106.1.1

```text
	1106.1.1 = {
		death="1106.1.1"
	}
```

## Full character block (verbatim)

```text
32965 = {
	name="Yusuf" #Mauretania 1071-1106
	dynasty=7274
	martial=9
	diplomacy=8
	intrigue=5
	stewardship=7
	religion="sunni"
	culture="maghreb_arabic"
	father=32962
	trait="zealous"
	trait="diligent"
	trait="brave"
	trait="deceitful"
	trait="proud"
	trait="skilled_tactician"
	1040.1.1 = {
		birth="1040.1.1"
	}
	1060.1.1 = {
		add_claim = k_mauretania
		add_claim = d_tangiers
		add_claim = d_fes
		add_claim = d_tlemcen
	}
	1071.1.1 = {
		add_spouse=3856
		add_claim = d_sevilla
		add_claim = d_granada
		add_claim = d_murcia
		remove_claim = k_mauretania
		create_bloodline = {
			type = almoravid
			has_dlc = "Holy Fury"
		}
	}
	1078.10.8 = {
		add_claim = d_zaragoza
		add_claim = d_valencia
		add_claim = d_mallorca
		add_claim = d_murcia
		add_claim = d_toledo
		add_claim = d_cordoba
		add_claim = d_badajoz
		add_claim = d_sevilla
		add_claim = d_granada
	}
	1106.1.1 = {
		death="1106.1.1"
	}
}
```
