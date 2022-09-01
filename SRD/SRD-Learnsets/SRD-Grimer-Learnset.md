---
DexID: 0088
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sludge Wave|Sludge Wave]]'
- - Ace
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Scary Face|Scary Face]]'
Name: Grimer
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