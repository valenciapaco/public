# Registro de actividad

Este folder lleva el historial de lo que se hace en el repo `public`, pensado para importarse después al sistema personal de tareas.

## Convención

**Un archivo por día**, nombrado:

```
logs/YYYY-MM-DD_repo-public.md
```

El slug `repo-public` va fijo en el nombre del archivo (además de en el frontmatter) para identificar de un vistazo que el log viene de este repositorio, útil si el sistema de tareas junta logs de varias fuentes en una sola carpeta.

Si en un día hay varias actividades, todas van en el mismo archivo (no se crean archivos separados). Si ya existe el log de ese día y hay una actividad nueva, **se edita el archivo existente** agregando una sección más — no se crea un archivo nuevo ni se duplica.

## Formato

```markdown
---
fecha: YYYY-MM-DD
fuente: repo-public
proyectos: [ruta/dentro/de/public, otra/ruta]
tags: [tag1, tag2]
---

# YYYY-MM-DD

## Título breve de la actividad 1

**Proyecto:** ruta/dentro/de/public
**Tipo:** infraestructura | desarrollo | contenido | documentacion
**Importancia:** alta | media | baja
**Commits:** hash1, hash2

### Qué se hizo

- Punto por punto, concreto y verificable.

### Por qué importa

Qué desbloquea, qué riesgo evita, o qué decisión representa.

## Título breve de la actividad 2

(mismo formato, si hubo más de una actividad ese día)
```

### Campos del frontmatter

| Campo | Valores | Uso |
|---|---|---|
| `fecha` | `YYYY-MM-DD` | fecha del día que cubre el log |
| `fuente` | slug fijo `repo-public` | identifica que el log viene del repo `public` — sirve para filtrar por origen al importar a un sistema que agrupe logs de varios repos |
| `proyectos` | lista de rutas relativas dentro de `public/` | unión de todos los proyectos tocados ese día |
| `tags` | lista libre | unión de tags de todas las actividades del día |

### Campos por actividad (dentro del cuerpo)

| Campo | Valores | Uso |
|---|---|---|
| `Proyecto` | ruta relativa dentro de `public/` | qué carpeta/iniciativa se tocó |
| `Tipo` | `infraestructura`, `desarrollo`, `contenido`, `documentacion` | categoría para filtrar/importar |
| `Importancia` | `alta`, `media`, `baja` | prioridad para el sistema personal |
| `Commits` | hashes cortos, separados por coma | trazabilidad hacia git, opcional |

Este README se actualiza si la convención cambia.
