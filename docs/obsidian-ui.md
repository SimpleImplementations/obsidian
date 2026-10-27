Interactuar con la UI de Obsidian **solo cuando el usuario lo pida**.

## Ver qué tiene abierto

Leer `Campaign/.obsidian/workspace.json`: las hojas (`type: "leaf"`) bajo `main` tienen el archivo en `state.state.file`; `active` es el id de la pestaña activa; `lastOpenFiles` es el historial reciente.

## Abrir una nota

```bash
xdg-open "obsidian://open?vault=Campaign&file=Sesiones%2FCamino%20de%20la%20Party&paneType=tab"
```

- Siempre con `paneType=tab`: abre en pestaña nueva. Sin eso reemplaza la pestaña activa y le cierra al usuario lo que tenía abierto. **Nunca cerrar ni reemplazar lo que está abierto.**
- `file` es la ruta dentro del vault, sin `.md`, URL-encoded.
- Verificar después en `workspace.json` (Obsidian tarda un momento en guardarlo; si no aparece, volver a leer).

## Lo que no se hace

- No editar `workspace.json` con Obsidian abierto (lo sobrescribe) ni para cambiar el layout.
- No intentar controlar la UI de otras formas (clics, automatización); si algo no sale con la URI, decirlo y no buscar workarounds.
