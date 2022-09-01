---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: Teleport the user and one more creature to a place of tranquility and
  high psychic resonance such as Pokemon Centers. Ceilings and walls block this move
  from working.
DmgType: SUPPORT
Effect: In the wild, the battle ends. In official battles, it counts as the Pokemon
  being recalled. Teleportation distances depend on Special and Storyteller's discretion.
Name: Teleport
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