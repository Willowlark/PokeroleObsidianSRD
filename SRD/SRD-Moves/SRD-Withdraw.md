---
Accuracy1: VITALITY
Accuracy2: BRAWL
Damage1: ''
Damage2: ''
Description: The user hides inside its hard shell to protect itself from incoming
  attacks.
DmgType: SUPPORT
Effect: Increase User's Defense.
Name: Withdraw
Power: 0
Target: User
Type: Water
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