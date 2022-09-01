---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The user lets out an infectious yawn that will make anyone drowsy enough
  to fall asleep pretty soon.
DmgType: SUPPORT
Effect: If the target is not removed from battle by the start of its next Round, it
  will fall asleep.
Name: Yawn
Power: 0
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