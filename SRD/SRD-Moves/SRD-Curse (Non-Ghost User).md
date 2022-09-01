---
Accuracy1: WILL
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The Pokemon prepares to deal and receive damage by muttering something
  not appropriate for kids.
DmgType: SUPPORT
Effect: Increase the User's Strength and Defense. Reduce the User's Dexterity. This
  effect is only for Pokemon who are not Ghost-Type.
Name: Curse (Non-Ghost User)
Power: 0
Target: User
Type: Ghost
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