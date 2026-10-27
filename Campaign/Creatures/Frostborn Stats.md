---
tags:
  - creature
  - stats
---

Mecánica del **[[Frostborn]]**. La descripción y el uso en campaña van en esa nota.

```statblock
layout: 5e 2024
columnWidth: 340
name: Frostborn Mystic
size: Small
type: Humanoid
alignment: Neutral
initiative: "+2 (12)"
ac: 15
hp: 81
hit_dice: "18d8"
speed: "30 ft."
stats: [9, 14, 11, 17, 12, 11]
saves:
  - intelligence: 6
  - wisdom: 4
skillsaves:
  - arcana: 6
  - history: 6
  - perception: 4
gear: "Quarterstaff, wand"
senses: "Passive Perception 14"
languages: "Common, Frostborn, plus two other languages"
cr: "6"
cr_detail: "XP 2,300; PB +3"
actions:
  - name: Multiattack
    desc: |-
      The frostborn makes three Arcane Burst attacks.
  - name: Quarterstaff
    desc: |-
      *Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d8 + 2) bludgeoning damage.
  - name: Arcane Burst
    desc: |-
      *Melee or Ranged Attack Roll:* +6, reach 5 ft. or range 120 ft. *Hit:* 16 (3d8 + 3) force damage.
  - name: Spellcasting
    desc: |-
      The frostborn casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14, +6 to hit with spell attacks):

      - **At Will:** [*ray of frost*](https://www.aidedd.org/spell/ray-of-frost)
      - **2/Day Each:** [*ice storm*](https://www.aidedd.org/spell/ice-storm), [*invisibility*](https://www.aidedd.org/spell/invisibility)
      - **1/Day Each:** [*cone of cold*](https://www.aidedd.org/spell/cone-of-cold), [*fly*](https://www.aidedd.org/spell/fly)
  - name: Conserved Breath (3/Day)
    desc: |-
      The frostborn chooses one creature it can see within 30 feet. The target gains 21 (4d8 + 3) temporary hit points, which last for 1 hour.
bonus_actions:
  - name: Misty Step (3/Day)
    desc: |-
      The frostborn casts [*misty step*](https://www.aidedd.org/spell/misty-step), using the same spellcasting ability as Spellcasting.
reactions:
  - name: Witnessing Ice (3/Day)
    desc: |-
      When a creature the frostborn can see within 30 feet is hit by an attack, the frostborn sheaths the target in spectral ice. The target gains a +5 bonus to AC against the triggering attack, potentially causing it to miss, and keeps that bonus until the start of the target's next turn.
```
