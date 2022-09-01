---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The user launches itself up and falls down with a brutal kick. It might
  hurt the user if it doesn't hit the target.
DmgType: PHYSICAL
Effect: If Accuracy Roll is unsuccessful, deal 5 Dice of Damage to the User. -1 Accuracy.
Name: High Jump Kick
Power: 5
Target: Foe
Type: Fighting
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