---
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Sleep Talk|Sleep Talk]]'
Name: Tauros
Pokedex: '[[SRD-Tauros|Tauros]]'
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
