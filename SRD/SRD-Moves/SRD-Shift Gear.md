---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The Pokemon has its gears rotate quickly,. Working like a powerful machine.
DmgType: SUPPORT
Effect: Increase the User's Strength by 1 and Dexterity by 2.
Name: Shift Gear
Power: 0
Target: User
Type: Steel
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`