---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Dragonborn Rogue
size: Medium
type: Humanoid
subtype: Dragonborn
alignment: Neutral
initiative: "+7 (17)"
ac: 16
hp: 84
hit_dice: "13d8 + 26"
speed: "30 ft."
stats: [11, 18, 14, 14, 12, 14]
saves:
  - dexterity: 7
  - intelligence: 5
skillsaves:
  - acrobatics: 7
  - perception: 4
  - sleight of hand: 7
  - stealth: 10
damage_resistances: "Poison"
gear: "Hand Crossbow, Shortsword, Studded Leather Armor, Thieves' Tools"
senses: "Darkvision 60 ft., Passive Perception 14"
languages: "Common, Draconic, Thieves' Cant"
cr: "5"
cr_detail: "XP 1,800; PB +3"
traits:
  - name: Sneak Attack (1/Turn)
    desc: |-
      The rogue deals an extra 10 (3d6) damage when it hits a target with an attack roll and has Advantage on the roll, or when the target is within 5 feet of an ally of the rogue that doesn't have the Incapacitated condition and the rogue doesn't have Disadvantage on the roll.
actions:
  - name: Multiattack
    desc: |-
      The rogue makes three attacks, using Shortsword or Hand Crossbow in any combination.
  - name: Shortsword
    desc: |-
      *Melee Attack Roll:* +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage.
  - name: Hand Crossbow
    desc: |-
      *Ranged Attack Roll:* +7, range 30/120 ft. *Hit:* 7 (1d6 + 4) Piercing damage.
  - name: Poison Breath (Recharge 5–6)
    desc: |-
      *Constitution Saving Throw:* DC 15, each creature in a 15-foot Cone. *Failure:* 22 (4d10) Poison damage. *Success:* Half damage.
bonus_actions:
  - name: Cunning Action
    desc: |-
      The rogue takes the Dash, Disengage, or Hide action.
reactions:
  - name: Uncanny Dodge
    desc: |-
      *Trigger:* The rogue is hit by an attack roll made by a creature it can see. *Response:* The rogue halves the attack's damage against itself (round down).
```
