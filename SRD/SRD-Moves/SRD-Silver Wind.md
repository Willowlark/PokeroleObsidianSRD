---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon blows a beautiful silver colered wind that harms the foe,
  the performance may give the user a big confidence boost.
DmgType: SPECIAL
Effect: Roll 1 Chance Dice to Increase User's Strength. Dexterity. Special. Defense.
  Sp. Defense.
Name: Silver Wind
Power: 2
Target: Foe
Type: Bug
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