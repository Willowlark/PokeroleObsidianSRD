---
Accuracy1: Tough
Accuracy2: Perform
AddedEffects:
  FixedDamage:
    BasedOn: MaxHp
    Percentage: 0.5
  StatChanges:
  - Affects: User
    Stages: 3
    Stats:
    - Strength
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon Roars a war cry while hitting its Belly.
DmgType: Support
Effect: User deals Damage to itself equal to Half of its total HP rounded down. Increase
  User's Strength by 3.
Name: Belly Drum
Power: 0
Target: User
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