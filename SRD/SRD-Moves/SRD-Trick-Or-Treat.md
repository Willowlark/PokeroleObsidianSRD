---
Accuracy1: Will
Accuracy2: Allure
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon takes the target Trick-or-Treating. The target gets a ghost
  costume which somehow cannot be removed without a medium's help.
DmgType: Support
Effect: Add the Ghost type to Target's Type. (ie. Meowth will now by Normal/Ghost
  Charizard will now be Fire/Flying/Ghost) If the Pokemon already has a third type
  attached, replace it.
Name: Trick-Or-Treat
Power: 0
Target: Foe
Type: Ghost
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