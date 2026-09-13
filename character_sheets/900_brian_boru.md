# Brian — character 900

> Transcribed as-is from the history files. Nothing invented; values below are the exact tokens from the source block.
> Source: `characters/irish.txt` (line 3876), block `900 = { ... }`.
> Display only: line endings normalized (CRLF → LF), encoding converted (Windows-1252 → UTF-8). Inline `#` comments are preserved in the verbatim sections.

## Identity (as in file)

| Field | Value in file |
|---|---|
| Character ID | `900` |
| Name | `"Brian"` |
| Sex | male (default — no `female=` line) |
| Dynasty | `100009` |
| Religion | `"catholic"` |
| Culture | `"irish"` |
| Father | `83330` — Cennétig (`characters/irish.txt`) |
| Mother | `166063` — Bébinn (`characters/irish.txt`) |
| DNA | — (absent) |
| Properties | — (absent) |

## Attributes (as in file)

| martial | diplomacy | intrigue | stewardship | learning |
|---|---|---|---|---|
| `9` | `5` | `7` | `7` | — |

## Traits (base entries, as in file)

- `"wroth"`
- `"brave"`
- `"martial_cleric"`

## Bloodline(s) (as in file)

### `brian_boru` — granted 941.1.1

```text
		create_bloodline = {
			type = brian_boru
			has_dlc = "Holy Fury"
		}
```

## Family & relations (IDs as in file; names looked up from the same history files)

- Father: `83330` — Cennétig (`characters/irish.txt`)
- Mother: `166063` — Bébinn (`characters/irish.txt`)
- Spouses:
  - added 962.1.1: `166116` — Mór (`characters/irish.txt`)
  - added 983.1.1: `166123` — Eachraidh (`characters/irish.txt`)
  - added 999.1.1: `166102` — Gormflaith (`characters/irish.txt`)
  - removed 1002.1.1: `166102` — Gormflaith (`characters/irish.txt`)
  - added 1002.2.1: `166124` — Dub Chobhlaigh (`characters/irish.txt`)
- Recorded children (11 other block(s) with `father=900` or `mother=900`):
  - `father=900`: `902` — Donnchad (`characters/irish.txt`), born 1000.1.1
  - `father=900`: `903` — Murchad (`characters/irish.txt`), born 965.1.1
  - `father=900`: `905` — Tadg (`characters/irish.txt`), born 985.1.1
  - `father=900`: `1026` — Sláine (`characters/irish.txt`), born 984.1.1
  - `father=900`: `83352` — Domnall (`characters/irish.txt`), born 1004.1.1
  - `father=900`: `166117` — Flann (`characters/irish.txt`), born 975.1.1
  - `father=900`: `166118` — Conchobar (`characters/irish.txt`), born 980.1.1
  - `father=900`: `166119` — Sadb (`characters/irish.txt`), born 970.1.1
  - `father=900`: `166125` — Dub Essa (`characters/irish.txt`), born 1006.1.1
  - `father=900`: `166126` — Bébinn (`characters/irish.txt`), born 989.1.1
  - `father=900`: `166128` — Blanaid (`characters/irish.txt`), born 962.9.1

## Chronology (date order as in file; statements verbatim)

- **941.1.1** — `birth="941.1.1"; create_bloodline={ type = brian_boru has_dlc = "Holy Fury" }`
- **962.1.1** — `add_spouse=166116`
- **978.1.1** — `dynasty=695`
- **983.1.1** — `add_spouse=166123`
- **999.1.1** — `add_spouse=166102`
- **1002.1.1** — `remove_spouse=166102`
- **1002.2.1** — `add_spouse=166124`
- **1014.4.23** — `death="1014.4.23"`

## History entries (verbatim)

### 941.1.1

```text
	941.1.1={
		birth="941.1.1"
		create_bloodline = {
			type = brian_boru
			has_dlc = "Holy Fury"
		}
	}
```

### 962.1.1

```text
	962.1.1={
		add_spouse=166116
	}
```

### 978.1.1

```text
	978.1.1={
		dynasty=695 #Ua Briain
	}
```

### 983.1.1

```text
	983.1.1={
		add_spouse=166123
	}
```

### 999.1.1

```text
	999.1.1={
		add_spouse=166102
	}
```

### 1002.1.1

```text
	1002.1.1={
		remove_spouse=166102
	}
```

### 1002.2.1

```text
	1002.2.1={
		add_spouse=166124
	}
```

### 1014.4.23

```text
	1014.4.23={
		death="1014.4.23"
	}
```

## Full character block (verbatim)

```text
900 = {
	name="Brian"
	# AKA: Brian Bóruma
	dynasty=100009 #Dál gCais
	martial=9
	diplomacy=5
	intrigue=7
	stewardship=7
	religion="catholic"
	culture="irish"
	trait="wroth"
	trait="brave"
	trait="martial_cleric"
	father=83330 #Cennétig of Dál gCais
	mother=166063 #Bé Binn of Uí Briúin Seóla
	941.1.1={
		birth="941.1.1"
		create_bloodline = {
			type = brian_boru
			has_dlc = "Holy Fury"
		}
	}
	962.1.1={
		add_spouse=166116
	}
	978.1.1={
		dynasty=695 #Ua Briain
	}
	983.1.1={
		add_spouse=166123
	}
	999.1.1={
		add_spouse=166102
	}
	1002.1.1={
		remove_spouse=166102
	} #Divorce
	1002.2.1={
		add_spouse=166124
	}
	1014.4.23={
		death="1014.4.23"
	}
}
```
