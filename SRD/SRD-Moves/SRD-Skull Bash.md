---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Def
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The Pokemon withdraws to its shell then charges against the foe.
DmgType: Physical
Effect: Increase the User's Defense. Charge.
Name: Skull Bash
Power: 5
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