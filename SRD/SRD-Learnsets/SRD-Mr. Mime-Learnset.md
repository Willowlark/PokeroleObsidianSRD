---
DexID: '0122'
Moves:
- - Starter
  - '[[SRD-Barrier|Barrier]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Beginner
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Beginner
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Beginner
  - '[[SRD-Trick|Trick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Power Swap|Power Swap]]'
- - Amateur
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Meditate|Meditate]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Substitute|Substitute]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recycle|Recycle]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Role Play|Role Play]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
Name: Mr. Mime
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