---
Moves:
- - Starter
  - '[[SRD-Clamp|Clamp]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
Name: Clamperl
Pokedex: '[[SRD-Clamperl|Clamperl]]'
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
