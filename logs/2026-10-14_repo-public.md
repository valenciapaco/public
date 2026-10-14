---
fecha: 2026-10-14
fuente: repo-public
proyectos: [maestria/m7/fix-it]
tags: [maestria, ux, prototipo, keewe]
---

# 2026-10-14

## Prototipo del asistente del anfitrión de Fix it!

**Proyecto:** maestria/m7/fix-it
**Tipo:** desarrollo
**Importancia:** alta
**Commits:** 7ccb0f1

### Qué se hizo

- Publicado el prototipo funcional de la app web del anfitrión de Fix it! (juego de KEEWE) en `maestria/m7/fix-it/index.html`.
- Incluye configuración de jugadores y duración estimada, reglas en 3 pasos, ronda de prueba guiada, temporizador, puntuación con criterios 3 · 2 · 1, marcador con rotación de jueces y cierre con ganador.
- Versión v1.1: corrige el texto de la regla de puntos y el +30 s del temporizador, que se arrastraba a las rondas siguientes.

### Por qué importa

Es el prototipo navegable de la entrega final de la materia 7 de la maestría (Diseño de Experiencias para Usuarios). La URL pública permite hacer las pruebas de usabilidad y compartirlo con la profesora sin configurar permisos.

## Ajustes al prototipo de Fix it! (v1.2)

**Proyecto:** maestria/m7/fix-it
**Tipo:** desarrollo
**Importancia:** media
**Commits:** cd09214

### Qué se hizo

- El +3 ("mejor resuelve mi necesidad") ahora es opcional: el juez puede elegir "Nadie resolvió mi necesidad". El +2 y el +1 siguen siendo obligatorios y a personas distintas.
- Opción de 1, 2 o 3 vueltas; rondas totales = jugadores × vueltas, con minutos estimados. El marcador muestra la vuelta y cuántas veces ha sido juez cada persona.

### Por qué importa

Define una regla que en los pilotos se resolvía de forma inconsistente y permite partidas más largas sin perder la equidad entre jueces.
