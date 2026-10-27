---
tags:
  - creature
aliases:
  - Frost Worm
---

[[Frost Worm.png]]

```statblock
layout: 5e 2024
columnWidth: 340
name: Frost Worm Large
size: Gargantuan
type: Monstrosity
subtype: Cold
alignment: Unaligned
initiative: "-1 (8)"
ac: 18
ac_class: armadura natural
hp: 297
hit_dice: "18d20 + 126"
speed: "40 ft., [[Burrow]] 40 ft. (hielo y nieve)"
stats: [28, 8, 22, 4, 12, 4]
skillsaves:
  - "[[Perception]]": 7
  - "[[Stealth]]": 3
damage_immunities: "Frío"
senses: "[[Tremorsense]] 120 ft. (solo a través de hielo o nieve), [[Blindsight]] 30 ft., [[Passive Perception]] 17"
languages: "—"
cr: "20"
cr_detail: "PX 25.000; PB +6"
traits:
  - name: Tremorsense en hielo
    desc: |-
      Mientras esté en contacto con hielo o nieve, el frost worm puede detectar y ubicar criaturas que se muevan o impacten el suelo en un radio de 120 ft., y puede sentir la forma aproximada del terreno.
  - name: Túneles de escarcha
    desc: |-
      Al excavar, deja túneles estables de hielo y nieve compactada que pueden usarse como pasadizos (o trampas) tras su paso.
  - name: Presencia abisal (miedo)
    desc: |-
      Una criatura hostil que **inicie su turno** a **4,5 m (15 ft.)** o menos del frost worm debe superar una salvación de Sabiduría **DC 18** o tener la condición **[[Frightened|Asustada]]** hasta el inicio de su siguiente turno. Si supera la salvación, es **inmune** a este efecto durante **24 horas**.
actions:
  - name: Succión de hielo
    desc: |-
      *Ataque cuerpo a cuerpo:* +15 al ataque, alcance 4,5 m (15 ft.), un objetivo. *Impacto:* **48 (8d10)** de daño por frío (escarcha y vacío que arrea la piel y los pulmones). Si el objetivo es Grande o más pequeño, debe superar una salvación de Fuerza **DC 20** o quedar **[[Grappled|agarrado]]** en la boca del gusano, arrastrado por la succión. Una criatura agarrada así queda [[Restrained|restringida]], tiene **desventaja** en la salvación para escapar, y queda sujeta a **congelación visceral** (ver más abajo).
  - name: Congelación visceral (solo criatura agarrada con Succión de hielo)
    desc: |-
      Al **inicio de cada turno** del frost worm, cada criatura agarrada por *Succión de hielo* **siempre** sufre **16 (3d10)** de daño por frío. Luego hace una salvación de Constitución **DC 20**; si **falla**, suma **1 contador de escarcha** (siguen acumulándose mientras siga agarrada). Si llega a **3 contadores** y **todavía está agarrada**, **muere al instante** (**Nivel III** en [[Congelación parcial (Frost Worm)]]). **Al dejar de estar agarrada**, aplica **Nivel I o II** según contadores en esa misma nota.

      Para **soltarse**, la criatura agarrada usa la **acción** para una salvación de Fuerza **DC 20**. **Además**, el gusano suelta de golpe a una criatura agarrada si en un solo turno recibe **20 o más puntos de daño por fuego** (de cualquier fuente); esa criatura cae **[[Prone|tumbada]]** en un espacio libre a 3 m (10 ft.). **O bien** si la criatura agarrada inflige **25 o más puntos de daño** en un solo turno con un arma cuerpo a cuerpo mientras está en la boca, el gusano la escupe igual (tumbada, a 3 m).
  - name: Aliento de escarcha (Recarga 5-6)
    desc: |-
      El frost worm exhala un cono de viento helado de 18 m (60 ft.). Cada criatura en esa zona debe superar una tirada de salvación de Constitución **DC 20**; si falla, recibe 45 (10d8) de daño por frío y su velocidad se reduce a 0 hasta el final de su siguiente turno; si supera, recibe la mitad del daño y no sufre la reducción de velocidad.
habitat: "Tundra, glaciares, capas de hielo y nieve profunda"
treasure: "—"
```

### Descripción

El **frost worm** grande es el titán del norte: un gusano de escarcha que no caza en superficie sino que vive bajo la tundra y el hielo eterno. Como los gusanos de arena del desierto, percibe las vibraciones de lo que pisa el suelo; cuando algo lo suficiente grande —o lo suficiente ruidoso— cruza su dominio, surge. Su boca es un abismo de hielo y dientes; el impacto de su cuerpo contra el suelo puede sepultar caravanas y abrir grietas en el permafrost. Los clanes del norte no lo cazan: lo evitan, trazan rutas donde el hielo es demasiado delgado para que se acerque, o cuentan leyendas de tribus que lo aplacaban con ofrendas. En combate **aspira** presas con un torbellino helado que las pega a la boca; el frío **desmenuza** antes que digerir.
