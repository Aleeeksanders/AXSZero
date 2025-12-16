# Modelo de Datos v0 — SQLite (local)

Relacionado con:
- [[Eris.Memory - Esquema mínimo]]
- [[Retención y Borrado de Datos]]
- [[Auditoría y Logs (Lite)]]

---

## Tabla: sessions
- session_id (UUID)
- date
- raw_text
- summary_text
- focus
- tension_level (low/medium/high)

---

## Tabla: consent
- consent_version
- accepted_at

---

## Tabla: system_logs
- timestamp
- event_type
- description

---

## Exclusiones
- No user_id global
- No tracking cross-device
- No perfiles persistentes complejos

---

## Regla
Datos simples → sistema comprensible → menos riesgo.
