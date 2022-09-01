---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon unleashes a swirling and glittery energy that releases a
  pleasant aroma that soothes the body and has healing properties.
DmgType: SPECIAL
Effect: If successful, heal any Status Ailment on the User and Allies. If the user
  of this Move is at its Final Stage of Evolution, this move fails. -1 Accuracy.
Name: Sparkly Swirl
Power: 3
Target: Foe
Type: Fairy
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