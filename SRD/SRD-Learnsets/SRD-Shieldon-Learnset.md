---
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - Beginner
  - '[[SRD-Metal Sound|Metal Sound]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Metal Burst|Metal Burst]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Guard Split|Guard Split]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Name: Shieldon
Pokedex: '[[SRD-Shieldon|Shieldon]]'
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
