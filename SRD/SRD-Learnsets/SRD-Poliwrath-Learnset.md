---
Moves:
- - Beginner
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Ace
  - '[[SRD-Mind Reader|Mind Reader]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Name: Poliwrath
Pokedex: '[[SRD-Poliwrath|Poliwrath]]'
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
