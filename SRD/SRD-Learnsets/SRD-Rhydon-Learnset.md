---
DexID: '0112'
Moves:
- - Starter
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Stomp|Stomp]]'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Smack Down|Smack Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Drill Run|Drill Run]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Horn Drill|Horn Drill]]'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Pro
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
Name: Rhydon
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