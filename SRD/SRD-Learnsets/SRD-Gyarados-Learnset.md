---
Moves:
- - Starter
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - Beginner
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
Name: Gyarados
Pokedex: '[[SRD-Gyarados|Gyarados]]'
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
