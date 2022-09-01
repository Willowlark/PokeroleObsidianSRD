---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The user swiftly uses its claws to strike the foe multiple times.
DmgType: PHYSICAL
Effect: Successive Actions. -1 Accuracy.
Name: Fury Swipes
Power: 1
Target: Foe
Type: Normal
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