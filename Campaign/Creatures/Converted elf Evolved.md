---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Converted Elf Evolved
size: Medium
type: Undead
alignment: Lawful Evil
initiative: "+4 (14)"
ac: 16
ac_class: natural armor
hp: 30
speed: "40 ft."
stats: [12, 18, 18, 9, 15, 7]
saves:
  - dexterity: 7
  - wisdom: 5
skillsaves:
  - perception: 5
  - stealth: 7
damage_vulnerabilities: "Bludgeoning"
damage_resistances: "Piercing, Slashing, Necrotic"
damage_immunities: "Poison"
condition_immunities: "Exhaustion, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 15"
languages: "Understands Elvish and Common but can't speak"
cr: "4"
cr_detail: "XP 1,100; PB +3"
traits:
  - name: Converted Blood
    desc: |-
      Whenever the elf rolls damage, it deals an extra 3 (1d6) poison damage as part of that damage roll.
  - name: Poisoned Wound
    desc: |-
      A creature that takes poison damage from the elf has its speed halved until the start of the elf's next turn. If the creature already has its speed reduced by Poisoned Wound when it takes poison damage from another creature, its speed becomes 0 until the start of that other creature's next turn.
actions:
  - name: Multiattack
    desc: |-
      The elf makes two Poisoned Bone Blade or Poisoned Bone Longbow attacks.
  - name: Poisoned Bone Blade
    desc: |-
      *Melee Attack Roll:* +6, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 3 (1d6) poison damage.
  - name: Poisoned Bone Longbow
    desc: |-
      *Ranged Attack Roll:* +6, range 150/600 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage plus 3 (1d6) poison damage.
bonus_actions:
  - name: Predatory Step
    desc: |-
      The elf moves up to 20 feet without provoking opportunity attacks.
  - name: Quick Slash
    desc: |-
      The elf makes one Poisoned Bone Blade attack.
```
