# README — Integraciones Wearables (Zero Phase)

Relacionado con:
- [[Fuentes de Datos (manual - dispositivos - futuro)]]
- [[Consentimiento Informado - Plantilla]]
- [[Eris v0 - Alcance]]
- [[Kill Switch Integraciones]]

---

## Propósito
Agregar inputs fisiológicos **opcionales** a Eris v0 sin romper:
- MVP
- compliance Chile
- foco del proyecto

---

## Regla central
Eris v0 funciona **100% sin sensores**.

Las integraciones solo pueden:
- entregar contexto
- sugerir foco (soft)
- generar alertas suaves (no clínicas)

---

## Datos permitidos (solo agregados)
- Sueño (horas / score)
- HR promedio (reposo si existe)
- Estrés agregado (si el proveedor lo expone)

Definido en:
→ [[Integración Wearables - Alcance]]

---

## Datos prohibidos (Zero Phase)
- HRV raw
- señales médicas
- ubicación
- inferencias clínicas

---

## Estado
🟢 Activo como opcional  
Si complica el MVP → se apaga con [[Kill Switch Integraciones]].
