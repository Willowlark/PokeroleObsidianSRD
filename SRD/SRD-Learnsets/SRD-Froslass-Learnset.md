---
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Aurora Veil|Aurora Veil]]'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
Name: Froslass
Pokedex: '[[SRD-Froslass|Froslass]]'
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
