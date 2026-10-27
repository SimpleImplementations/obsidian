---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Converted Goliath Evolved
size: Large
type: Undead
alignment: Neutral Evil
initiative: "+0 (10)"
ac: 17
ac_class: natural armor
hp: 90
speed: "30 ft."
stats: [20, 10, 18, 6, 12, 5]
saves:
  - strength: 8
  - constitution: 7
  - wisdom: 4
skillsaves:
  - athletics: 8
  - perception: 4
damage_resistances: "Bludgeoning, Piercing, Slashing, Necrotic, Cold"
damage_immunities: "Poison"
condition_immunities: "Exhaustion, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 14"
languages: "Understands Giant and Common but can't speak"
cr: "6"
cr_detail: "XP 2,300; PB +3"
traits:
  - name: Converted Blood
    desc: |-
      Whenever the goliath rolls damage, it deals an extra 3 (1d6) poison damage as part of that damage roll.
  - name: Poisoned Wound
    desc: |-
      A creature that takes poison damage from the goliath has its speed halved until the start of the goliath's next turn. If the creature already has its speed reduced by Poisoned Wound when it takes poison damage from another creature, its speed becomes 0 until the start of that other creature's next turn.
actions:
  - name: Bone Maul
    desc: |-
      *Melee Attack Roll:* **+9**, reach 10 ft., one target. *Hit:* **15 (2d8 + 6) bludgeoning damage plus 3 (1d6) poison damage.**
reactions:
  - name: Locking Strike
    desc: |-
      When a creature the goliath can see moves out of the goliath's reach, the goliath makes one Bone Maul attack against it. On a hit, the target's speed becomes 0 until the end of the current turn.
  - name: Intercept Blow
    desc: |-
      When a creature the goliath can see within 5 feet is hit by an attack, the goliath can impose disadvantage on that attack roll.
```
