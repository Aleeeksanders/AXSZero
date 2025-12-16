# Eventos — TSN / ICA (Zero Phase)

Relacionado con:
- [[TSN Interna - Variables permitidas (T, ΔT)]]
- [[Auditoría y Logs (Lite)]]

---

## Eventos Permitidos

### SESSION_START
- fecha
- consentimiento válido (sí/no)

### INPUT_RECEIVED
- longitud del texto
- tono general (neutral)

### TENSION_ESTIMATED
- T ∈ {low, medium, high}

### FOCUS_SELECTED
- foco elegido por el usuario

### SESSION_END
- duración
- feedback (sí/no)

---

## Eventos Prohibidos
- Riesgo clínico
- Predicción de conducta
- Inferencias de salud

---

## Regla
Eventos describen hechos,
**no interpretaciones profundas**.
