---
fecha: 2026-08-21
fuente: repo-public
proyectos: [logs]
tags: [proceso, registro, sistema-personal]
---

# 2026-08-21

## Definición del sistema de registro de actividad (logs por día)

**Proyecto:** logs
**Tipo:** documentacion
**Importancia:** media
**Commits:** (pendiente de commitear)

### Qué se hizo

- Se definió la convención de registro: un archivo markdown por día (`logs/YYYY-MM-DD.md`), con frontmatter YAML (`fecha`, `proyectos`, `tags`) y una sección por actividad dentro del mismo archivo (con `Proyecto`, `Tipo`, `Importancia`, `Commits`, `Qué se hizo`, `Por qué importa`).
- Si un día ya tiene log y surge una actividad nueva, se edita ese mismo archivo agregando una sección — no se crean archivos nuevos por actividad.
- Se documentó la convención en `logs/README.md`.
- Se reconstruyeron, en retrospectiva, los logs de los días previos de la sesión (2026-08-19: conexión del repo; 2026-08-20: herramienta de naming).

### Por qué importa

Sin esta convención, el trabajo hecho en el repo no queda trazado en ningún lugar fuera de git — y git no es un formato fácil de importar a un sistema de tareas personal. El formato por día, con frontmatter estructurado, es la unidad que se va a importar al sistema personal, así que fijar bien la convención ahora evita tener que reformatear el histórico después.
