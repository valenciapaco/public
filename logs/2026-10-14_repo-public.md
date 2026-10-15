---
fecha: 2026-10-14
fuente: repo-public
proyectos: [maestria/m7/fix-it, maestria/m7/bitacora-ia]
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

## Ajustes al prototipo de Fix it! tras la primera prueba de usabilidad (v1.3 y v1.4)

**Proyecto:** maestria/m7/fix-it
**Tipo:** desarrollo
**Importancia:** alta
**Commits:** 06f6312, 1391d55

### Qué se hizo

- v1.3: la pantalla de preparación de cada ronda indica con pasos numerados que la carta de personaje del juez se muestra a todos y que lo único secreto es el lugar y la necesidad; el botón de inicio pide confirmar que todos vieron el personaje.
- v1.4: "Cómo se juega" pide leer cada pantalla en voz alta al grupo, con textos más cortos; el +1 (mención especial) también es opcional ("Nadie destacó"). El +2 sigue siendo obligatorio.

### Por qué importa

Responde a los hallazgos de la primera prueba con un anfitrión externo: el grupo entendió que la carta del juez era secreta, el anfitrión tardó de 5 a 7 minutos en arrancar porque sentía que debía entender todo antes de explicarlo, y los puntos obligatorios incomodaban cuando nadie los merecía.

## Bitácora de uso de IA del proyecto de M7

**Proyecto:** maestria/m7/bitacora-ia
**Tipo:** documentacion
**Importancia:** alta
**Commits:** fc1cd86

### Qué se hizo

- Publicada la bitácora de uso de IA generativa del proyecto integrador de M7 (página con línea de tiempo, usos por tipo de tarea y decisiones del autor).
- Publicada la conversación completa de la sesión de Claude Code, anonimizada (participantes con nombre e inicial; sin rutas locales ni correos).

### Por qué importa

La profesora pidió declarar el uso de IA conforme a la política de APA del curso, con enlace al chat utilizado. Esta URL es la que se cita en el documento final.
