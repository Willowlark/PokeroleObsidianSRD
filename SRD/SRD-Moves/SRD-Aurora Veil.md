---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: AuroraVeil
Attributes: {}
Damage1: ''
Damage2: ''
Description: Aurora lights and hail spin around the Pokemon and its Allies, deflecting
  attacks.
DmgType: Support
Effect: User and Allies will receive 1 less Damage from both Physical and Special
  Attacks. This move will fail if not performed under Hail Weather. Lasts until Hail
  Weather is over.
Name: Aurora Veil
Power: 0
Target: User and Allies
Type: Ice
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