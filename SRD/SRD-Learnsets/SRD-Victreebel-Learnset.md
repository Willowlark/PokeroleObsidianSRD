---
Moves:
- - Starter
  - '[[SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Swallow|Swallow]]'
- - Beginner
  - '[[SRD-Spit Up|Spit Up]]'
- - Beginner
  - '[[SRD-Stockpile|Stockpile]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Belch|Belch]]'
- - Pro
  - '[[SRD-Power Whip|Power Whip]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
Name: Victreebel
Pokedex: '[[SRD-Victreebel|Victreebel]]'
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
