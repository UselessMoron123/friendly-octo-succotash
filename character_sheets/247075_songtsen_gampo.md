# Songtsen Gampo — character 247075

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/bodpa.txt` (line 2712), block `247075 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `247075` |
| Name | `"Songtsen Gampo"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `105800` |
| Religion | `"bon"` |
| Culture | `"bodpa"` |
| Father | `247073` — Namri Songtsen (`characters/bodpa.txt`) |
| Mother | `247074` — Driza Tökarma (`characters/zhangzhung.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

_None at top level._

## Bloodline(s) (as in file)

### `songtsen_gampo` — granted 622.1.1

```text
		create_bloodline = {
			type = songtsen_gampo
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `247073` — Namri Songtsen (`characters/bodpa.txt`)
- Mother: `247074` — Driza Tökarma (`characters/zhangzhung.txt`)
- Spouses:
  - added 622.1.1: `247080` — Bhrikuti Devi (`characters/nepali.txt`)
  - added 641.1.1: `247081` — Wencheng (`characters/han.txt`)
- Recorded children (1 other block(s) with `father=247075` or `mother=247075`):
  - `father=247075`: `247088` — Gungsrong Gungtsen (`characters/bodpa.txt`), born 631.1.1

## Chronology (date order as in file; statements verbatim)

- **605.1.1** — `birth=yes`
- **622.1.1** — `add_spouse=247080; create_bloodline={ type = songtsen_gampo has_dlc = "Holy Fury" }`
- **625.1.1** — `(see verbatim block below)`
- **629.1.1** — `(see verbatim block below)`
- **634.1.1** — `(see verbatim block below)`
- **636.1.1** — `(see verbatim block below)`
- **641.1.1** — `add_spouse=247081; religion="buddhist"; trait=vajrayana_buddhist`
- **650.1.1** — `death=yes`

## History entries (verbatim)

### 605.1.1

```text
	605.1.1={
		birth=yes
	}
```

### 622.1.1

```text
	622.1.1={
		add_spouse=247080
		create_bloodline = {
			type = songtsen_gampo
			has_dlc = "Holy Fury"
		}
	}
```

### 625.1.1

```text
	625.1.1={
		effect={ROOT={add_consort=c_247078}}
	}
```

### 629.1.1

```text
	629.1.1={
		effect={ROOT={add_consort=c_247079}}
	}
```

### 634.1.1

```text
	634.1.1={
		effect={ROOT={add_consort=c_247003}}
	}
```

### 636.1.1

```text
	636.1.1={
		effect={ROOT={add_consort=c_247343}}
	}
```

### 641.1.1

```text
	641.1.1={
		add_spouse=247081
		religion="buddhist"
		trait = vajrayana_buddhist
	}
```

### 650.1.1

```text
	650.1.1={
		death=yes
	}
```

## Full character block (verbatim)

```text
247075 = {
	name="Songtsen Gampo"
	dynasty=105800 #Purgyal
	religion="bon"
	culture="bodpa"
	father=247073
	mother=247074
	605.1.1={
		birth=yes
	}
	622.1.1={
		add_spouse=247080
		create_bloodline = {
			type = songtsen_gampo
			has_dlc = "Holy Fury"
		}
	}
	625.1.1={
		effect={ROOT={add_consort=c_247078}}
	}
	629.1.1={
		effect={ROOT={add_consort=c_247079}}
	}
	634.1.1={
		effect={ROOT={add_consort=c_247003}}
	}
	636.1.1={
		effect={ROOT={add_consort=c_247343}}
	}
	641.1.1={
		add_spouse=247081
		religion="buddhist"
		trait = vajrayana_buddhist
	}
	650.1.1={
		death=yes
	}
}
```
