---
Accuracy1: Clever
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: User
    Type: ChangedAbility
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user swaps its identity with the target, making both feel like they
  are from each other's species.
DmgType: Support
Effect: Switch Abilities with the foe. The abilities Flower Gift. Illusion. Imposter.
  Stance Change. Wonder Guard. Plot Device and others cannot be switched.
Name: Skill Swap
Power: 0
Target: Foe
Type: Psychic
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