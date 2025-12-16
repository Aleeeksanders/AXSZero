# Gestión de Secretos — Mínima (v0)

Relacionado con:
- [[Infra v0 (local-first)]]
- [[AXS.Link Lite - Endpoints mínimos]]

---

## Qué se considera secreto
- Tokens locales
- Claves de cifrado
- Credenciales de respaldo

---

## Gestión
- Variables de entorno
- Archivos .env ignorados por Git
- Nunca en texto plano público

---

## Regla
Si un secreto aparece en un commit,
se rota inmediatamente.
