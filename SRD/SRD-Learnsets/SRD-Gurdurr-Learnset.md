---
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Low Kick|Low Kick]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Foresight|Foresight]]'
- - Pro
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Name: Gurdurr
Pokedex: '[[SRD-Gurdurr|Gurdurr]]'
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
