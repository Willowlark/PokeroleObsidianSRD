---
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Play Nice|Play Nice]]'
- - Beginner
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Amateur
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wish|Wish]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Copycat|Copycat]]'
Name: Slurpuff
Pokedex: '[[SRD-Slurpuff|Slurpuff]]'
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
