# Mérovech — character 168671

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/old_frankish.txt` (line 2448), block `168671 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `168671` |
| Name | `"Mérovech"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `542` |
| Religion | `"norse_pagan"` |
| Culture | `"old_frankish"` |
| Father | `168670` — Clodion (`characters/old_frankish.txt`) |
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

### `merovingian` — granted 410.1.1

```text
		create_bloodline = {
			type = merovingian
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `168670` — Clodion (`characters/old_frankish.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=168671` or `mother=168671`):
  - `father=168671`: `168672` — Childéric (`characters/old_frankish.txt`), born 430.1.1

## Chronology (date order as in file; statements verbatim)

- **410.1.1** — `birth=yes; create_bloodline={ type = merovingian has_dlc = "Holy Fury" }`
- **457.1.1** — `death=yes`

## History entries (verbatim)

### 410.1.1

```text
	410.1.1 = {
		birth=yes
		create_bloodline = {
			type = merovingian
			has_dlc = "Holy Fury"
		}
	}
```

### 457.1.1

```text
	457.1.1 = {
		death=yes
	}
```

## Full character block (verbatim)

```text
168671 = {
	name="Mérovech"
	dynasty=542
	religion="norse_pagan"
	culture="old_frankish"
	father=168670
	410.1.1 = {
		birth=yes
		create_bloodline = {
			type = merovingian
			has_dlc = "Holy Fury"
		}
	}
	
	457.1.1 = {
		death=yes
	}
}
```
