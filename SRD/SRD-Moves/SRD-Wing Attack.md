---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The user flies towards the foe and strikes with its wings.
DmgType: Physical
Effect: '-'
Name: Wing Attack
Power: 2
Target: Foe
Type: Flying
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`