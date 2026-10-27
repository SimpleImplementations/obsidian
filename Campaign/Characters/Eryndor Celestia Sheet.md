```statblock
layout: 5e 2024
columnWidth: 340
name: Eryndor Celestia
type: "NPC, druida de alto nivel del hielo (D&D 5e)"
initiative: "+2"
ac: 17
hp: 132
speed: "30 ft."
stats: [10, 14, 18, 14, 22, 16]
saves:
  - constitution: 9
  - wisdom: 11
skillsaves:
  - Medicina: 11
  - Naturaleza: 7
  - Percepción: 11
  - Perspicacia: 11
damage_resistances: "frío"
senses: "Passive Perception 21"
traits:
  - name: Spellcasting
    desc: |-
      (WIS). Ataque de hechizo +11, CD de salvación 19.
  - name: PB
    desc: |-
      +5
  - name: Custodio de la Nieve
    desc: |-
      Mientras esté sobre nieve, hielo, tierra natural o bosque, tiene ventaja en salvaciones de Constitución para mantener concentración.
  - name: Resistencia legendaria (2/día)
    desc: |-
      Si falla una tirada de salvación, puede elegir superarla.
  - name: Aura de invierno
    desc: |-
      El terreno a 15 pies de Eryndor es terreno difícil para enemigos. Aliados de su elección ignoran este efecto.
  - name: Forma salvaje superior (3/día)
    desc: |-
      Acción bonus. Se transforma en una de las formas de abajo. Al llegar a 0 HP en forma animal, vuelve a Eryndor con los HP que tenía antes de transformarse.
actions:
  - name: Rayo de escarcha antigua
    desc: |-
      Ataque mágico a distancia: +11 al ataque, alcance 120 pies, 1 objetivo.
      Impacto: 28 (4d10 + 6) de daño de frío y la velocidad del objetivo baja 10 pies hasta el inicio del próximo turno de Eryndor.
  - name: Tormenta del Círculo (Recarga 5-6)
    desc: |-
      Esfera de 20 pies de radio a 120 pies.
      Salvación de Constitución CD 19.
      Daño: 36 (8d8) de frío, o la mitad con salvación exitosa.
      Quienes fallen quedan con velocidad reducida a la mitad hasta el final de su próximo turno.
  - name: Raíces bajo la nieve (3/día)
    desc: |-
      Punto a 90 pies; radio de 20 pies.
      Salvación de Fuerza CD 19.
      Quienes fallen quedan restrained hasta el final de su próximo turno.
  - name: Curación mayor (2/día)
    desc: |-
      Una criatura que vea a 60 pies recupera 45 HP.
bonus_actions:
  - name: Forma salvaje superior (3/día)
    desc: |-
      Se transforma en escorpión gigante, gorila de la nieve o águila blanca.
  - name: Paso de ventisca (3/día)
    desc: |-
      Se teletransporta hasta 30 pies a un espacio que vea. Deja una ráfaga de nieve; los ataques de oportunidad contra él tienen desventaja hasta el final del turno.
reactions:
  - name: Corteza de hielo (3/día)
    desc: |-
      Cuando él o un aliado a 30 pies recibe daño, reduce ese daño en 20.
```

Tema: druida del hielo y líder sereno; pelea sobre todo transformándose. Los hechizos son respaldo para curar, controlar terreno o resolver una escena.

HECHIZOS SIMPLES
- Cantrips: *druidcraft*, *frostbite*, *guidance*, *thorn whip*
- Nivel 1: *absorb elements*, *cure wounds*, *ice knife*
- Nivel 2: *lesser restoration*, *moonbeam*, *pass without trace*
- Nivel 3: *dispel magic*, *sleet storm*
- Nivel 4: *freedom of movement*, *ice storm*
- Nivel 5: *cone of cold*, *greater restoration*
- Nivel 6: *heal*, *wall of thorns*
- Nivel 7: *regenerate*, *fire storm* (describir como tormenta de luz helada si querés mantener estética)

FORMAS SALVAJES

```statblock
layout: 5e 2024
columnWidth: 340
name: Escorpión gigante de hielo
size: Large
type: beast
ac: 17
hp: 115
speed: "40 ft."
actions:
  - name: Multiattack
    desc: |-
      Hace 2 pinzas y 1 aguijón.
  - name: Pinza
    desc: |-
      Ataque cuerpo a cuerpo: +10 al ataque, alcance 10 pies, 1 objetivo.
      Impacto: 16 (2d10 + 5) contundente. Si impacta, el objetivo queda grappled (escape CD 18).
  - name: Aguijón helado
    desc: |-
      Ataque cuerpo a cuerpo: +10 al ataque, alcance 10 pies, 1 objetivo.
      Impacto: 18 (3d8 + 5) perforante + 18 (4d8) frío.
```

Uso simple: forma para trabar enemigos fuertes o bloquear un pasillo.

```statblock
layout: 5e 2024
columnWidth: 340
name: Gorila de la nieve
size: Huge
type: beast
ac: 16
hp: 135
speed: "40 ft., climb 40 ft."
actions:
  - name: Multiattack
    desc: |-
      Hace 2 puñetazos.
  - name: Puñetazo
    desc: |-
      Ataque cuerpo a cuerpo: +11 al ataque, alcance 10 pies, 1 objetivo.
      Impacto: 24 (3d10 + 8) contundente.
  - name: Roca de hielo
    desc: |-
      Ataque a distancia: +11 al ataque, alcance 60/120 pies, 1 objetivo.
      Impacto: 26 (4d8 + 8) contundente/frío.
  - name: Rugido blanco (Recarga 5-6)
    desc: |-
      Criaturas enemigas a 15 pies hacen salvación de Fuerza CD 19.
      Si fallan, reciben 18 (4d8) frío y caen prone. Si salvan, mitad de daño y no caen.
```

Uso simple: forma principal para pelear y aguantar daño.

```statblock
layout: 5e 2024
columnWidth: 340
name: Águila blanca del norte
size: Large
type: beast
ac: 16
hp: 90
speed: "20 ft., fly 90 ft."
actions:
  - name: Multiattack
    desc: |-
      Hace 1 pico y 1 garra.
  - name: Pico
    desc: |-
      Ataque cuerpo a cuerpo: +10 al ataque, alcance 5 pies, 1 objetivo.
      Impacto: 17 (2d10 + 6) perforante.
  - name: Garras
    desc: |-
      Ataque cuerpo a cuerpo: +10 al ataque, alcance 5 pies, 1 objetivo.
      Impacto: 20 (4d6 + 6) cortante.
  - name: Tomar y soltar
    desc: |-
      Si impacta con garras a una criatura Medium o menor, puede moverla 20 pies con él sin provocar ataques de oportunidad.
```

Uso simple: forma para moverse, rescatar aliados, perseguir o escapar.

MODO DE USO PARA EL DM
Turno normal:
1. Si tiene que pelear de frente -> Gorila de la nieve.
2. Si tiene que trabar un enemigo o bloquear paso -> Escorpión gigante de hielo.
3. Si tiene que moverse, rescatar o perseguir -> Águila blanca del norte.
4. Si un aliado cae o está muy herido -> vuelve a forma élfica y usa Curación mayor o *heal*.
5. Guardá Corteza de hielo para golpes grandes, no para daño chico.

MODO JEFE / ALIADO PODEROSO
- Ronda 1: Forma salvaje según la escena.
- Ronda 2: Ataques básicos de la forma; no pienses de más.
- Ronda 3: Si la forma está funcionando, seguí. Si el grupo necesita ayuda, vuelve y cura/controla.
