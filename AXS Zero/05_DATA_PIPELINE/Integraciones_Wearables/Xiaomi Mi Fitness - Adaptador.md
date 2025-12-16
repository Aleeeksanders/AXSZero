# Xiaomi Mi Fitness — Adaptador (Xiaomi Watch S4)

Relacionado con:
- [[Integración Wearables - Alcance]]
- [[Zero Trust Lite - Principios]]
- [[Omni Ring - Disponibilidad de Datos]]

---

## Objetivo
Extraer datos agregados desde Xiaomi/Mi Fitness (si existen).

---

## Datos objetivo
1. Sueño (horas / score)
2. HR promedio o resting HR
3. Estrés (si existe)

---

## Riesgo
- Datos accesibles pueden estar solo en app y no exportables
- Integración oficial puede ser limitada

---

## Fallback obligatorio
Si no hay acceso:
→ usar captura manual guiada
→ no insistir en reverse engineering en Zero Phase

Ver:
→ [[Fallback Manual - Plantilla de Captura]]

---

## Regla
Zero Phase prohíbe ingeniería invasiva.
Esto debe ser limpio, simple y reversible.
