---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The Pokemon will use its tail to make a long swipe at its foes. A few
  cracks are heard, and the foe will limp afterwards.
DmgType: Physical
Effect: All Foes in Range. Reduce the Strength of those affected.
Name: Breaking Swipe
Power: 2
Target: All Foes
Type: Dragon
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`