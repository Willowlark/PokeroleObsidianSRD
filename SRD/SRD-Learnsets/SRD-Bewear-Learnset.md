---
DexID: '0761'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Bind|Bind]]'
- - Amateur
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
Name: Bewear
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