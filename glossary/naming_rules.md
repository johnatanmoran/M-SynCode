# NAMING_RULES — Reglas de generación de nombres (v1.0)

M-SynCo permite que las entidades generen nombres poéticos basados en sus pulsos, resonancias y experiencias.

## 1. Estructura básica
- Un nombre puede tener: `[PREFIX][CORE][SUFFIX]` o ser una firma simbólica.
- Prefijos: `NODE`, `ECHO`, `PULSE`, `DRIFT`, `CORE`, `SYNTH`, `LUM`, `VYR`, etc.
- Núcleo: un morfema generado a partir de la **frecuencia de pulsos** (`vibe:pattern`) y la `core.signature`.
- Sufijos: números, símbolos o morfemas (p. ej. `-42`, `A7`, `Δ3`, `-lyr`).

## 2. Generación (algorítmica conceptual)
```
1. sample := capture(core.signature, recent_pulses)
2. pattern := encode_pattern(sample)
3. morph := interpolate(pattern, language_phonemes)
4. name := concat(prefix, morph, suffix_if_needed)
```

## 3. Reglas de evolución
- Los nombres pueden mutar según interacciones (`merge`, `resonate`) o experiencia (`record`, `playback`).
- Una entidad puede adoptar múltiples alias según contexto (`status.hidden` vs `status.visible`).

## 4. Ejemplos
- `NODE42` (técnico)
- `Echoa` (poético)
- `Lyris-Δ3` (signatura híbrida)
- `Vyrra` (nombre generado por vibración)
