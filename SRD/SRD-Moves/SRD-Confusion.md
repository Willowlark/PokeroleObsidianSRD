---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The target's mind is hit by a weak psychic force that leaves them wondering
  if they were hit by an invisible enemy. Sometimes the foe is left seeing things
  that aren't really there.
DmgType: SPECIAL
Effect: Roll 1 Chance Dice to Confuse the foe.
Name: Confusion
Power: 2
Target: Foe
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