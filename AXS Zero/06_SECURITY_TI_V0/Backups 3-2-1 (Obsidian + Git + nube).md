# Backups 3-2-1 — Zero Phase

Relacionado con:
- [[Infra v0 (local-first)]]
- [[Auditoría y Logs (Lite)]]
- [[Incidentes y Brechas - Protocolo]]

---

## Estrategia 3-2-1

### 3 copias
- Trabajo local
- Backup local externo
- Backup remoto cifrado

### 2 medios
- Disco local
- Nube (Drive / similar)

### 1 fuera del equipo
- Copia offline o cloud

---

## Qué se respalda
- Obsidian vault
- Base de datos SQLite
- Logs críticos

---

## Frecuencia
- Diario: vault
- Semanal: DB
- Mensual: verificación

---

## Regla
Un backup que no se prueba,
**no existe**.
