---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  BlockDamagePool: 2
Damage1: Special
Damage2: ''
Description: The Pokemon summons a huge swarm of bugs to prevent the foe from escaping.
  Sometimes the swarm may take a hit to the foe. The call extends for hundreds of
  yards.
DmgType: Special
Effect: Blocks. Roll 2 Dice of Damage against the foe at the end of each Round. Lasts
  4 Rounds.
Name: Infestation
Power: 1
Target: Foe
Type: Bug
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