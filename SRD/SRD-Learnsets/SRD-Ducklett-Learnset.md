---
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defog|Defog]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
- - Pro
  - '[[SRD-Mirror Move|Mirror Move]]'
Name: Ducklett
Pokedex: '[[SRD-Ducklett|Ducklett]]'
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
