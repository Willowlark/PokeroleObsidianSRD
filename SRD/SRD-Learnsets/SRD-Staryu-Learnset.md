---
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Reflect Type|Reflect Type]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Name: Staryu
Pokedex: '[[SRD-Staryu|Staryu]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
