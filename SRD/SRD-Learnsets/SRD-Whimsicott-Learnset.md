---
Moves:
- - Starter
  - '[[SRD-Growth|Growth]]'
- - Starter
  - '[[SRD-Leech Seed|Leech Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Gust|Gust]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Memento|Memento]]'
- - Pro
  - '[[SRD-Encore|Encore]]'
Name: Whimsicott
Pokedex: '[[SRD-Whimsicott|Whimsicott]]'
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
