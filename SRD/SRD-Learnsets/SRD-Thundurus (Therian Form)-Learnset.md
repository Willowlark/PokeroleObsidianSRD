---
Moves:
- - Master
  - '[[SRD-Uproar|Uproar]]'
- - Master
  - '[[SRD-Astonish|Astonish]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Swagger|Swagger]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Revenge|Revenge]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Heal Block|Heal Block]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Thrash|Thrash]]'
- - Master
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Master
  - '[[SRD-Electric Terrain|Electric Terrain]]'
Name: Thundurus (Therian Form)
Pokedex: '[[SRD-Thundurus (Therian Form)|Thundurus (Therian Form)]]'
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
