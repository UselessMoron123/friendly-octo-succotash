# Niall — character 7255

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/irish.txt` (line 3135), block `7255 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `7255` |
| Name | `"Niall"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `9217` |
| Religion | `"pagan"` |
| Culture | `"irish"` |
| Father | `83432` — Eochaid (`characters/irish.txt`) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `11` | `12` | `9` | `12` | — |

## Traits (base entries, as in file)

- `"proud"`
- `"tough_soldier"`

## Bloodline(s) (as in file)

### `niall` — granted 400.1.1

```text
		create_bloodline = {
			type = niall
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `83432` — Eochaid (`characters/irish.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (3 other block(s) with `father=7255` or `mother=7255`):
  - `father=7255`: `7252` — Conall Gulban (`characters/irish.txt`), born 428.1.1
  - `father=7255`: `7254` — Conall Cremthainne (`characters/irish.txt`), born 429.1.1
  - `father=7255`: `7257` — Eógán (`characters/irish.txt`), born 430.1.1

## Chronology (date order as in file; statements verbatim)

- **400.1.1** — `birth="400.1.1"; create_bloodline={ type = niall has_dlc = "Holy Fury" }; give_nickname=nick_of_the_nine_hostages`
- **418.1.1** — `dynasty=199`
- **450.1.1** — `death="450.1.1"`

## History entries (verbatim)

### 400.1.1

```text
	400.1.1={
		birth="400.1.1"
		create_bloodline = {
			type = niall
			has_dlc = "Holy Fury"
		}
		give_nickname = nick_of_the_nine_hostages
	}
```

### 418.1.1

```text
	418.1.1={
		dynasty=199 #Ua Niall Noigiallaigh
	}
```

### 450.1.1

```text
	450.1.1={
		death="450.1.1"
	}
```

## Full character block (verbatim)

```text
7255 = {
	name="Niall"
	dynasty=9217
	martial=11
	diplomacy=12
	intrigue=9
	stewardship=12
	trait="proud"
	trait="tough_soldier"
	religion="pagan"
	culture="irish"
	father=83432
	400.1.1={
		birth="400.1.1"
		create_bloodline = {
			type = niall
			has_dlc = "Holy Fury"
		}
		give_nickname = nick_of_the_nine_hostages
	}
	418.1.1={
		dynasty=199 #Ua Niall Noigiallaigh
	}
	450.1.1={
		death="450.1.1"
	}
}
```
