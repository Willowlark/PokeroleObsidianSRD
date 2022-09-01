---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon dashes at great speed using the rocks on its body to strike
  its foe upon impact.
DmgType: PHYSICAL
Effect: Priority 1.
Name: Accelerock
Power: 2
Target: Foe
Type: Rock
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