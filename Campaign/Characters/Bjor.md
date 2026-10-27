Druida orco de la [[Orden del Círculo de la nieve]]. Poco tacto; lealtad inquebrantable al círculo.  

```statblock
layout: 5e 2024
columnWidth: 340
name: Bjor
size: Large
type: humanoid
subtype: orc
alignment: neutral primal
ac: 14
ac_class: hide armor
hp: 95
hit_dice: "10d8 + 40"
speed: "30 ft."
stats: [16, 12, 16, 10, 18, 8]
saves:
  - wisdom: 8
  - constitution: 7
skillsaves:
  - perception: 8
  - survival: 8
senses: "darkvision 60 ft., passive Perception 18"
languages: "Common, Orc, Druidic"
cr: "~8"
cr_detail: "3,900 XP"
traits:
  - name: Beast-Focused Druid
    desc: |-
      Bjor has 3 uses of Wild Shape per day. He almost always fights in beast form.
  - name: Barkskin Ritual
    desc: |-
      If given 1 round before combat, Bjor casts *barkskin* (AC 16) before Wild Shaping.
  - name: Primal Resilience
    desc: |-
      When a Wild Shape drops to 0 HP, Bjor reverts with remaining damage and can Wild Shape again as a bonus action.
actions:
  - name: Quarterstaff
    desc: |-
      *Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. Hit: 7 (1d8 + 3) bludgeoning.
  - name: Healing Word (3/day)
    desc: |-
      Bonus action; a creature within 60 ft. regains 8 (1d4 + 4) HP.
  - name: Wild Shape
    desc: |-
      Bonus action to transform into a beast (see below).
```

## 🐻 **Wild Shape: Giant Dire Bear**

```statblock
layout: 5e 2024
columnWidth: 340
name: Giant Dire Bear
size: Huge
type: beast
ac: 14
hp: 110
speed: "40 ft., climb 30 ft."
traits:
  - name: Relentless Rage (1/day)
    desc: |-
      When reduced to 0 HP, drops to 1 HP instead.
actions:
  - name: Multiattack
    desc: |-
      One bite and one claw.
  - name: Bite
    desc: |-
      *Melee:* +8 to hit, 14 (2d8 + 5) piercing.
  - name: Claw
    desc: |-
      *Melee:* +8 to hit, 12 (2d6 + 5) slashing.
```

## 🐗 **Wild Shape: Giant Dire Boar**

```statblock
layout: 5e 2024
columnWidth: 340
name: Giant Dire Boar
size: Large
type: beast
ac: 13
hp: 95
speed: "40 ft."
traits:
  - name: Relentless
    desc: |-
      When reduced to 0 HP, drops to 1 HP instead.
actions:
  - name: Charge
    desc: |-
      If the boar moves 20 ft. straight and hits:
  - name: Gore
    desc: |-
      *Melee:* +7 to hit, 15 (2d10 + 4) piercing; DC 15 STR save or target is knocked prone.
```

## 🦍 **Wild Shape: Giant Ape**

```statblock
layout: 5e 2024
columnWidth: 340
name: Giant Ape
size: Huge
type: beast
ac: 12
hp: 100
speed: "40 ft., climb 40 ft."
actions:
  - name: Multiattack
    desc: |-
      Two fists.
  - name: Fist
    desc: |-
      *Melee:* +9 to hit, 22 (3d10 + 6) bludgeoning.
  - name: Rock
    desc: |-
      *Ranged:* +9 to hit, range 50/100 ft., 22 (3d10 + 6) bludgeoning.
```

### **Tactics**
Bjor opens with **Barkskin → Wild Shape**, then commits to **one form at a time**, using only basic attacks.  
He retreats only if forced out of Wild Shape twice.

### **Description**
Bjor believes beasts are the purest expression of the land's will. Civilization is weakness; tooth, tusk, and claw are truth. When he fights, he abandons speech entirely and lets the wild speak for him.
