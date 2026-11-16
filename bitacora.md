
---

## 📄 FASES.md

```markdown
# Proceso de Desarrollo por Fases

Documentación del avance del portafolio, construido en **8 fases** para mantener un historial de commits limpio y comprensible. Cada fase añade una capa funcional o visual sobre la anterior.

---

## Fase 1: Estructura base, fuentes y variables
- Se creó el archivo `index.html` con el esqueleto HTML5 y los metadatos.
- Se conectó Tailwind CSS vía CDN y Google Fonts (`Bangers` e `Inter`).
- Se definieron las variables CSS de color (`--tinta`, `--papel`, `--papel-alt`, `--carbon`, `--acento`) y la tipografía `.font-manga` en `styles.css`.

## Fase 2: Navegación y cabecera (Header)
- Se añadió un `<header>` fijo (`sticky top-0`) con borde inferior negro.
- Se incluyeron enlaces internos a `#sobre-mi`, `#habilidades`, `#aprendizaje` e `#intereses`.
- Se agregaron enlaces externos a GitHub y Gmail usando listas `<ul>` y estilos de botón redondeado.

## Fase 3: Layout de 3 columnas y viñetas base
- Se creó una cuadrícula principal de 3 columnas (`aside` izquierdo, `main` central, `aside` derecho).
- Se definieron los estilos `.vineta` (borde de 2 px) y `.sombra-tinta` (sombra dura de 3 px).
- Los paneles laterales se hicieron `sticky` para acompañar el scroll.

## Fase 4: Viñeta Hero (solo texto)
- Se construyó la primera viñeta con el estado “disponible”, el nombre **Sebastián Ortega** en naranja y los botones de acción.
- Se usó tipografía de cómic (`font-manga`) y se reservó el color naranja (`orange-500`) para resaltados.

## Fase 5: Imagen del Hero y sección “Sobre mí”
- Se dividió la viñeta Hero en dos columnas: texto e imagen de retrato.
- Se creó la estructura base de “Sobre mí” con los primeros párrafos de texto.

## Fase 6: GIF personal y sección de Habilidades
- Se integró el GIF animado personal en la sección “Sobre mí”.
- Se añadió la rejilla de habilidades con tarjetas para desarrollo, idiomas, sociales y aprendizaje actual.
- Se incluyó una imagen adicional (`HSE.png`) dentro de la rejilla.

## Fase 7: Sección Intereses y corte diagonal
- Se aplicó `clip-path: polygon(...)` para crear un corte diagonal superior en la sección de intereses.
- Se maquetó el contenido de intereses con una imagen y bloques de texto.

## Fase 8: Footer y ajustes responsive
- Se añadió el `<footer>` con el mensaje “Fin del capítulo”, enlaces de contacto y créditos.
- Se incorporaron media queries para móviles (sombra más fina, corte diagonal más pequeño, `scroll-padding` adaptado) y `prefers-reduced-motion`.

---

## Ajustes posteriores (fuera de las 8 fases)

- **Personalización de contenido:** Se reemplazaron los textos de ejemplo por la filosofía de vida, los intereses personales y las aspiraciones profesionales reales.
- **Eliminación de los `<aside>` laterales:** Para centrar la lectura y dar más protagonismo a las viñetas, se removieron los paneles laterales y se ajustó el ancho máximo del contenedor a `max-w-5xl`.
- **Corrección de errores de marcado:** Se cerraron comillas faltantes en atributos `alt` y `class` de las imágenes, y se reorganizaron etiquetas `<div>` en la sección de intereses.
- **Actualización de enlaces reales:** Se sustituyeron los enlaces de ejemplo por el perfil de GitHub y el correo electrónico personales.