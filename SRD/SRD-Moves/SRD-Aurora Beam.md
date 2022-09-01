---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon shoots a beautiful rainbow colored beam that may leave the
  foe flabbergasted.
DmgType: SPECIAL
Effect: Roll 1 Chance Dice to Reduce foe's Strength.
Name: Aurora Beam
Power: 2
Target: Foe
Type: Ice
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