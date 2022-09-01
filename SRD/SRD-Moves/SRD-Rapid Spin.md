---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon spins swiftly to strike the foe. Anything near will be scattered
  around.
DmgType: PHYSICAL
Effect: Remove Entry Hazards (Spikes, Stealth Rock, etc.) and Leech Seed from the
  user's side of the field. Increase user's Dexterity.
Name: Rapid Spin
Power: 2
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