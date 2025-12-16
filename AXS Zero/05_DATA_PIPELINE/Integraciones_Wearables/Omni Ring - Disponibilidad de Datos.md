# Omni Ring — Disponibilidad de Datos (Zero Phase)

Relacionado con:
- [[Integración Wearables - Alcance]]
- [[Kill Switch Integraciones]]

---

## Objetivo
Definir qué datos del Omni Ring son accesibles **realmente**.

---

## Lista esperada (hipótesis)
- Sueño (horas/score)
- HR promedio
- Estrés o readiness (si existe)

---

## Validación requerida
Antes de integrar:
- Confirmar si hay exportación
- Confirmar si hay API
- Confirmar si hay “data sync” fuera de su app

---

## Resultado
- ✅ Integrable (datos agregados accesibles)
- ⚠️ Semi-integrable (solo export manual)
- ❌ No integrable (app cerrada)

Registrar resultado en:
→ [[Estado de Integraciones - Tabla]]

---

## Regla
Si no hay acceso real, no se fuerza.
Se usa fallback manual.
