---
Moves:
- - Starter
  - '[[SRD-Bide|Bide]]'
- - Starter
  - '[[SRD-Detect|Detect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Acupressure|Acupressure]]'
- - Ace
  - '[[SRD-Power Trick|Power Trick]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
Name: Medicham (Mega Form)
Pokedex: '[[SRD-Medicham (Mega Form)|Medicham (Mega Form)]]'
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
