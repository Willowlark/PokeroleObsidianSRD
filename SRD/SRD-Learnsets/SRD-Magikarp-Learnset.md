---
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
Name: Magikarp
Pokedex: '[[SRD-Magikarp|Magikarp]]'
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
