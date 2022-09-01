---
DexID: '0467'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Name: Magmortar
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