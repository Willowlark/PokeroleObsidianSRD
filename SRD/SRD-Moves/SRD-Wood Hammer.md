---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Recoil: true
Damage1: Strength
Damage2: ''
Description: The Pokemon recklessly slams the foe with a part of its rugged body,
  the user also gets hurt in the process.
DmgType: Physical
Effect: Recoil.
Name: Wood Hammer
Power: 5
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