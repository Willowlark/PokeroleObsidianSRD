---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon lets out an electric beam then uses the remaining charge
  to boost its power.
DmgType: SPECIAL
Effect: Roll 5 Chance Dice to Increase the User's Special. -1 Accuracy.
Name: Charge Beam
Power: 2
Target: Foe
Type: Electric
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