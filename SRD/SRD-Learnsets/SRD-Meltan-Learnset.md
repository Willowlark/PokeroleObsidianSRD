---
DexID: 0809
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Protect|Protect]]'
- - Pro
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Pro
  - '[[SRD-Steel Beam|Steel Beam]]'
Name: Meltan
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