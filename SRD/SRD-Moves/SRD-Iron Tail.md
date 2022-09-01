---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The user hits the foe with its hardened tail. The target is left vulnerable
  against subsequent attacks.
DmgType: PHYSICAL
Effect: Roll 3 Chance Dice to Reduce the foe's Defense. -3 Accuracy.
Name: Iron Tail
Power: 4
Target: Foe
Type: Steel
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