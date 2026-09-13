# Boleslav — character 508

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/bohemian.txt` (line 968), block `508 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `508` |
| Name | `"Boleslav"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `506` |
| Religion | `catholic` |
| Culture | `bohemian` |
| Father | `504` — Vratislav (`characters/bohemian.txt`) |
| Mother | `505` — Drahomira (`characters/pommeranian.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `6` | `7` | `6` | `4` | — |

## Traits (base entries, as in file)

- `"lisp"`
- `"kinslayer"`
- `"envious"`
- `"flamboyant_schemer"`

## Other top-level fields (as in file)

- `give_nickname = nick_the_cruel`

## Bloodline(s) (as in file)

### `premyslid` — granted 935.9.28

```text
		create_bloodline = {
			type = premyslid
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `504` — Vratislav (`characters/bohemian.txt`)
- Mother: `505` — Drahomira (`characters/pommeranian.txt`)
- Spouses:
  - added 931.1.1: `507` — Biagota (`characters/bohemian.txt`)
- Recorded children (2 other block(s) with `father=508` or `mother=508`):
  - `father=508`: `509` — Doubravka (`characters/bohemian.txt`), born 933.1.1
  - `father=508`: `510` — Boleslav (`characters/bohemian.txt`), born 932.1.1

## Chronology (date order as in file; statements verbatim)

- **915.1.1** — `birth="915.1.1"`
- **931.1.1** — `add_spouse=507`
- **935.9.28** — `create_bloodline={ type = premyslid has_dlc = "Holy Fury" }`
- **972.1.1** — `death="972.1.1"`

## History entries (verbatim)

### 915.1.1

```text
	915.1.1={
		birth="915.1.1"
	}
```

### 931.1.1

```text
	931.1.1={
		add_spouse = 507
	}
```

### 935.9.28

```text
	935.9.28={
		create_bloodline = {
			type = premyslid
			has_dlc = "Holy Fury"
		}
	}
```

### 972.1.1

```text
	972.1.1={
		death="972.1.1"
	}
```

## Full character block (verbatim)

```text
508 = {
	name="Boleslav"
	dynasty=506
	martial=6
	diplomacy=7
	intrigue=6
	stewardship=4
	religion = catholic
	culture = bohemian
	trait="lisp"
	trait="kinslayer"
	trait="envious"
	trait="flamboyant_schemer"
	give_nickname = nick_the_cruel
	father = 504
	mother = 505
	915.1.1={
		birth="915.1.1"
	}
	931.1.1={
		add_spouse = 507
	}
	935.9.28={
		create_bloodline = {
			type = premyslid
			has_dlc = "Holy Fury"
		}
	}
	972.1.1={
		death="972.1.1"
	}
}
```
