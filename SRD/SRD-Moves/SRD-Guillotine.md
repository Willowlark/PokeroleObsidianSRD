---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  FixedDamage:
    BasedOn: Hp
    Percentage: 1
Attributes:
  AccuracyReduction: 5
  Lethal: true
Damage1: ''
Damage2: ''
Description: The Pokemon uses the sharpest part of its body to almost snap the neck
  of its foe. It is a devastating attack. The foe must be lucky to get out of it alive.
DmgType: Physical
Effect: The target is dealt damage equal to its remaining HP plus 1 Lethal. -5 Accuracy.
Name: Guillotine
Power: 0
Target: Foe
Type: Normal
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