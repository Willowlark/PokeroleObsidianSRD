---
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Me First|Me First]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Steel Wing|Steel Wing]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Pro
  - '[[SRD-Air Cutter|Air Cutter]]'
Name: Fletchling
Pokedex: '[[SRD-Fletchling|Fletchling]]'
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
