## Raíces

- Raíz del repo: solo `AGENTS.md`, `CLAUDE.md`, `docs/` y los dos vaults. Cualquier otra nota o imagen suelta acá queda fuera de los vaults (Obsidian no la ve): revisar si se usa y moverla a `Campaign/`, o confirmar antes de borrarla.
- Raíz de `Campaign/`: vacía. Obsidian crea las notas nuevas en `Campaign/Unsorted/` (`newFileLocation` en `.obsidian/app.json`); al ordenar, moverlas de ahí a su carpeta.

## Carpetas de `Campaign/`

| Carpeta | Qué va |
|---|---|
| `Characters/` | NPCs y sus stats (`<Nombre> Stats`). Ardyn está acá. |
| `Characters/Player Characters/` | PJs (Aira, Delaken, Lucke, Lairtou, …) |
| `Characters/Barbaros Goliath/` | Grupo con folder note |
| `Creatures/` | Monstruos y stat blocks de criaturas (incl. `Askadar Stats Phase 1/2`) |
| `Combates/` | Combates preparados (encuentro, mecánicas, links a stats) |
| `Special Notes/` | Preparación de escenas/aventuras (p. ej. `Viaje al plano Astral`, `Ardyn en Valdrias Islas`, `Personajes Tromvas Aftermath`) |
| `Places/` | Lugares, incl. lugares dentro de otros (`El Salto`, `Templo de Moradin`, `Biblioteca Marlavir`). Las locaciones nuevas van acá (decisión provisoria, no reorganizar sin preguntar). |
| `Places/Special/` | Lugares especiales/planares |
| `Lore/` | Historia, dioses, planos, familias y grupos (`La Manada`, `Lagmagnar`) |
| `Mechanics/` | Reglas homebrew y tablas de mecánicas (`Lingering Injury`) |
| `Spells/` | Conjuros, con tag `spell` y link a aidedd |
| `items/` | Objetos |
| `Sesiones/` | Sesiones, índice y `Camino de la Party`. Ver `docs/sesiones.md` |
| `Tablas Random/` | Tablas aleatorias |
| `Tools/` | Herramientas del DM (nombres, glosario, tareas, música) |
| `Templates/` | Plantillas (la de sesión está desactualizada) |
| `Images/` | Solo imágenes |
| `Audio/` | Audio embebido en sesiones |
| `Unsorted/` | Notas nuevas sin ordenar |

## Mover notas

- Los enlaces son por nombre (`[[Nota]]`), sin rutas, así que mover no los rompe **si el nombre es único** en el vault. Verificar con `find Campaign -name "<Nota>.md"` antes de mover.
- Mover con `mv`; git detecta el rename al hacer `git add -A`.
- Antes de borrar algo, buscar referencias (`grep -rn "<nombre>" --include=*.md Campaign`) y si hay un duplicado con más contenido.
