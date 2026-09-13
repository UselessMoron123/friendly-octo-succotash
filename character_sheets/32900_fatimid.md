# Abdullah — character 32900

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/bedouin_arabic.txt` (line 15540), block `32900 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `32900` |
| Name | `"Abdullah"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `589` |
| Religion | `"shiite"` |
| Culture | `"bedouin_arabic"` |
| Father | `33920` — Hussayn (`characters/bedouin_arabic.txt`) |
| Mother | — (no `mother=` line) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

- `"sayyid"`

## Bloodline(s) (as in file)

### `fatimid` — granted 909.1.1

```text
		create_bloodline = {
			type = fatimid
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `33920` — Hussayn (`characters/bedouin_arabic.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children (1 other block(s) with `father=32900` or `mother=32900`):
  - `father=32900`: `32901` — al-Qaim (`characters/bedouin_arabic.txt`), born 893.1.1

## Chronology (date order as in file; statements verbatim)

- **870.1.1** — `birth="870.1.1"`
- **909.1.1** — `create_bloodline={ type = fatimid has_dlc = "Holy Fury" }`
- **934.1.1** — `death="934.1.1"`

## History entries (verbatim)

### 870.1.1

```text
	870.1.1={
		birth="870.1.1"
	}
```

### 909.1.1

```text
	909.1.1 = {
		create_bloodline = {
			type = fatimid
			has_dlc = "Holy Fury"
		}
	}
```

### 934.1.1

```text
	934.1.1={
		death="934.1.1"
	}
```

## Full character block (verbatim)

```text
32900 = {
	name="Abdullah" # Rabi Abdullah - the Eleventh Ismaili Imam and first Fatimid Caliph
	dynasty=589
	religion="shiite"
	culture="bedouin_arabic"
	father=33920
	trait="sayyid"
	870.1.1={
		birth="870.1.1"
	}
	909.1.1 = {
		create_bloodline = {
			type = fatimid
			has_dlc = "Holy Fury"
		}
	}
	934.1.1={
		death="934.1.1"
	}
}
```
