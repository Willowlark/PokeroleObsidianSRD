---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon attacks with a small destructive shock that can go through
  armor, thick hide, or walls to deal some damage.
DmgType: Special
Effect: This moves always inflicts 1 damage.
Name: Sonic Boom
Power: 0
Target: Foe
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