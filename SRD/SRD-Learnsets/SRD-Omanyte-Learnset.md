---
DexID: 0138
Moves:
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leer|Leer]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Tickle|Tickle]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Name: Omanyte
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