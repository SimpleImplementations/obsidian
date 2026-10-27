```statblock
layout: 5e 2024
columnWidth: 340
name: Druida Tier 1
type: NPC druida simple
subtype: D&D 5e
initiative: "+1"
ac: 14
hp: 28
speed: "30 ft."
stats: [10, 12, 14, 12, 16, 10]
saves:
  - constitution: 4
  - wisdom: 5
skillsaves:
  - medicina: 5
  - naturaleza: 3
  - percepción: 5
  - supervivencia: 5
senses: "Passive Perception 15"
traits:
  - name: Spellcasting
    desc: |-
      (WIS). Ataque de hechizo +5, CD de salvación 13.
  - name: PB
    desc: |-
      +2
actions:
  - name: Produce Flame
    desc: |-
      Ataque mágico a distancia: +5 al ataque, alcance 30 pies, 1 objetivo.
      Impacto: 7 (1d8 + 3) de fuego.
  - name: Thorn Whip
    desc: |-
      Ataque mágico cuerpo a cuerpo: +5 al ataque, alcance 30 pies, 1 objetivo.
      Impacto: 6 (1d6 + 3) perforante y puede arrastrar 10 pies al objetivo.
  - name: Entangle (2/día)
    desc: |-
      Área de 20 pies. Salvación de Fuerza CD 13.
      Quienes fallen quedan restrained hasta que escapen.
  - name: Moonbeam (1/día)
    desc: |-
      Radio de 5 pies, alcance 120 pies. Salvación de Constitución CD 13.
      Daño: 11 (2d10) radiante, o mitad si salva.
bonus_actions:
  - name: Healing Word (3/día)
    desc: |-
      Una criatura a 60 pies recupera 7 (1d4 + 5) HP.
```

Tema: soporte de naturaleza, curación chica y control simple.

HECHIZOS SIMPLES
- Cantrips: *druidcraft*, *guidance*, *produce flame*, *thorn whip*
- Nivel 1: *cure wounds*, *entangle*, *healing word*
- Nivel 2: *lesser restoration*, *moonbeam*, *pass without trace*

MODO DE USO PARA EL DM
1. Si un aliado cae -> *Healing Word*.
2. Si hay que frenar enemigos -> *Entangle*.
3. Si el enemigo es grande o importante -> *Moonbeam*.
4. Si no -> *Produce Flame* o *Thorn Whip*.
