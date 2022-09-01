---
DexID: '0655'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Substitute|Substitute]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Double Team|Double Team]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Name: Froakie
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