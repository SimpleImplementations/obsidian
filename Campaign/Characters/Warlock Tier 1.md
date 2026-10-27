```statblock
layout: 5e 2024
columnWidth: 340
name: Warlock Tier 1
type: NPC brujo simple
subtype: D&D 5e
initiative: "+2"
ac: 14
hp: 30
speed: "30 ft."
stats: [10, 14, 14, 12, 12, 16]
saves:
  - wisdom: 3
  - charisma: 5
skillsaves:
  - arcana: 3
  - deception: 5
  - intimidation: 5
senses: "Passive Perception 11"
traits:
  - name: Spellcasting
    desc: |-
      (CHA). Ataque de hechizo +5, CD de salvación 13.
  - name: PB
    desc: |-
      +2
actions:
  - name: Eldritch Blast
    desc: |-
      Ataque mágico a distancia: +5 al ataque, alcance 120 pies, 1 objetivo.
      Impacto: 9 (1d10 + 3) de fuerza.
  - name: Pact Dagger
    desc: |-
      Ataque cuerpo a cuerpo o a distancia: +5 al ataque, alcance 5 pies o 20/60 pies, 1 objetivo.
      Impacto: 6 (1d6 + 3) perforante.
  - name: "*Hold Person* (1/día)"
    desc: |-
      Humanoide a 60 pies. Salvación de Sabiduría CD 13.
      Si falla, queda paralyzed hasta el final de su próximo turno.
bonus_actions:
  - name: "*Hex* (2/día)"
    desc: |-
      Marca una criatura a 90 pies. Los ataques del brujo contra ella hacen +3 (1d6) necrótico.
  - name: "*Misty Step* (1/día)"
    desc: |-
      Se teletransporta hasta 30 pies a un espacio que vea.
reactions:
  - name: "*Hellish Rebuke* (2/día)"
    desc: |-
      Cuando una criatura lo daña a 60 pies, salvación de Destreza CD 13.
      Daño: 11 (2d10) de fuego, o mitad si salva.
```

Tema: brujo simple de patrón oscuro; buen daño a distancia y control raro.

HECHIZOS SIMPLES
- Cantrips: *eldritch blast*, *mage hand*, *minor illusion*
- Nivel 1: *armor of Agathys*, *hex*, *hellish rebuke*
- Nivel 2: *hold person*, *misty step*

MODO DE USO PARA EL DM
1. Si el combate recién empieza -> *Hex* al objetivo principal.
2. Si el objetivo es humanoide peligroso -> *Hold Person*.
3. Si está lejos -> *Eldritch Blast*.
4. Si lo dañan fuerte -> *Hellish Rebuke*.
5. Si lo traban -> *Misty Step*.
