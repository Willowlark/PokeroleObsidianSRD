---
DexID: '0436'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Imprison|Imprison]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Heal Block|Heal Block]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
Name: Bronzor
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