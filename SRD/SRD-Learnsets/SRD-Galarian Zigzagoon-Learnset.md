---
DexID: 0263G
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Snarl|Snarl]]'
- - Amateur
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Taunt|Taunt]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Parting Shot|Parting Shot]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
Name: Galarian Zigzagoon
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