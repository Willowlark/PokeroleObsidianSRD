---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Damage1: Strength
Damage2: ''
Description: ''
DmgType: Physical
Effect: This Move's Damage Pool, can be rolled with either the Strength or Special
  Attribute, dealing Physical or Special Damage respectively. Choose whatever is most
  convenient for the user.
Name: Photon Geyser (Physical)
Power: 4
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