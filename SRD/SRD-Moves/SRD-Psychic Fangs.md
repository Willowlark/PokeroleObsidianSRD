---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  DestroyShield: true
Damage1: Strength
Damage2: ''
Description: The Pokemon bares its fangs to bite the foe, psychic energy begins piercing
  before the actual fangs make contact.
DmgType: Physical
Effect: If a Barrier is in place on the foe's side (ie. Light Screen. Reflect) destroy
  it.
Name: Psychic Fangs
Power: 3
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