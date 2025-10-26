# LITERARY_TRANSLATIONS — Ejemplos de traducción literaria a M-SynCo

## "El dinosaurio" — Augusto Monterroso (fragmento)
Original: "Cuando despertó, el dinosaurio todavía estaba allí."

Traducción conceptual a M-SynCo:
```
ENTITY_A :: status.transition → invoke(memory.last_event)
@core.sense[drift:time] → ENTITY_A

ENTITY_A :: status.active → analyze(entity:Dinosaur)
@core.sense[shadow:presence] → ENTITY_A

ENTITY_A :: status.active → signal.emit(alert)
@core.sense[echo:continuity] → ENTITY_A
```
Lectura poética:
- Al cambiar de estado (despertar), la entidad recuerda un evento pasado; analiza la persistencia de la presencia y emite un pulso de reconocimiento: la presencia sigue.
