---
Moves:
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Charge Beam|Charge Beam]]'
Name: Vikavolt
Pokedex: '[[SRD-Vikavolt|Vikavolt]]'
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
