---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The user charges its fists with electricity, and upon impact the charge
  materializes into plasma that adds an electric element to all of its Normal moves.
DmgType: PHYSICAL
Effect: Fist Based. If successful, all Normal-Type Moves of the user will be considered
  Electric Type until the end of the Scene.
Name: Plasma Fists
Power: 4
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