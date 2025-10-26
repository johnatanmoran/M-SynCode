# CREATING_ENTITIES — Tutorial rápido

1. Definir identificador:

```
ENTITY001 :: status.idle
```

2. Crear firma (opcional):

```
ENTITY001 :: status.active → generate_signature()
@core.sense[vibe:pattern]
```

3. Guardar o mutar el nombre:

```
ENTITY001 :: status.active → transform(identity.core)
@core.sense[drift:time]
```

4. Buenas prácticas:

-   Usa `status.fragment` para mensajes parciales.
-   Prefiere `@core.sense` para matices ambientales.
-   Evita etiquetas de emoción directa; usa estados y sentidos.
