---
Accuracy1: DEXTERITY
Accuracy2: BRAWL/CHANNEL
Damage1: STRENGTH/SPECIAL
Damage2: ''
Description: ''
DmgType: PHYSICAL/SPECIAL
Effect: The most basic attack.
Name: Struggle
Power: 0
Target: Foe
Type: Typeless
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