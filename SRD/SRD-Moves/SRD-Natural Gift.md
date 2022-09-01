---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: STRENGTH
Damage2: ''
Description: The user throws its berry at the foe. The results can be quite surprising.
DmgType: PHYSICAL
Effect: User loses its held berry. Ranged. See Natural Gift on p.432 for more info.
Name: Natural Gift
Power: 3
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