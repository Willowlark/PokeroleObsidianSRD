---
Accuracy1: INSIGHT
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The user moves as if locking a door. It takes a few moments before everyone
  realizes that they are not really trapped.
DmgType: SUPPORT
Effect: Blocks. Last 1 Round.
Name: Fairy Lock
Power: 0
Target: Battlefield
Type: Fairy
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