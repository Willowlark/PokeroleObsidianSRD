---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  FixedDamage:
    BasedOn: Hp
    MaxValue: 10
    Percentage: 0.5
Attributes:
  AccuracyReduction: 1
  IgnoreDefenses: true
Damage1: ''
Damage2: ''
Description: The Pokemon jumps at the foe to crush it with an awful bite.
DmgType: Physical
Effect: Damage Roll is Half of the Foe's remaining HP (up to 10) rounded down. If
  the remaining HP of the foe is 1 this move fails. Ignore the foe's Defenses. -1
  Accuracy.
Name: Super Fang
Power: 0
Target: Foe
Type: Normal
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