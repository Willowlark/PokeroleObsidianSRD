---
Moves:
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Refresh|Refresh]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Trump Card|Trump Card]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Name: Eevee
Pokedex: '[[SRD-Eevee|Eevee]]'
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
