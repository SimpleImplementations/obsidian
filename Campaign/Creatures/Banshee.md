---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Banshee
size: Medium
type: Undead
alignment: Chaotic Evil
initiative: "+2 (12)"
ac: 12
hp: 54
hit_dice: "12d8"
speed: "5 ft., Fly 40 ft. (hover)"
stats: [1, 14, 10, 12, 11, 17]
damage_resistances: "Acid, Bludgeoning, Fire, Lightning, Piercing, Slashing, Thunder"
damage_immunities: "Cold, Necrotic, Poison"
condition_immunities: "Charmed, Exhaustion, Frightened, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained"
senses: "Darkvision 60 ft., Passive Perception 10"
languages: "Common, Elvish"
cr: "4"
cr_detail: "XP 1,100; PB +2"
traits:
  - name: Detect Life
    desc: |-
      The banshee magically senses the direction of creatures up to 1 mile away that aren't Constructs or Undead.
  - name: Incorporeal Movement
    desc: |-
      The banshee can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.
actions:
  - name: Multiattack
    desc: |-
      The banshee makes two Corrupting Touch attacks and uses Horrify.
  - name: Corrupting Touch
    desc: |-
      *Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Necrotic damage.
  - name: Horrify
    desc: |-
      *Wisdom Saving Throw:* DC 13, one creature the banshee can see within 60 feet that can see the banshee. *Failure:* The target has the Frightened condition until the start of the banshee's next turn. *Success:* The target is immune to this banshee's Horrifying Visage for 24 hours.
  - name: Deathly Wail (1/Day)
    desc: |-
      The banshee releases a mournful wail if it isn't in sunlight. *Constitution Saving Throw:* DC 13, each creature within 30 feet that can hear the wail and isn't a Construct or an Undead. *Failure:* If the target has 25 Hit Points or fewer, it drops to 0 Hit Points. Otherwise, the target takes 10 (3d6) Psychic damage.
```
