---
Moves:
- - Starter
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Twineedle|Twineedle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Ace
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
Name: Beedrill (Mega Form)
Pokedex: '[[SRD-Beedrill (Mega Form)|Beedrill (Mega Form)]]'
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
