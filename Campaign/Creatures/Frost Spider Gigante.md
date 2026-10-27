---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Frost Spider Gigante
size: Gargantuan
type: Beast
subtype: Cold
alignment: Unaligned
initiative: "+2 (12)"
ac: 16
ac_class: armadura natural
hp: 136
hit_dice: "12d12 + 60"
speed: "40 ft., [[Climbing|Escalada]] 40 ft."
stats: [22, 14, 20, 4, 12, 4]
skillsaves:
  - "[[Perception]]": 4
  - "[[Stealth]]": 5
damage_immunities: "Frío"
senses: "[[Darkvision]] 60 ft., [[Passive Perception]] 14"
languages: "—"
cr: "7"
cr_detail: "PX 2.900; PB +3"
traits:
  - name: Escalada de araña
    desc: |-
      La araña puede escalar superficies difíciles, incluidos techos, sin necesidad de tirada.
  - name: Caminante de telaraña
    desc: |-
      La araña ignora las restricciones de movimiento por telarañas y conoce la ubicación de cualquier criatura en contacto con la misma tela.
  - name: Telaraña helada
    desc: |-
      Las telarañas de la araña están impregnadas de escarcha. Una criatura [[Restrained|restringida]] por su tela recibe 5 (1d10) de daño por frío al inicio de cada turno de la araña.
actions:
  - name: Multiataque
    desc: |-
      La araña hace dos ataques de Mordisco, o un Mordisco y un ataque de Telaraña.
  - name: Mordisco
    desc: |-
      *Ataque cuerpo a cuerpo:* +9 al ataque, alcance 3 m (10 ft.), un objetivo. *Impacto:* 13 (2d6 + 6) de daño perforante más 9 (2d8) de daño por frío. El objetivo debe superar una tirada de salvación de Constitución **DC 15** o queda **[[Paralyzed|paralizada]]** (congelada) hasta el final de su siguiente turno. Al final de cada uno de sus turnos, la criatura puede repetir la salvación para terminar el efecto.
  - name: Telaraña (Recarga 5-6)
    desc: |-
      *Tirada de salvación de Destreza DC 15,* una criatura que la araña pueda ver dentro de 18 m (60 ft.). *Fallar:* La criatura queda [[Restrained|restringida]] por la tela helada hasta que la liberen (CA 10; PG 10; vulnerabilidad al daño de fuego; inmunidad a veneno y psiónico). Mientras está restringida, recibe el daño por frío de Telaraña helada al inicio de cada turno de la araña.
habitat: "Pared de Hielo, túneles helados"
```
