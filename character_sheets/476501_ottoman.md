# Osman — character 476501

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/turkish.txt` (line 3273), block `476501 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `476501` |
| Name | `"Osman"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `7` |
| Religion | `"sunni"` |
| Culture | `"turkish"` |
| Father | `71840` — Ertugrul (`characters/turkish.txt`) |
| Mother | `71843` — Khaima (`characters/turkish.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `8` | `6` | `5` | `6` | — |

## Traits (base entries, as in file)

- `"gluttonous"`
- `"skilled_tactician"`

## Bloodline(s) (as in file)

### `ottoman` — granted 1281.1.1

```text
		create_bloodline = {
			type = ottoman
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `71840` — Ertugrul (`characters/turkish.txt`)
- Mother: `71843` — Khaima (`characters/turkish.txt`)
- Spouses:
  - added 1277.1.1: `71844` — Malhun (`characters/turkish.txt`)
- Recorded children (2 other block(s) with `father=476501` or `mother=476501`):
  - `father=476501`: `71845` — Alaeddin (`characters/turkish.txt`), born 1278.1.1
  - `father=476501`: `476500` — Orhan (`characters/turkish.txt`), born 1281.1.1

## Chronology (date order as in file; statements verbatim)

- **1258.1.1** — `birth="1258.1.1"`
- **1277.1.1** — `add_spouse=71844`
- **1281.1.1** — `create_bloodline={ type = ottoman has_dlc = "Holy Fury" }`
- **1324.1.1** — `death="1324.1.1"`

## History entries (verbatim)

### 1258.1.1

```text
	1258.1.1={
		birth="1258.1.1"
	}
```

### 1277.1.1

```text
	1277.1.1={
	add_spouse=71844
	}
```

### 1281.1.1

```text
	1281.1.1={
	capital=c_ankyra
		create_bloodline = {
			type = ottoman
			has_dlc = "Holy Fury"
		}
	}
```

### 1324.1.1

```text
	1324.1.1={
		death="1324.1.1"
	}
```

## Full character block (verbatim)

```text
476501 = {
	name="Osman"
	dynasty=7
	martial=8
	diplomacy=6
	intrigue=5
	stewardship=6
	religion="sunni"
	culture="turkish"
	trait="gluttonous"
	trait="skilled_tactician"
	father=71840
	mother=71843
	1258.1.1={
		birth="1258.1.1"
	}
	1277.1.1={
	add_spouse=71844
	}
	1281.1.1={
	capital=c_ankyra
		create_bloodline = {
			type = ottoman
			has_dlc = "Holy Fury"
		}
	}
	1324.1.1={
		death="1324.1.1"
	}
}
```
