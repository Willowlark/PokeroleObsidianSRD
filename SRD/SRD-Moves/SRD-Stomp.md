---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon steps and stomps the foe, the weight may leave the target
  squashed on the floor.
DmgType: PHYSICAL
Effect: Roll 3 Chance Dice to Flinch the foe.
Name: Stomp
Power: 2
Target: Foe
Type: Normal
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