# Quick character sheet

You can use this character sheet for NPC that appears only in combat. It contains minimal information, but it's very fast to create one.

## Template

```
(Agility+Reaction) - Name [Health]
---
Attack: Attribute+Skill +Weapon_damage,Weapon_quirks
Dodge: Reaction+Athletics-Armor_penalty
Block: Reaction+Parry
Armor: [Inner_Physical]+Outer_Physical / [Inner_Elemental]+Outer_Elemental
```

The expression inside `( )` is the initiative bonus.

## Example

Example for a guard with:
- Agility: 3
- Constitution: 3
- Reaction: 2
- Strength: 3
- Athletics: 3
- Melee: 2
- Parry: 2
- Spear
- Light armor

```
(3+2) - Guard [3/3/3/2]
---
Attack: 3+2 +2dmg,threatening,versatile
Dodge: 2+3-1
Block: 2+2
Armor: [0]+2 / [0]+0
```
