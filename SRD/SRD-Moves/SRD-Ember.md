---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The user shoots a small flame against the target that may cause a first-degree
  burn.
DmgType: SPECIAL
Effect: Roll 1 Chance Dice to Burn the foe.
Name: Ember
Power: 2
Target: Foe
Type: Fire
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