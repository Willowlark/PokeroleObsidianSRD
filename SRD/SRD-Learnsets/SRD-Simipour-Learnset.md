---
Moves:
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scald|Scald]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Name: Simipour
Pokedex: '[[SRD-Simipour|Simipour]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
