---
DexID: '0065'
Moves:
- - Starter
  - '[[SRD-Teleport|Teleport]]'
- - Starter
  - '[[SRD-Kinesis|Kinesis]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ally Switch|Ally Switch]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Trick|Trick]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Name: Alakazam
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM "Pokerole SRD/SRD-Learnsets"
flatten moves as T
where file.path = this.file.path
```