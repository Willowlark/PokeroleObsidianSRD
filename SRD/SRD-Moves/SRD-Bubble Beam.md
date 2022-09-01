---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: A long stream of bubbles hits the foe, the bubble foam may prevent the
  target from moving freely.
DmgType: SPECIAL
Effect: Roll 1 Chance Dice to Reduce the foe's Dexterity.
Name: Bubble Beam
Power: 3
Target: Foe
Type: Water
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