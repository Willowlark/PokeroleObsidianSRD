---
Moves:
- - Starter
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Pro
  - '[[SRD-Supersonic|Supersonic]]'
- - Pro
  - '[[SRD-Infestation|Infestation]]'
Name: Dottler
Pokedex: '[[SRD-Dottler|Dottler]]'
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
