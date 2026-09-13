# Musa — character 161035

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/manden.txt` (line 354), block `161035 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `161035` |
| Name | `"Musa"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `1030002` |
| Religion | `"sunni"` |
| Culture | `"manden"` |
| Father | `161033` — Faga-Laye (`characters/manden.txt`) |
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

### `mansa_musa` — granted 1312.1.1

```text
		create_bloodline = {
			type = mansa_musa
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `161033` — Faga-Laye (`characters/manden.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=161035` or `mother=161035`):
  - `father=161035`: `161036` — Maghan (`characters/manden.txt`), born 1300.1.1

## Chronology (date order as in file; statements verbatim)

- **1280.1.1** — `birth="1280.1.1"`
- **1312.1.1** — `give_nickname=nick_the_lion; create_bloodline={ type = mansa_musa has_dlc = "Holy Fury" }`
- **1337.1.1** — `death="1337.1.1"`

## History entries (verbatim)

### 1280.1.1

```text
	1280.1.1={
		birth="1280.1.1"
	}
```

### 1312.1.1

```text
	1312.1.1 = {
		give_nickname = nick_the_lion
		create_bloodline = {
			type = mansa_musa
			has_dlc = "Holy Fury"
		}
	}
```

### 1337.1.1

```text
	1337.1.1={
		death="1337.1.1"
	}
```

## Full character block (verbatim)

```text
161035 = {
	name="Musa"
	dynasty=1030002
	religion="sunni"
	culture="manden"
	father=161033
	1280.1.1={
		birth="1280.1.1"
	}
	
	1312.1.1 = {
		give_nickname = nick_the_lion
		create_bloodline = {
			type = mansa_musa
			has_dlc = "Holy Fury"
		}
	}
	
	1337.1.1={
		death="1337.1.1"
	}
}
```
