---
tags:
  - creature
---

*Yeti convertido en no-muerto por [[Orren el putrefacto]].*

```statblock
layout: 5e 2024
columnWidth: 340
name: Converted Yeti
size: Large
type: Undead
alignment: Lawful Evil
initiative: "+1 (11)"
ac: 14
ac_class: natural armor
hp: 76
hit_dice: "8d10 + 32"
speed: "40 ft., Climb 40 ft."
stats: [18, 13, 18, 6, 12, 5]
saves:
  - strength: 6
  - constitution: 6
  - wisdom: 3
skillsaves:
  - perception: 5
  - stealth: 5
damage_vulnerabilities: "Bludgeoning"
damage_resistances: "Piercing, Slashing, Necrotic"
damage_immunities: "Cold, Poison"
condition_immunities: "Exhaustion, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 15"
languages: "Understands Yeti but can't speak"
cr: "4"
cr_detail: "XP 1,100; PB +2"
traits:
  - name: Undead Fortitude
    desc: |-
      If the yeti is reduced to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant, fire, or from a critical hit. On a success, the yeti drops to 1 hit point instead.
  - name: Fear of Fire
    desc: |-
      If the yeti takes Fire damage, it has Disadvantage on attack rolls and ability checks until the end of its next turn.
  - name: Dead Mountain Climber
    desc: |-
      The yeti has advantage on Strength checks made to climb, grapple, or shove while on ice, stone, or snow.
actions:
  - name: Multiattack
    desc: |-
      The yeti can use Bone-Chilling Gaze and makes two attacks, using Claw or Ice Throw in any combination.
  - name: Claw
    desc: |-
      *Melee Attack Roll:* +6, reach 5 ft. *Hit:* 9 (1d10 + 4) Slashing damage plus 4 (1d8) Cold damage.
  - name: Ice Throw
    desc: |-
      *Ranged Attack Roll:* +6, range 30/120 ft. *Hit:* 8 (1d8 + 4) Bludgeoning damage plus 4 (1d8) Cold damage.
  - name: Bone-Chilling Gaze
    desc: |-
      *Constitution Saving Throw:* DC 14, one creature the yeti can see within 30 feet. *Failure:* 9 (2d8) Cold damage, and the target has the Paralyzed condition until the start of the yeti's next turn unless the target has Immunity to Cold damage. *Success:* The target is immune to the Bone-Chilling Gaze of converted yetis for 1 hour.
bonus_actions:
  - name: Corpse Rush (Recharge 5-6)
    desc: |-
      The yeti moves up to half its Speed toward a creature it can see. If it ends this movement within 5 feet of that creature, its next Claw attack this turn has advantage.
```

Converted yetis are frozen corpses dragged back into motion by Orren's necromancy. Their fur hangs in dead clumps over exposed bone, and their eyes glow with a pale blue hunger. They still hunt like yetis, but without breath, fear, or exhaustion.
