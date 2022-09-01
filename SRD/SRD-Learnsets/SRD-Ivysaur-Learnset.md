---
DexID: '0002'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Ace
  - '[[SRD-Synthesis|Synthesis]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Name: Ivysaur
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM "Pokerole SRD/SRD-Learnsets"
flatten moves as T
where file.path = this.file.path
```