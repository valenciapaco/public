# Diplomado en Habilidades Directivas para la Era de la IA — Media Kit

Media kit de campaña para el **Diplomado en Habilidades Directivas para la Era de la Inteligencia Artificial** de la Universidad Latina de América (UNLA). Assets y textos listos para que el cuerpo docente y el equipo UNLA difundan la clase muestra y las inscripciones.

## Estructura

```
.
├── media-kit.html          # El media kit (slides) — se genera a partir del MD
├── media-kit-fuente.md     # Fuente de contenido (editar aquí primero)
├── README.md
└── assets/
    ├── cards/              # Ecards de los 6 profesores
    │   ├── francisco-valencia.png
    │   ├── helena-hernandez.png
    │   ├── alejandro-montoya.png
    │   ├── arturo-monroy.png
    │   ├── jose-antonio-reyes.png
    │   └── jairo-flores.png
    └── ads/                # Imágenes de campaña
        ├── clase-muestra-cuadrado.jpeg      # clase muestra (feed)
        ├── clase-muestra-vertical.jpeg      # clase muestra (historias)
        ├── general-cuadrado.png             # publicidad general (feed)
        └── general-vertical.png             # publicidad general (historias)
```

## Fechas clave

- **Clase muestra gratuita:** 29 de septiembre de 2026
- **Cierre de inscripciones:** 2 de octubre de 2026
- **Diplomado:** del 9 de octubre de 2026 al 9 de abril de 2027

## Links

- Registro a la clase muestra: https://forms.gle/zxtf3FFQ2NyXszwt9
- PDF con la info del diplomado: https://x.gd/HDIA_UNLA

## Flujo de trabajo

1. El contenido se edita en `media-kit-fuente.md`.
2. De ahí se genera `media-kit.html` (slides con la identidad visual del diplomado).
3. Las imágenes se colocan en `assets/` con los nombres de arriba y el HTML las llama por ruta relativa.
