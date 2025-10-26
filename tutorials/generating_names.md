# GENERATING_NAMES — Guía conceptual

1. Captura la firma:

```
sample := capture(core.signature, recent_pulses)
```

2. Codifica un patrón:

```
pattern := encode_pattern(sample)
```

3. Mapea a fonemas o morfemas:

```
morph := interpolate(pattern, phoneme_set)
```

4. Concatena con prefijo/sufijo:

```
name := concat(prefix, morph, suffix)
```

5. Ejemplo conceptual:

-   `prefix = "Vyr"`
-   `morph = "ra"`
-   `suffix = "-Δ3"`
-   Resultado: `Vyrra-Δ3`
