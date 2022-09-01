---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The user eats the dreams of a sleeping target. When the foe wakes up,
  it will feel weak and empty.
DmgType: SPECIAL
Effect: The user restores HP equal to half the damage dealt, rounded down. The target
  must be asleep, this move will fail otherwise.
Name: Dream Eater
Power: 4
Target: Foe
Type: Psychic
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