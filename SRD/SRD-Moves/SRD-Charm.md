---
Accuracy1: CUTE
Accuracy2: ALLURE
Damage1: ''
Damage2: ''
Description: The Pokemon uses a cute and harmless attitude to make the foe less wary
  and aggresive.
DmgType: SUPPORT
Effect: Reduce foe's Strength by 2.
Name: Charm
Power: 0
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