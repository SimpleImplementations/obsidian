---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Troll convertido
size: Large
type: Giant
alignment: Chaotic Evil
initiative: "+2 (12)"
ac: 16
hp: 136
hit_dice: "13d10 + 65"
speed: "30 ft."
stats: [20, 14, 20, 7, 10, 7]
skillsaves:
  - "[[Perception]]": 6
senses: "[[Darkvision]] 60 ft.; [[Passive Perception]] 16"
languages: "Giant"
cr: "7"
cr_detail: "XP 2,900; PB +3"
traits:
  - name: Death-Fed Regeneration
    desc: |-
      When a creature dies within 30 feet of the troll, the troll regains 22 (4d10) Hit Points. This can happen any number of times per round. This healing is not prevented by Acid or Fire damage (unlike the troll's Regeneration trait).
  - name: Deathless Tenacity
    desc: |-
      If the troll is reduced to 0 Hit Points by damage that isn't Acid or Fire, it doesn't die permanently. After 10 minutes, it revives with 1 Hit Point and its Regeneration functions normally again. If the troll was reduced to 0 Hit Points by Acid or Fire damage, it dies permanently and doesn't revive.
  - name: Regeneration
    desc: |-
      The troll regains 20 Hit Points at the start of each of its turns. If the troll takes Acid or Fire damage, this trait doesn't function on the troll's next turn. The troll dies only if it starts its turn with 0 Hit Points and doesn't regenerate.
actions:
  - name: Multiattack
    desc: |-
      The troll makes three Rend attacks.
  - name: Rend
    desc: |-
      *Melee Attack Roll:* +8, reach 10 ft. *Hit:* 13 (2d6 + 5) Slashing damage.
bonus_actions:
  - name: Charge
    desc: |-
      The troll moves up to half its Speed straight toward an enemy it can see.
```

Variante más fuerte del [[Troll]] base: se fortalece con la muerte de criaturas cercanas y tiene resistencia tipo no-muerto (Deathless Tenacity).
