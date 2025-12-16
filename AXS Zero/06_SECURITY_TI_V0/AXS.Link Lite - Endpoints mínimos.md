# AXS.Link Lite — Endpoints mínimos (v0)

Relacionado con:
- [[Infra v0 (local-first)]]
- [[Eventos (TSN-ICA) - Especificación]]

---

## Rol de AXS.Link Lite
Comunicación **interna y controlada** entre:
- UI
- lógica de Eris
- almacenamiento local

---

## Endpoints Permitidos (conceptuales)

- /session/start
- /session/input
- /session/end
- /consent/check
- /data/export
- /data/delete

---

## Seguridad
- Solo localhost
- Sin exposición externa
- Tokens simples por sesión

---

## Regla
Si no es necesario para Eris v0 → no existe.
