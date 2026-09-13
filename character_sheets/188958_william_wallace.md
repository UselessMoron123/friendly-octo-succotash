# William — character 188958

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/scottish.txt` (line 9179), block `188958 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `188958` |
| Name | `"William"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `3133` |
| Religion | `"catholic"` |
| Culture | `"scottish"` |
| Father | `188957` — Alan (`characters/scottish.txt`) |
| Mother | `188956` — Margaret (`characters/scottish.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| — | — | — | — | — |

## Traits (base entries, as in file)

- `brilliant_strategist`
- `quick`
- `ambitious`
- `gregarious`
- `diligent`

## Bloodline(s) (as in file)

### `william_wallace` — granted 1271.1.1

```text
		create_bloodline = {
			type = william_wallace
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `188957` — Alan (`characters/scottish.txt`)
- Mother: `188956` — Margaret (`characters/scottish.txt`)
- Spouses: — (no `add_spouse=` / `remove_spouse=` lines)
- Recorded children: — (no block has `father=188958` or `mother=188958`)

## Chronology (date order as in file; statements verbatim)

- **1271.1.1** — `birth=yes; create_bloodline={ type = william_wallace has_dlc = "Holy Fury" }`
- **1305.8.23** — `death=yes`

## History entries (verbatim)

### 1271.1.1

```text
	1271.1.1={
		birth=yes
		create_bloodline = {
			type = william_wallace
			has_dlc = "Holy Fury"
		}
	}
```

### 1305.8.23

```text
	1305.8.23={
		death=yes
	}
```

## Full character block (verbatim)

```text
188958 = {  	
	name="William"
	dynasty=3133 # Wallace
	religion="catholic"
	culture="scottish"
	father=188957
	mother=188956
	trait=brilliant_strategist
	trait=quick
	trait=ambitious
	trait=gregarious
	trait=diligent
	1271.1.1={
		birth=yes
		create_bloodline = {
			type = william_wallace
			has_dlc = "Holy Fury"
		}
	}
	1305.8.23={
		death=yes
	}
}
```
