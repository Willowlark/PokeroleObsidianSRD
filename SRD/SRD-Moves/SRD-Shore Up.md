---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Heal:
    Type: Basic
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon gathers the sand around itself to restore its body to shape.
DmgType: Support
Effect: Basic Heal. If performed under Sandstorm weather, this move is a Complete
  Heal.
Name: Shore Up
Power: 0
Target: User
Type: Ground
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