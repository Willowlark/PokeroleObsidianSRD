---
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bone Club|Bone Club]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Bonemerang|Bonemerang]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bone Rush|Bone Rush]]'
- - Ace
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Retaliate|Retaliate]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Name: Marowak
Pokedex: '[[SRD-Marowak|Marowak]]'
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
