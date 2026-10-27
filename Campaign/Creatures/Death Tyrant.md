---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Death Tyrant
size: Large
type: Undead
alignment: Lawful Evil
initiative: "+2 (12)"
ac: 19
ac_class: natural armor
hp: 187
hit_dice: "25d10 + 50"
speed: "0 ft., Fly 20 ft. (hover)"
stats: [10, 14, 14, 19, 15, 19]
saves:
  - strength: 5
  - constitution: 7
  - intelligence: 9
  - wisdom: 7
  - charisma: 9
skillsaves:
  - perception: 12
damage_immunities: "Poison"
condition_immunities: "Charmed, Exhaustion, Paralyzed, Petrified, Poisoned, Prone"
senses: "Darkvision 120 ft., Passive Perception 22"
languages: "Deep Speech, Undercommon"
cr: "14"
cr_detail: "XP 11,500; CR 15 / XP 13,000 in lair; PB +5"
traits:
  - name: Negative Energy Cone
    desc: |-
      The death tyrant's central eye emits an invisible magical 150-foot cone of negative energy. At the start of each of its turns, the tyrant decides which way the cone faces and whether the cone is active.

      Creatures in the cone can't regain hit points. Any humanoid that dies there becomes a zombie under the tyrant's command. The zombie keeps its place in initiative and animates at the start of its next turn, provided the body hasn't been completely destroyed.
actions:
  - name: Bite
    desc: |-
      *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 14 (4d6) piercing damage.
  - name: Eye Rays
    desc: |-
      The death tyrant shoots three of the following magical eye rays at random, rerolling duplicates. It chooses one to three targets it can see within 120 feet:

      - **1: Charm Ray.** *Wisdom Saving Throw:* DC 17. *Failure:* The target is Charmed by the tyrant for 1 hour, or until the tyrant harms it.
      - **2: Paralyzing Ray.** *Constitution Saving Throw:* DC 17. *Failure:* The target is Paralyzed for 1 minute. It repeats the save at the end of each of its turns, ending the effect on a success.
      - **3: Fear Ray.** *Wisdom Saving Throw:* DC 17. *Failure:* The target is Frightened for 1 minute. It repeats the save at the end of each of its turns, ending the effect on a success.
      - **4: Slowing Ray.** *Dexterity Saving Throw:* DC 17. *Failure:* For 1 minute, the target's Speed is halved, it can't take Reactions, and it can take either an action or a Bonus Action on its turn, not both. It repeats the save at the end of each of its turns, ending the effect on a success.
      - **5: Enervation Ray.** *Constitution Saving Throw:* DC 17. *Failure:* 36 (8d8) necrotic damage. *Success:* Half damage.
      - **6: Telekinetic Ray.** *Strength Saving Throw:* DC 17. *Failure:* If the target is a creature, the tyrant moves it up to 30 feet in any direction. The target is Restrained until the start of the tyrant's next turn or until the tyrant is Incapacitated. If the target is an object weighing 300 pounds or less that isn't worn or carried, the tyrant moves it up to 30 feet and can manipulate it with fine control.
      - **7: Sleep Ray.** *Wisdom Saving Throw:* DC 17. *Failure:* The target is Unconscious for 1 minute. It wakes if it takes damage or another creature uses an action to wake it. This ray has no effect on Constructs or Undead.
      - **8: Petrification Ray.** *Dexterity Saving Throw:* DC 17. First Failure: The target is Restrained and repeats the save at the end of its next turn. Second Failure: The target is Petrified until freed by *greater restoration* or similar magic. Success ends the effect.
      - **9: Disintegration Ray.** *Dexterity Saving Throw:* DC 17. *Failure:* 45 (10d8) force damage. If this reduces a creature to 0 HP, its body becomes fine gray dust. A Large or smaller nonmagical object or creation of magical force is disintegrated automatically; a Huge or larger one loses a 10-foot cube.
      - **10: Death Ray.** *Dexterity Saving Throw:* DC 17. *Failure:* 55 (10d10) necrotic damage. The target dies if this damage reduces it to 0 HP.
legendary_description: |-
  Legendary Action Uses: 3.
legendary_actions:
  - name: Eye Ray
    desc: |-
      The death tyrant uses one random eye ray.
```

### Lair

A death tyrant's lair is usually the same site it held as a beholder, but with more trappings of death and decay.

- **Lair actions + efectos regionales**: [[Death Tyrant Lair]]
