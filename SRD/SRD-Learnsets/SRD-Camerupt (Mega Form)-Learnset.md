---
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Magnitude|Magnitude]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Eruption|Eruption]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Name: Camerupt (Mega Form)
Pokedex: '[[SRD-Camerupt (Mega Form)|Camerupt (Mega Form)]]'
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
