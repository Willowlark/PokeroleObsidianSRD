---
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Fake Out|Fake Out]]'
- - Beginner
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Pay Day|Pay Day]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Flatter|Flatter]]'
Name: Meowth (Alolan Form)
Pokedex: '[[SRD-Meowth (Alolan Form)|Meowth (Alolan Form)]]'
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
