---
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Beginner
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Spite|Spite]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Ace
  - '[[SRD-Mystical Fire|Mystical Fire]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
Name: Mismagius
Pokedex: '[[SRD-Mismagius|Mismagius]]'
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
