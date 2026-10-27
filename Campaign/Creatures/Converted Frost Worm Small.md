---
tags:
  - creature
---

*Frost worm joven convertido en no-muerto por [[Orren el putrefacto]].*

```statblock
layout: 5e 2024
columnWidth: 340
name: Converted Frost Worm Small
size: Huge
type: Undead
alignment: Lawful Evil
initiative: "+0 (10)"
ac: 17
ac_class: natural armor
hp: 170
hit_dice: "20d12 + 40"
speed: "35 ft., [[Burrow]] 30 ft. (hielo, nieve y hueso)"
stats: [22, 10, 20, 3, 10, 3]
saves:
  - strength: 10
  - constitution: 9
  - wisdom: 4
skillsaves:
  - perception: 6
  - stealth: 4
damage_vulnerabilities: "Bludgeoning"
damage_resistances: "Piercing, Slashing, Necrotic"
damage_immunities: "Cold, Poison"
condition_immunities: "Exhaustion, Poisoned"
senses: "[[Tremorsense]] 60 ft. (solo a través de hielo, nieve o hueso), [[Blindsight]] 15 ft., Passive Perception 16"
languages: "—"
cr: "10"
cr_detail: "XP 5,900; PB +4"
traits:
  - name: Undead Fortitude
    desc: |-
      If the frost worm is reduced to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant, fire, or from a critical hit. On a success, the worm drops to 1 hit point instead.
  - name: Tremorsense en hielo y hueso
    desc: |-
      Mientras esté en contacto con hielo, nieve o restos óseos, detecta y ubica criaturas que se muevan o impacten el suelo en un radio de **60 ft.**, y percibe la forma aproximada del terreno.
  - name: Túneles de hueso helado
    desc: |-
      Deja pasadizos estrechos al excavar. Los túneles son inestables; si una criatura dentro recibe 20 o más de daño contundente, de trueno o de fuego en un turno, el túnel puede derrumbarse a criterio del DM.
  - name: Death-Cold Hunger
    desc: |-
      Una criatura agarrada por la Succión de hielo no puede recuperar HP.
actions:
  - name: Succión de hielo
    desc: |-
      *Ataque cuerpo a cuerpo:* +10 al ataque, alcance 10 ft., un objetivo. *Impacto:* **34 (8d6 + 6)** de daño por frío/necrótico. Si el objetivo es Mediano o más pequeño, debe superar una salvación de Fuerza **DC 14** o quedar **[[Grappled|agarrado]]** en la boca del gusano, arrastrado por la succión. Una criatura agarrada así queda [[Restrained|restringida]], tiene **desventaja** en la salvación para escapar, y queda sujeta a **congelación visceral**.
  - name: Congelación visceral (solo criatura agarrada con Succión de hielo)
    desc: |-
      Al **inicio de cada turno** del frost worm, cada criatura agarrada por *Succión de hielo* sufre **13 (3d8)** de daño por frío/necrótico. Luego hace una salvación de Constitución **DC 14**; si **falla**, suma **1 contador de escarcha**. Si llega a **3 contadores** y **todavía está agarrada**, **muere al instante** (**Nivel III** en [[Congelación parcial (Frost Worm)]]). **Al dejar de estar agarrada**, aplica **Nivel I o II** según contadores en esa misma nota.

      Para **soltarse**: **acción**, salvación de Fuerza **DC 14**. Si el gusano recibe **20 o más puntos de daño por fuego o radiante** en un solo turno mientras tiene una criatura agarrada, suelta; esa criatura cae **[[Prone|tumbada]]** a 5 ft. **O** si la criatura agarrada inflige **20 o más puntos** en un solo turno con un arma cuerpo a cuerpo desde la boca, el gusano la escupe (misma caída).
  - name: Aliento de escarcha muerta (Recarga 6)
    desc: |-
      Cono de 30 ft. Constitución **DC 14**; **36 (8d8)** de daño por frío/necrótico y velocidad 0 hasta el fin del siguiente turno del gusano si falla; mitad de daño y sin reducción de velocidad si supera.
bonus_actions:
  - name: Bone-Burrow Shift (Recharge 5-6)
    desc: |-
      El frost worm excava hasta 15 ft. sin provocar ataques de oportunidad. Si emerge junto a una criatura, tiene ventaja en su próxima *Succión de hielo* este turno.
habitat: "Grietas, túneles superficiales, capas de nieve bajo la pared de hielo, fosas con restos óseos"
treasure: "—"
```

### Descripción

Un [[Frost Worm Small]] reanimado por magia necrótica. Sus placas de hielo están rajadas por costillas expuestas, su boca parece un anillo de hueso congelado y sus túneles quedan sembrados de fragmentos blancos que crujen como dientes bajo la nieve.
