# Saladin — character 226000

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/levantine_arabic.txt` (line 2638), block `226000 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `226000` |
| Name | `"Saladin"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `24000` |
| Religion | `"sunni"` |
| Culture | `"levantine_arabic"` |
| Father | `226053` — Eyyub Necmedîn (`characters/kurdish.txt`) |
| Mother | — (no `mother=` line) |
| DNA | `fcvmfemunim` |
| Properties | `am0bib000000000000` |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `7` | `5` | `7` | `10` | — |

## Traits (base entries, as in file)

- `"diligent"`
- `"patient"`
- `"charitable"`
- `"just"`
- `"grey_eminence"`

## Bloodline(s) (as in file)

### `saladin` — granted 1187.10.2

```text
		create_bloodline = {
			type = saladin
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `226053` — Eyyub Necmedîn (`characters/kurdish.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (8 other block(s) with `father=226000` or `mother=226000`):
  - `father=226000`: `32917` — Ghazi (`characters/egyptian_arabic.txt`), born 1172.1.1
  - `father=226000`: `32918` — Khider (`characters/egyptian_arabic.txt`), born 1177.1.1
  - `father=226000`: `32919` — Da'ud (`characters/egyptian_arabic.txt`), born 1180.1.1
  - `father=226000`: `32920` — Turanshah (`characters/egyptian_arabic.txt`), born 1181.1.1
  - `father=226000`: `32921` — Nosrat-es-Din (`characters/egyptian_arabic.txt`), born 1182.1.1
  - `father=226000`: `226050` — Al-Aziz Uthman (`characters/maghreb_arabic.txt`), born 1171.1.1
  - `father=226000`: `226051` — Al-Afdal (`characters/levantine_arabic.txt`), born 1170.1.1
  - `father=226000`: `226054` — Az-Zahir Ghazi (`characters/levantine_arabic.txt`), born 1172.1.1

## Chronology (date order as in file; statements verbatim)

- **1138.1.1** — `birth="1138.1.1"`
- **1187.10.2** — `create_bloodline={ type = saladin has_dlc = "Holy Fury" }`
- **1193.3.4** — `death="1193.3.4"`

## History entries (verbatim)

### 1138.1.1

```text
	1138.1.1={
		birth="1138.1.1"
	}
```

### 1187.10.2

```text
	1187.10.2= {
		create_bloodline = {
			type = saladin
			has_dlc = "Holy Fury"
		}
	}
```

### 1193.3.4

```text
	1193.3.4={
		death="1193.3.4"
	}
```

## Full character block (verbatim)

```text
226000 = {
	name="Saladin" #Egypt
	# AKA: Salah ad
	dna = fcvmfemunim
	properties = am0bib000000000000
	dynasty=24000
	martial=7
	diplomacy=5
	intrigue=7
	stewardship=10
	religion="sunni"
	culture="levantine_arabic"
	trait="diligent"
	trait="patient"
	trait="charitable"
	trait="just"
	trait="grey_eminence"
	father=226053
	1138.1.1={
		birth="1138.1.1"
	}
	1187.10.2= {
		create_bloodline = {
			type = saladin
			has_dlc = "Holy Fury"
		}
	}
	1193.3.4={
		death="1193.3.4"
	}
}
```
