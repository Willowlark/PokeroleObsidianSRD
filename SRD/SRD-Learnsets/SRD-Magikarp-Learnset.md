---
DexID: 0129
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
Name: Magikarp
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