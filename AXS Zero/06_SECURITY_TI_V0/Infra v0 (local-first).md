# Infra v0 — Local-first (AXS Zero Phase)

Relacionado con:
- [[Modelo de Datos v0 (SQLite)]]
- [[Backups 3-2-1 (Obsidian + Git + nube)]]
- [[Matriz de Roles y Accesos — Técnica]]

---

## Principio Base
Todo corre **localmente** mientras sea posible.

---

## Componentes Activos
- Aplicación local (desktop / local server)
- Base de datos SQLite
- Archivos Markdown (Obsidian)
- Backups manuales y automáticos

---

## Componentes Apagados
- Cloud permanente
- Microservicios
- Autenticación federada
- Exposición pública

---

## Justificación
- Menor superficie de ataque
- Menor carga legal
- Mayor control del dato

---

## Regla
Cloud solo se activa si:
→ el producto ya es usado
→ y lo exige la experiencia
