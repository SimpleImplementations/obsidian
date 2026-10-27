---
tags:
  - creature
---

*Elven archmage converted by Orren el Putrefacto*

```statblock
layout: 5e 2024
columnWidth: 340
name: Bone Seer of the Withered Glade (Ascendant)
size: Medium
type: Undead
alignment: Lawful Evil
initiative: "+3 (13)"
ac: 18
ac_class: natural armor, arcane ward
hp: 165
hit_dice: "22d8 + 66"
speed: "35 ft."
stats: [10, 16, 20, 20, 18, 14]
saves:
  - constitution: 10
  - intelligence: 10
  - wisdom: 9
skillsaves:
  - arcana: 10
  - perception: 9
  - stealth: 8
damage_vulnerabilities: "Bludgeoning"
damage_resistances: "Piercing, Necrotic"
damage_immunities: "Poison"
condition_immunities: "Exhaustion, Poisoned"
senses: "Darkvision 120 ft., Passive Perception 19"
languages: "Understands Elvish and Common but can't speak"
cr: "12"
cr_detail: "XP 8,400; PB +4"
traits:
  - name: Undead Spellweaver
    desc: |-
      Int is the spellcasting ability (save DC 18, +10 to hit). No verbal components.
  - name: Withered Majesty (Aura)
    desc: |-
      Enemies of the Bone Seer that start their turn within 15 ft. must succeed on a DC 18 Wisdom save or have disadvantage on attack rolls until the start of their next turn.
  - name: Grave-Bound Focus
    desc: |-
      Advantage on Constitution saves to maintain concentration.
  - name: Elven Fade
    desc: |-
      In dim light or darkness, the first attack against the Bone Seer each round is made at disadvantage.
  - name: Spellcasting
    desc: |-
      12th-level spellcaster.

      **At Will:** *chill touch*, *mage hand*, *minor illusion*, *detect magic*

      **3/Day Each:** *blight*, *counterspell*, *fear*

      **2/Day Each:** *blight*; *blinding smite* (necrotic); *summon undead*

      **1/Day Each:** *finger of death*
  - name: Blight Obsession
    desc: |-
      *Blight* can deal necrotic damage; undead allies in the area heal HP equal to half the damage dealt.
actions:
  - name: Grave Bolt
    desc: |-
      *Ranged Spell Attack:* +10 to hit, range 120 ft., one target. *Hit:* 22 (5d8) necrotic; target can't regain HP until the start of the Bone Seer's next turn.
  - name: Sovereign of Stillness (Recharge 5–6)
    desc: |-
      Creatures of choice within 30 ft. must succeed on a DC 18 Wisdom save or be restrained until the end of their next turn; on a success, speed is halved.
legendary_description: |-
  *Legendary Action Uses: 3. The Bone Seer can take one legendary action at a time, at the end of another creature's turn.*
legendary_actions:
  - name: Cantrip
    desc: |-
      Cast *chill touch*.
  - name: Fade Step
    desc: |-
      Teleport up to 20 ft. to dim light or darkness.
  - name: Grave Pulse (Costs 2)
    desc: |-
      Creatures of choice within 15 ft. take 10 (3d6) necrotic damage (DC 18 Constitution save for half).
lair_actions:
  - name: Lair Actions (Withered Glade)
    desc: |-
      On initiative count 20 (losing ties), one effect occurs:
  - name: Rooted Silence
    desc: |-
      A 20-ft. radius becomes difficult terrain until the next round; enemies have disadvantage on concentration saves.
  - name: Necrotic Bloom
    desc: |-
      A blighted tree erupts; enemies within 15 ft. take 14 (4d6) necrotic damage (DC 18 Constitution save for half).
  - name: Judgment of the Dead
    desc: |-
      One restrained or frightened creature takes 18 (4d8) necrotic damage.
```

[[Tree Blight]]
[[Vine Blight]]
