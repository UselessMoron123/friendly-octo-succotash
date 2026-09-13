# Caradog — character 252141

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/welsh.txt` (line 9365), block `252141 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `252141` |
| Name | `"Caradog"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `105920` |
| Religion | `"pagan"` |
| Culture | `"welsh"` |
| Father | `252137` — Cynfelyn (`characters/welsh.txt`) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

- `brave`
- `strong`
- `inspiring_leader`
- `aggressive_leader`

## Bloodline(s) (as in file)

### `caratacus` — granted 21.1.1

```text
		create_bloodline = {
			type = caratacus
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `252137` — Cynfelyn (`characters/welsh.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=252141` or `mother=252141`):
  - `father=252141`: `252149` — Madog (`characters/welsh.txt`), born 38.1.1

## Chronology (date order as in file; statements verbatim)

- **21.1.1** — `birth=yes; create_bloodline={ type = caratacus has_dlc = "Holy Fury" }`
- **50.1.1** — `death=yes`

## History entries (verbatim)

### 21.1.1

```text
	21.1.1={
		birth=yes
		create_bloodline = {
			type = caratacus
			has_dlc = "Holy Fury"
		}
	}
```

### 50.1.1

```text
	50.1.1={
		death=yes
	}
```

## Full character block (verbatim)

```text
252141 = {
	name="Caradog" #Caratacus
	dynasty=105920
	religion="pagan"
	culture="welsh"
	father=252137
	trait=brave
	trait=strong
	trait=inspiring_leader
	trait=aggressive_leader
	21.1.1={
		birth=yes
		create_bloodline = {
			type = caratacus
			has_dlc = "Holy Fury"
		}
	}
	50.1.1={
		death=yes
	}
}
```
