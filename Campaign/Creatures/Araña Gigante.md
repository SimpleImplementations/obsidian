---
tags:
  - creature
---

La araña gigante tiene un cuerpo oscuro y peludo, con ocho patas largas y delgadas. Sus ojos brillan en rojo, mientras que sus colmillos venenosos sobresalen de una mandíbula retorcida.

```statblock
layout: 5e 2024
columnWidth: 340
name: Araña Gigante
size: Large
type: Beast
alignment: Unaligned
initiative: "+3 (13)"
ac: 14
hp: 26
hit_dice: "4d10 + 4"
speed: "30 ft., Climb 30 ft."
stats: [14, 16, 12, 2, 11, 4]
skillsaves:
  - perception: 4
  - stealth: 7
senses: "Darkvision 60 ft., Passive Perception 14"
languages: "None"
cr: "1"
cr_detail: "XP 200; PB +2"
traits:
  - name: Spider Climb
    desc: |-
      The spider can climb difficult surfaces, including along ceilings, without needing to make an ability check.
  - name: Web Walker
    desc: |-
      The spider ignores movement restrictions caused by webs, and it knows the location of any other creature in contact with the same web.
actions:
  - name: Bite
    desc: |-
      *Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing damage plus 7 (2d6) Poison damage.
  - name: Web (Recharge 5–6)
    desc: |-
      *Dexterity Saving Throw:* DC 13, one creature the spider can see within 60 feet. *Failure:* The target has the Restrained condition until the web is destroyed (AC 10; HP 5; Vulnerability to Fire damage; Immunity to Poison and Psychic damage).
```
