---
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Milk Drink|Milk Drink]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Name: Gogoat
Pokedex: '[[SRD-Gogoat|Gogoat]]'
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
