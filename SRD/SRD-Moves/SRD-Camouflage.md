---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user mimics the environment, it becomes one with the surroundings.
DmgType: Support
Effect: For the rest of the scene the User changes type to one that fits the terrain
  it is in (i.e. Usar is in a rocky cave, becoming rock type)
Name: Camouflage
Power: 0
Target: User
Type: Normal
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