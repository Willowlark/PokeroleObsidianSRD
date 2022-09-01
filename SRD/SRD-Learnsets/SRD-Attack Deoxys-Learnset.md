---
DexID: 0386F1
Moves:
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Wrap|Wrap]]'
- - Master
  - '[[SRD-Night Shade|Night Shade]]'
- - Master
  - '[[SRD-Teleport|Teleport]]'
- - Master
  - '[[SRD-Taunt|Taunt]]'
- - Master
  - '[[SRD-Pursuit|Pursuit]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Psycho Boost|Psycho Boost]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Toxic|Toxic]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Bind|Bind]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
Name: Attack Deoxys
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