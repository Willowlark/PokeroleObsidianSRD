---
Accuracy1: VITALITY
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: One Pokemon's trash is another one's treasure.
DmgType: SUPPORT
Effect: The Pokemon reuses an Item that has already been spent. (Berries etc.) An
  Item may not be recycled more than 5 times.
Name: Recycle
Power: 0
Target: User
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