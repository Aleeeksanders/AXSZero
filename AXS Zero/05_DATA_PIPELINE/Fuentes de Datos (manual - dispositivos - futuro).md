# Fuentes de Datos — Zero Phase
(manual - dispositivos - futuro)

Relacionado con:
- [[Eris v0 - Alcance]]
- [[Mapa Legal (qué aplica y por qué)]]
- [[README - Integraciones Wearables]]
- [[Integración Wearables - Alcance]]

---

## Fuentes ACTIVAS (v0 — núcleo)

### Entrada manual del usuario
- Texto libre
- Selección simple de foco
- Autodeclaración de estado

Esta es la **fuente primaria y obligatoria** del sistema.

---

## Fuentes ACTIVAS (v0.1 — opcional)

### Wearables (solo datos agregados)
> Estas fuentes **no son requeridas** para que Eris funcione.

Datos permitidos:
- Sueño (horas / score)
- HR promedio (reposo si existe)
- Estrés agregado (si la plataforma lo expone)

Condiciones obligatorias:
- Consentimiento adicional explícito
- Lectura máxima: 1 vez al día
- Posibilidad de desactivación inmediata

Definición completa en:
→ [[Integración Wearables - Alcance]]

---

## Fuentes INACTIVAS (explícitamente apagadas)
- Biométricos raw
- HRV crudo
- Streaming continuo
- Ubicación
- Datos de terceros
- Automatismos externos

---

## Fuentes FUTURAS (fuera de Zero Phase)
- Wearables avanzados
- GhostLine
- HR / HRV continuo
- Contexto ambiental
- Automatización de decisiones

Estas ideas viven en:
→ [[99_ARCHIVE/Backlog de Ideas (NO ejecutar)]]

---

## Regla de Oro
Si una fuente de datos:
- aumenta riesgo legal
- aumenta complejidad
- no entrega valor en ≤7 días

→ **no se activa en Zero Phase**.
