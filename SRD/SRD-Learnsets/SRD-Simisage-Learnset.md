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
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Name: Simisage
Pokedex: '[[SRD-Simisage|Simisage]]'
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
