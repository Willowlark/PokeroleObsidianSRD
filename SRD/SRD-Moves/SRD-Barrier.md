---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Def
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user casts a protective field around itself.
DmgType: Support
Effect: Increase the User's Defense by 2.
Name: Barrier
Power: 0
Target: Foe
Type: Psychic
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