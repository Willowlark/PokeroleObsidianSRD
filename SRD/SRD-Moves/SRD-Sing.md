---
Accuracy1: CUTE
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: With a charming song, the user lulls its foe to sleep.
DmgType: SUPPORT
Effect: Inflict Sleep on the target. Sound Based. -3 Accuracy.
Name: Sing
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