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
  - '[[SRD-Hex|Hex]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Bonemerang|Bonemerang]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Shadow Bone|Shadow Bone]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Retaliate|Retaliate]]'
- - Ace
  - '[[SRD-Bone Rush|Bone Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Pro
  - '[[SRD-Flame Charge|Flame Charge]]'
Name: Marowak (Alolan Form)
Pokedex: '[[SRD-Marowak (Alolan Form)|Marowak (Alolan Form)]]'
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
