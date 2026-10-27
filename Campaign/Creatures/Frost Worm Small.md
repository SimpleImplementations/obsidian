---
tags:
  - creature
---

```statblock
layout: 5e 2024
columnWidth: 340
name: Frost Worm Small
size: Huge
type: Monstrosity
subtype: Cold
alignment: Unaligned
initiative: "+0 (10)"
ac: 16
ac_class: armadura natural
hp: 153
hit_dice: "14d12 + 56"
speed: "35 ft., [[Burrow]] 30 ft. (hielo y nieve)"
stats: [22, 10, 18, 3, 10, 3]
skillsaves:
  - "[[Perception]]": 5
  - "[[Stealth]]": 4
damage_immunities: "Frío"
senses: "[[Tremorsense]] 60 ft. (solo a través de hielo o nieve), [[Blindsight]] 15 ft., [[Passive Perception]] 15"
languages: "—"
cr: "9"
cr_detail: "PX 5.000; PB +4"
traits:
  - name: Tremorsense en hielo
    desc: |-
      Mientras esté en contacto con hielo o nieve, detecta y ubica criaturas que se muevan o impacten el suelo en un radio de **60 ft.**, y percibe la forma aproximada del terreno.
  - name: Túneles de escarcha
    desc: |-
      Como el [[Frost Worm Large|adulto]], deja pasadizos estrechos al excavar; los túneles son menos estables y más propensos a derrumbarse si se combate dentro.
actions:
  - name: Succión de hielo
    desc: |-
      *Ataque cuerpo a cuerpo:* +10 al ataque, alcance 3 m (10 ft.), un objetivo. *Impacto:* **30 (8d6)** de daño por frío (vórtice helado que deshidrata y quema la piel). Si el objetivo es Mediano o más pequeño, debe superar una salvación de Fuerza **DC 10** o quedar **[[Grappled|agarrado]]** en la boca del gusano, arrastrado por la succión. Una criatura agarrada así queda [[Restrained|restringida]], tiene **desventaja** en la salvación para escapar, y queda sujeta a **congelación visceral**.
  - name: Congelación visceral (solo criatura agarrada con Succión de hielo)
    desc: |-
      Al **inicio de cada turno** del frost worm, cada criatura agarrada por *Succión de hielo* **siempre** sufre **8 (2d8)** de daño por frío. Luego hace una salvación de Constitución **DC 10**; si **falla**, suma **1 contador de escarcha**. Si llega a **3 contadores** y **todavía está agarrada**, **muere al instante** (**Nivel III** en [[Congelación parcial (Frost Worm)]]). **Al dejar de estar agarrada**, aplica **Nivel I o II** según contadores en esa misma nota.

      Para **soltarse**: **acción**, salvación de Fuerza **DC 10**. Si el gusano recibe **17 o más puntos de daño por fuego** en un solo turno mientras tiene una criatura agarrada, suelta; esa criatura cae **[[Prone|tumbada]]** a 1,5 m (5 ft.). **O** si la criatura agarrada inflige **17 o más puntos** en un solo turno con un arma cuerpo a cuerpo desde la boca, el gusano la escupe (misma caída).
  - name: Aliento de escarcha (Recarga 6)
    desc: |-
      Cono de 9 m (30 ft.). Constitución **DC 10**; **27 (6d8)** de daño por frío y velocidad 0 hasta el fin del siguiente turno del gusano si falla; mitad de daño y sin reducción de velocidad si supera.
habitat: "Grietas, túneles superficiales, capas de nieve bajo la pared de hielo"
treasure: "—"
```

### Descripción

Un **frost worm** joven o subadulto: el mismo hambre helado que el [[Frost Worm Large]], pero sin la presencia que paraliza de su pariente. **Succiona** presas con un túnel de aire gélido antes de atraparlas entre los anillos de la boca; suele emboscar desde grietas en lugar de partir el suelo bajo caravanas enteras.
