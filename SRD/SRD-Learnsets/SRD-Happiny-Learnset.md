---
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Copycat|Copycat]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Present|Present]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Name: Happiny
Pokedex: '[[SRD-Happiny|Happiny]]'
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
