```statblock
layout: 5e 2024
columnWidth: 340
name: Orren el putrefacto
size: Medium
type: Undead
subtype: Wizard
alignment: Neutral Evil
initiative: "+17"
ac: 20
hp: 315
speed: "30 ft."
stats: [11, 16, 16, 21, 14, 16]
saves:
  - dexterity: 10
  - constitution: 10
  - intelligence: 12
  - wisdom: 9
skillsaves:
  - arcana: 19
  - history: 12
  - insight: 9
  - perception: 9
damage_resistances: "Cold, Lightning"
damage_immunities: "Necrotic, Poison"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Poisoned"
senses: "Truesight 120 ft., Passive Perception 19"
languages: "All"
traits:
  - name: PB
    desc: |-
      +7
  - name: Spellcasting
    desc: |-
      (INT). Spell attack +12, save DC 20.
  - name: Legendary Resistance (4/day)
    desc: |-
      Si Orren falla una tirada de salvacion, puede elegir superarla.
  - name: Reliquias de Karr
    desc: |-
      Si Orren es destruido pero sus reliquias siguen intactas, reformara su cuerpo en 1d10 dias en su altar.
actions:
  - name: Multiattack
    desc: |-
      Hace tres ataques, usando *Eldritch Burst* o *Paralyzing Touch* en cualquier combinacion.
  - name: Eldritch Burst
    desc: |-
      Ataque cuerpo a cuerpo o a distancia: +12 al impacto, alcance 5 ft. o 120 ft.
      Impacto: 31 (4d12 + 5) de force.
  - name: Paralyzing Touch
    desc: |-
      Ataque cuerpo a cuerpo: +12 al impacto, alcance 5 ft.
      Impacto: 15 (3d6 + 5) de cold, y el objetivo queda paralizado hasta el comienzo del siguiente turno de Orren.
  - name: Spellcasting
    desc: |-
      **At will:** *Detect Magic*, *Detect Thoughts*, *Dispel Magic*, *Fireball* (nivel 5), *Invisibility*, *Lightning Bolt* (nivel 5), *Mage Hand*, *Prestidigitation*

      **2/day c/u:** *Animate Dead*, *Dimension Door*, *Plane Shift*

      **1/day c/u:** *Chain Lightning*, *Finger of Death*, *Power Word Kill*, *Scrying*
reactions:
  - name: Protective Magic
    desc: |-
      Orren castea *Counterspell* o *Shield* en respuesta al disparador.
legendary_actions:
  - name: Deathly Teleport
    desc: |-
      Orren se teletransporta hasta 60 ft.; cada criatura a 10 ft. del espacio que dejo recibe 11 (2d10) de necrotic.
  - name: Disrupt Life
    desc: |-
      Salvacion de CON CD 20 para cada criatura no-muerta en una emanacion de 20 ft.
      Fallo: 31 (9d6) de necrotic. Exito: mitad.
  - name: Frightening Gaze
    desc: |-
      Orren castea *Fear*.
```

Base: [[Lich]]
