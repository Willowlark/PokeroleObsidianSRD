---
Moves:
- - Starter
  - '[[SRD-Belch|Belch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Stockpile|Stockpile]]'
- - Beginner
  - '[[SRD-Swallow|Swallow]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dive|Dive]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
Name: Cramorant
Pokedex: '[[SRD-Cramorant|Cramorant]]'
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
