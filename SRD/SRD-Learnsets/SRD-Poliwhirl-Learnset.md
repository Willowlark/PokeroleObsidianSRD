---
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
Name: Poliwhirl
Pokedex: '[[SRD-Poliwhirl|Poliwhirl]]'
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
