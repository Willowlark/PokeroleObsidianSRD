---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes: {}
Damage1: ''
Damage2: ''
Description: A powerful somniferous spore that is shot at the target to make it fall
  asleep.
DmgType: Support
Effect: Put the Target to Sleep.
Name: Spore
Power: 0
Target: Foe
Type: Grass
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