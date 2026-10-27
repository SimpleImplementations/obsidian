```statblock
layout: 5e 2024
columnWidth: 340
name: Askadar (Phase 1)
size: Gargantuan
type: Dragon
subtype: Chromatic
alignment: Chaotic Evil
initiative: "+16 (26)"
ac: 22
hp: 300
speed: "40 ft., Fly 320 ft., Swim 40 ft."
stats: [27, 14, 25, 16, 15, 22]
saves:
  - dexterity: 9
  - wisdom: 9
skillsaves:
  - perception: 16
  - stealth: 9
damage_immunities: "Acid, Necrotic, Poison"
senses: "Blindsight 60 ft., Darkvision 120 ft., Passive Perception 26"
languages: "Common, Draconic"
cr: "21"
cr_detail: "XP 33 000, or 41 000 in Lair; PB +7"
traits:
  - name: Amphibious
    desc: |-
      The dragon can breathe air and water.
  - name: Legendary Resistance (4/Day, or 5/Day in Lair)
    desc: |-
      If the dragon fails a saving throw, it can choose to succeed instead.
actions:
  - name: Multiattack
    desc: |-
      The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast *[Melf's Acid Arrow](https://www.aidedd.org/spell/melfs-acid-arrow)* (level 4 version).
  - name: Rend
    desc: |-
      *Melee Attack Roll:* +15, reach 15 ft. *Hit:* 17 (2d8 + 8) Slashing damage plus 9 (2d8) Acid damage.
  - name: Acid Breath (Recharge 5–6)
    desc: |-
      *Dexterity Saving Throw:* DC 22, each creature in a 90-foot-long, 10-foot-wide Line. *Failure:* 67 (15d8) Acid damage. *Success:* Half damage.
  - name: Spellcasting
    desc: |-
      The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21, +13 to hit with spell attacks):

      - At Will: *[Detect Magic](https://www.aidedd.org/spell/detect-magic), [Fear](https://www.aidedd.org/spell/fear), [Melf's Acid Arrow](https://www.aidedd.org/spell/melfs-acid-arrow)* (level 4 version)
      - 1/Day Each: *[Create Undead](https://www.aidedd.org/spell/create-undead), [Speak with Dead](https://www.aidedd.org/spell/speak-with-dead), [Vitriolic Sphere](https://www.aidedd.org/spell/vitriolic-sphere)* (level 5 version)
legendary_description: |-
  Legendary Action Uses: 3 (4 in Lair). Immediately after another creature's turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.
legendary_actions:
  - name: Cloud of Insects
    desc: |-
      *Dexterity Saving Throw:* DC 21, one creature the dragon can see within 120 feet. *Failure:* 33 (6d10) Poison damage, and the target has Disadvantage on saving throws to maintain Concentration until the end of its next turn. *Failure or Success:* The dragon can't take this action again until the start of its next turn.
  - name: Frightful Presence
    desc: |-
      The dragon uses Spellcasting to cast *[Fear](https://www.aidedd.org/spell/fear)*. The dragon can't take this action again until the start of its next turn.
  - name: Pounce
    desc: |-
      The dragon moves up to half its Speed, and it makes one Rend attack.
```
