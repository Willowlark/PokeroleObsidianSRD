---
Moves:
- - Starter
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Starter
  - '[[SRD-Flower Shield|Flower Shield]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Wish|Wish]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Amateur
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Grass Knot|Grass Knot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Name: Florges
Pokedex: '[[SRD-Florges|Florges]]'
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
