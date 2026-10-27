---
tags:
  - character
  - stats
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Thassyr
size: Medium
type: humanoid
alignment: monk tier 2
initiative: "+4"
ac: 17
hp: 78
speed: "45 ft."
stats: [12, 18, 14, 10, 16, 10]
saves:
  - dexterity: 7
  - wisdom: 6
traits:
  - name: Evasión
    desc: |-
      Si falla una salvación de DEX a medias, igual no recibe daño. Si falla, recibe la mitad.
  - name: Disciplined Movement
    desc: |-
      Las oportunidades de ataque contra él tienen desventaja.
actions:
  - name: Acción principal — elegí una
    desc: ""
  - name: "Opción A: Multiattack"
    desc: |-
      Tres golpes. +7 al ataque, alcance 5 ft. Cada golpe: **1d10 + 4** de daño contundente.
  - name: "Opción B: Stunning Palm *(2/día)*"
    desc: |-
      Un golpe. +7 al ataque, alcance 5 ft. Daño: **1d10 + 4**.
      Si impacta → el objetivo tira **salvación de CON DC 15**. Si falla: queda **aturdido** hasta el fin del próximo turno de Thassyr.
bonus_actions:
  - name: "Flurry of Blows *(3/día)*"
    desc: |-
      Un golpe extra inmediatamente. +7 al ataque, **1d10 + 4** de daño.
reactions:
  - name: "Deflect Strike *(3/día)*"
    desc: |-
      Cuando recibe un golpe, reduce el daño en **15**.
```
