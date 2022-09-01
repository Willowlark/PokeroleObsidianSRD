---
DexID: 0853
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Name: Sinistea
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