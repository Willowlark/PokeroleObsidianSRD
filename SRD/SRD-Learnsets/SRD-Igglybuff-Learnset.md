---
Moves:
- - Starter
  - '[[SRD-Sing|Sing]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
Name: Igglybuff
Pokedex: '[[SRD-Igglybuff|Igglybuff]]'
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
