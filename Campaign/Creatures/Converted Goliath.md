---
tags:
  - creature
---

Tanky converted goliath variant, built to feel like an unyielding wall of bone and stone. It uses Undead Fortitude prominently and is meant to stand in front of Orren's forces and not go down easily.

Goliat convertido en esqueleto por [[Orren el putrefacto]]

```statblock
layout: 5e 2024
columnWidth: 340
name: Converted Goliath
size: Large
type: Undead
alignment: Neutral Evil
initiative: "+0 (10)"
ac: 17
ac_class: natural armor
hp: 110
hit_dice: "13d10 + 39"
speed: "30 ft."
stats: [20, 10, 16, 6, 12, 5]
saves:
  - constitution: 6
  - wisdom: 4
skillsaves:
  - athletics: 8
  - perception: 4
damage_vulnerabilities: "Bludgeoning"
damage_resistances: "Piercing, Slashing"
damage_immunities: "Poison"
condition_immunities: "Exhaustion, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 14"
languages: "Understands Giant and Common but can't speak"
cr: "5"
cr_detail: "XP 1,800; PB +3"
traits:
  - name: Undead Fortitude
    desc: |-
      If the goliath is reduced to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the goliath drops to 1 hit point instead.
  - name: Stone-Bound Frame
    desc: |-
      The goliath has advantage on Strength and Constitution saving throws, and it cannot be knocked prone while it is conscious.
  - name: Bulwark of Bone
    desc: |-
      Allies of Orren within 10 feet of the goliath gain half cover (+2 AC and Dexterity saving throws) while the goliath is conscious.
  - name: Relentless Advance
    desc: |-
      Difficult terrain doesn't cost the goliath extra movement.
actions:
  - name: Multiattack
    desc: |-
      The goliath makes two attacks with its bone maul.
  - name: Bone Maul
    desc: |-
      *Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) bludgeoning damage.
  - name: Grave Slam (Recharge 5–6)
    desc: |-
      The goliath smashes the ground. Each creature of the goliath's choice within 10 feet must succeed on a DC 15 Strength saving throw or take 18 (4d8) bludgeoning damage and be knocked prone. On a success, the creature takes half damage and isn't knocked prone.
reactions:
  - name: Intercept Blow
    desc: |-
      When a creature the goliath can see within 5 feet is hit by an attack, the goliath can impose disadvantage on that attack roll.
```

These towering undead are the skeletal remains of goliath warriors, reforged with necromantic stone-binding rituals. Their bones are etched with runes of endurance, anchoring them to the battlefield like living ramparts. They do not rage, do not flee, and do not fall easily—serving as Orren's immovable guardians and shock absorbers.
