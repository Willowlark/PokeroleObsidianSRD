---
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Icicle Crash|Icicle Crash]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Play Nice|Play Nice]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
Name: Beartic
Pokedex: '[[SRD-Beartic|Beartic]]'
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
