# Samsung Health — Adaptador (Galaxy Watch 7)

Relacionado con:
- [[Integración Wearables - Alcance]]
- [[Infra v0 (local-first)]]
- [[Omni Ring - Disponibilidad de Datos]]

---

## Objetivo
Extraer datos agregados (si están disponibles) desde el stack Samsung.

---

## Datos objetivo (en orden)
1. Sueño (horas / score)
2. HR promedio o resting HR
3. Estrés (si existe como score)

---

## Estrategia técnica (Zero Phase)
- Preferir export/lectura agregada (no real-time)
- Evitar credenciales persistentes
- Mantener el flujo local-first

---

## Riesgo
- APIs pueden estar cerradas o variar por región/app

---

## Fallback si no hay API estable
- Captura manual guiada (usuario escribe sleep_hours/score)
- Esto mantiene el valor sin romper MVP

Ver fallback:
→ [[Fallback Manual - Plantilla de Captura]]

---

## Regla
No se bloquea Eris por falta de acceso a Samsung Health.
