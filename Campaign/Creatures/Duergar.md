---
tags:
  - creature
---

*Duergar veteranos de patrulla, exiliados o mercenarios de [[Calimba]], acostumbrados a pelear en túneles estrechos y a tomar prisioneros antes que hacer ruido innecesario.*

```statblock
layout: 5e 2024
columnWidth: 340
name: Duergar Rompelíneas
size: Medium
type: Humanoid
subtype: Dwarf
alignment: Lawful Evil
initiative: "+1 (11)"
ac: 18
ac_class: chain mail, shield
hp: 93
hit_dice: "11d8 + 44"
speed: "25 ft."
stats: [18, 12, 18, 11, 13, 10]
saves:
  - strength: 7
  - constitution: 7
  - wisdom: 4
skillsaves:
  - athletics: 7
  - intimidation: 3
  - perception: 4
  - stealth: 4
damage_resistances: "Poison"
senses: "Darkvision 120 ft., Passive Perception 14"
languages: "Dwarvish, Undercommon"
cr: "5"
cr_detail: "XP 1,800; PB +3"
traits:
  - name: Duergar Resilience
    desc: |-
      The duergar has advantage on saving throws against the Charmed, Paralyzed, and Poisoned conditions.
  - name: Sunlight Sensitivity
    desc: |-
      While in sunlight, the duergar has disadvantage on attack rolls and Wisdom (Perception) checks that rely on sight.
  - name: Tunnel Fighter
    desc: |-
      The duergar has advantage on melee attack rolls against a creature if both the duergar and the target are within 5 feet of stone walls, worked tunnels, or a natural choke point.
actions:
  - name: Multiattack
    desc: |-
      The duergar makes two War Pick attacks.
  - name: War Pick
    desc: |-
      *Melee Attack Roll:* +7, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing damage plus 7 (2d6) Psychic damage.
  - name: Heavy Crossbow
    desc: |-
      *Ranged Attack Roll:* +4, range 100/400 ft. *Hit:* 6 (1d10 + 1) Piercing damage plus 7 (2d6) Psychic damage.
  - name: Enlarge (Recharge 5-6)
    desc: |-
      For 1 minute, the duergar becomes Large, gains advantage on Strength checks and Strength saving throws, and its War Pick attacks deal an extra 3 (1d6) damage. If there isn't enough room to become Large, it instead gains 10 temporary Hit Points.
  - name: Invisibility (Recharge 6)
    desc: |-
      The duergar magically has the Invisible condition until it attacks, casts Enlarge, or its Concentration ends.
bonus_actions:
  - name: Hook and Drag
    desc: |-
      After the duergar hits a creature with War Pick, the target must succeed on a DC 15 Strength saving throw or be pulled up to 10 feet straight toward the duergar.
habitat: "Underdark"
treasure: "Armamento enano, monedas de [[Calimba]], herramientas de captura"
```
