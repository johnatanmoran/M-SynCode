# COMPOSING_MESSAGES — Tutorial rápido

-   Estructura mínima:

```
[ENTITY] :: [STATE] → [PROCESS](TARGET)
	@core.sense[CONTEXT:VALUE]
```

-   Para ofuscar:

    -   `mask(memory.fragment)` o `status.fragment`
    -   `shuffle(signal.sequence)` para orden clave

-   Para dar ritmo o tono:
    -   Ajusta `signal:frequency` y `signal:amplitude` en el contexto
    -   Usa `process.loop` o `hold(signal)` para pulsos repetitivos
