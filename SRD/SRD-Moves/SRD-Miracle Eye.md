---
Accuracy1: INSIGHT
Accuracy2: ALERT
Damage1: ''
Damage2: ''
Description: The user's sight transcends the flesh and can look directly into the
  innermost mental pressence of everyone around. Hidden enemies can be detected.
DmgType: SUPPORT
Effect: The User may hit Dark Type Pokemon with Psychic Moves. The Pokemon ignores
  Evasion modifiers. Opponents can't reduce the User's Accuracy.
Name: Miracle Eye
Power: 0
Target: User
Type: Psychic
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