---
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Glare|Glare]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Fly|Fly]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
Name: Drampa
Pokedex: '[[SRD-Drampa|Drampa]]'
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
