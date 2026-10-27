Los stat blocks del vault Campaign usan el plugin **Fantasy Statblocks** con el layout propio **`5e 2024`** (`docs/statblocks/5e 2024.json`, importado en el plugin). Para cambiar el layout: editar el JSON y reimportarlo en *Ajustes → Fantasy Statblocks → Layouts*.

## Formato del bloque

````
```statblock
layout: 5e 2024
columnWidth: 340
name: Soldering Construct
size: Small
type: Construct
subtype: Goblinoid            # lo que va entre paréntesis
alignment: Unaligned
initiative: "+2 (12)"
ac: 13
ac_class: natural armor       # opcional, se muestra "13 (natural armor)"
hp: 13
hit_dice: "3d6 + 3"           # opcional
speed: "30 ft."
stats: [10, 14, 12, 4, 10, 4] # STR DEX CON INT WIS CHA (puntajes, no modificadores)
saves:                        # solo salvaciones distintas del modificador
  - dexterity: 9
skillsaves:
  - perception: 16
damage_vulnerabilities: "..."
damage_resistances: "..."
damage_immunities: "Fire, Poison, Psychic"
condition_immunities: "Charmed, Poisoned"
gear: "..."
senses: "Darkvision 60 ft., Passive Perception 10"
languages: "..."
cr: "1/4"
cr_detail: "XP 50; PB +2"     # el paréntesis original del CR, tal cual
traits:
  - name: Mender's Touch
    desc: |-
      Texto en markdown.
actions: [...]                # mismo formato que traits
bonus_actions: [...]
reactions: [...]
legendary_description: |-
  Texto introductorio.
legendary_actions: [...]
lair_actions: [...]
regional_effects: [...]
habitat: "..."
treasure: "..."
```
````

- El layout dibuja la tabla MOD/SAVE 2024 calculando MOD desde `stats`; SAVE = MOD salvo que esté en `saves`.
- `Immunities` muestra daño y condiciones juntos (`damage; conditions`).
- `columnWidth: 340` hace que los stat blocks largos se partan en dos columnas dentro del ancho de lectura; los cortos quedan en una.
- Strings con `*`, `:`, `[`, `#`, comillas, etc.: usar comillas dobles o bloque `|-`. Para `desc` usar siempre `|-`.

## Reglas de conversión (desde el formato viejo)

- **Fidelidad total**: no resumir, no traducir, no corregir. Copiar cada texto tal cual (incluido español, typos, cursivas `*...*`, enlaces `[..](..)` y `[[..]]`).
- **Nombre**: el `# Nombre` del infobox o la línea de nombre; si no hay, el nombre de la nota. Si hay varias versiones de la misma criatura (Phase 1/2), nombres distintos.
- **Qué entra al bloque**: el callout `[!infobox]` y las secciones de stat block que lo siguen (Traits/Rasgos, Actions/Acciones, Bonus Actions/Acción bonus, Reactions/Reacción, Legendary Actions, Lair Actions, Spellcasting). Las secciones en español van a su campo equivalente, con el texto en español.
- **Qué queda fuera, como markdown normal**: frontmatter, descripciones, Tactics, Descripción, notas del DM, subrazas, enlaces sueltos (p. ej. a aidedd), imágenes (como enlace `[[x.png]]`, nunca incrustadas con `![[...]]`: el usuario no quiere que se vean) y secciones no estándar (Wild Shape, Metamagic, listas de conjuros por nivel, Perks). Mantener su posición: lo que estaba antes del stat block va arriba del bloque; lo demás, abajo.
- **Se descarta**: el wrapper `> [!infobox...]`, las tablas vacías `| |` / `| - |`, `![[Infobox Blank Space.png]]`, separadores `---` internos, y propiedades vacías (p. ej. `**Habitat**` sin valor).
- **Formato 2014**: `Saving Throws` → `saves`; tabla `20 (+5)` → solo el puntaje; `Challenge 7 (2,900 XP)` → `cr: "7"`, `cr_detail: "2,900 XP"`; `Damage Immunities`/`Condition Immunities` → sus campos. Propiedades sin campo (p. ej. `Nivel`, `PB` suelto, `Spellcasting` como línea) → un trait con ese nombre.
- **Enlaces en skills**: la clave puede llevar el enlace (`- "[[Perception]]": 9`); el layout la muestra tal cual, con markdown.
- **Subtítulo**: se arma con `size type (subtype), alignment` y se renderiza como markdown. Si la línea original no tiene ese formato (p. ej. "NPC, jefa arcana (D&D 5e)"), poner la cadena en `type` para que se vea igual.
- **Formas sin puntajes** (Wild Shapes): omitir `stats`; el bloque se muestra sin tabla. El validador lo marca como falso positivo.
- **Texto entre el infobox y las secciones** (descripciones): queda debajo del bloque.
- **Varios stat blocks en una nota** (Bjor, Eryndor Celestia Sheet): un bloque `statblock` por cada uno, en su lugar, con el texto intermedio como markdown.
- **Párrafo sin nombre dentro de una sección**: agregarlo al `desc` del trait anterior. Si es el primero de Legendary Actions, va a `legendary_description`; en otra sección, un trait con el nombre de la sección.

## Crear desde aidedd

- Antes de crear, buscar si ya existe una nota con ese nombre (`find Campaign -iname "*nombre*"`); si existe, editarla, no sobrescribirla.
- Texto copiado del HTML de la página (WebFetch resume; usar `curl`). Debajo del bloque: enlace `[Nombre (DnD 2024)](url)` y la descripción en inglés.
- Criaturas que la nota invoca o menciona y existen en el vault: enlazar con `[[...]]`.
