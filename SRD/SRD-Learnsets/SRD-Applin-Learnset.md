---
Moves:
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Pro
  - '[[SRD-Rollout|Rollout]]'
- - Pro
  - '[[SRD-Recycle|Recycle]]'
Name: Applin
Pokedex: '[[SRD-Applin|Applin]]'
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
