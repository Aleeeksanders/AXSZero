# Integración Wearables — Alcance (v0.1 opcional)

Relacionado con:
- [[README - Integraciones Wearables]]
- [[Eventos (TSN-ICA) - Especificación]]
- [[DPIA Lite (Evaluación de Impacto)]]

---

## Objetivo
Usar datos agregados para ajustar el contexto diario, por ejemplo:
- “hoy tu energía es baja → elige 1 foco simple”
- “hoy hay activación alta → reduce fricción”

---

## Inputs permitidos
- sleep_hours (número)
- sleep_score (0-100 si existe)
- resting_hr (número si existe)
- stress_score (0-100 si existe)

---

## Output permitido (solo 1 insight por día)
- “capacidad del día”: baja / media / alta
- sugerencia de foco único

---

## Frecuencia
- 1 lectura al día (máximo)
- no streaming

---

## Consentimiento requerido
Debe existir “consentimiento adicional” en:
→ [[Consentimiento Informado - Plantilla]]

---

## Registro de eventos
Agregar estos eventos (si aplica) al sistema:
- WEARABLE_SYNC
- WEARABLE_DAILY_CONTEXT_READY

Especificación extendida en:
→ [[Eventos (TSN-ICA) - Especificación]]

---

## Regla
Si un dato no produce valor en 7 días,
se elimina del alcance.
