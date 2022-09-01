---
DexID: '0045'
Moves:
- - Starter
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Petal Dance|Petal Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Name: Vileplume
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