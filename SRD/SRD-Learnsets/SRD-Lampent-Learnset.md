---
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Minimize|Minimize]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - Beginner
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Curse|Curse]]'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Pain Split|Pain Split]]'
- - Ace
  - '[[SRD-Overheat|Overheat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Pro
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Haze|Haze]]'
Name: Lampent
Pokedex: '[[SRD-Lampent|Lampent]]'
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
