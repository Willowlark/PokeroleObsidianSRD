---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Target
    Type: WonderRoom
Attributes: {}
Damage1: ''
Damage2: ''
Description: Inside the Wonder Room, a strong mind makes a strong body and a resilient
  body makes a resilient mind. However, if the mind is weak, the body will be weak
  and vice-versa.
DmgType: Support
Effect: Defense and Sp. Defense will be calculated with Insight instead of Vitality.
  Lasts 4 Rounds.
Name: Wonder Room
Power: 0
Target: Battlefield
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