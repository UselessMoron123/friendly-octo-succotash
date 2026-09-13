# Æthelstan — character 33350

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/saxon.txt` (line 1609), block `33350 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `33350` |
| Name | `"Æthelstan"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `100072` |
| Religion | `"catholic"` |
| Culture | `"saxon"` |
| Father | `100` — Eadward (`characters/saxon.txt`) |
| Mother | — (no `mother=` line) |
| DNA | `dwuqrcylhrw` |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `8` | `9` | `5` | `6` | `5` |

## Traits (base entries, as in file)

- `scholarly_theologian`
- `erudite`
- `ambitious`
- `chaste`
- `diligent`
- `proud`

## Other top-level fields (as in file)

- `disallow_random_traits = yes`
- `prp = amq00b00000000000000000000000000000000`

## Bloodline(s) (as in file)

### `athelstan` — granted 927.1.1

```text
		create_bloodline = {
			type = athelstan
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `100` — Eadward (`characters/saxon.txt`)
- Mother: — (no `mother=` line)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children: — (no block has `father=33350` or `mother=33350`)

## Chronology (date order as in file; statements verbatim)

- **893.1.1** — `birth="893.1.1"`
- **927.1.1** — `create_bloodline={ type = athelstan has_dlc = "Holy Fury" }`
- **936.1.1** — `(see verbatim block below)`
- **937.1.1** — `(see verbatim block below)`
- **939.10.27** — `death="939.10.27"`

## History entries (verbatim)

### 893.1.1

```text
	893.1.1={
		birth="893.1.1"
	}
```

### 927.1.1

```text
	927.1.1 = {
		create_bloodline = {
			type = athelstan
			has_dlc = "Holy Fury"
		}
	}
```

### 936.1.1

```text
	936.1.1 = {
		capital = c_winchester
	}
```

### 937.1.1

```text
	937.1.1 = {
		capital = c_winchester
	}
```

### 939.10.27

```text
	939.10.27={
		death="939.10.27"
	}
```

## Full character block (verbatim)

```text
33350 = {
	name="Æthelstan"
	dna = dwuqrcylhrw
	prp = amq00b00000000000000000000000000000000

	disallow_random_traits = yes
	diplomacy = 9
	martial = 8
	intrigue = 5
	stewardship = 6
	learning = 5
	trait = scholarly_theologian
	trait = erudite
	trait = ambitious
	trait = chaste
	trait = diligent
	trait = proud

	dynasty=100072
	religion="catholic"
	culture="saxon"
	father = 100
	893.1.1={
		birth="893.1.1"
	}
	927.1.1 = {
		create_bloodline = {
			type = athelstan
			has_dlc = "Holy Fury"
		}
	}
	936.1.1 = {
		capital = c_winchester
	}
	937.1.1 = {
		capital = c_winchester
	}
	939.10.27={
		death="939.10.27"
	}
}
```
