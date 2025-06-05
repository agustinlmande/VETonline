# VETonline – Diseño Web Adaptable

El proyecto **VETonline** fue desarrollado aplicando el principio de **Diseño Web Adaptable (Responsive Web Design)**, lo que garantiza que la estructura y el contenido del sitio se ajusten correctamente a distintos tamaños de pantalla y dispositivos, desde monitores de escritorio hasta smartphones.

---

## Tecnologías utilizadas

- **HTML5**: para la estructura semántica del contenido.
- **CSS3**: para el diseño visual y estilos responsivos mediante _media queries_.
- **Diseño mobile-first progresivo**: enfoque de diseño que prioriza pantallas pequeñas y se adapta a resoluciones mayores.

---

## Estrategias de diseño responsivo implementadas

### Unidades relativas

- Uso de `%` para evitar valores fijos que limiten la adaptabilidad.

### Sistema de grillas CSS (Grid Layout)

Aplicado al formulario mediante `grid-template-columns`, que se ajusta automáticamente con _media queries_:

- Tres columnas en pantallas grandes
- Dos columnas en tablets
- Una columna en dispositivos móviles

### Media Queries

- Hasta 1200px: se reduce el tamaño de imágenes, márgenes y botones.
- Hasta 768px: el formulario cambia a dos columnas.
- Hasta 480px: el diseño se adapta a una sola columna, optimizando la legibilidad.

### Contenedores con `max-width` y `min-width`

- Garantizan legibilidad en diferentes dispositivos sin romper la estructura.

### Imágenes fluidas

- `width: 100%` y `height: auto` para que se ajusten sin deformarse.

### Flexbox

- Utilizado en elementos como el menú de navegación y botones para distribuir contenido de forma flexible y centrada.

---

## Footer completamente adaptable

El pie de página cuenta con una imagen de fondo (`bg-final.PNG`) ubicada en la carpeta **Imágenes**, que se adapta mediante:

- `background-size: cover`
- `background-position: center`
- `min-height` y `padding` con unidades relativas

El contenido del footer (datos de contacto e íconos) se reorganiza verticalmente en pantallas pequeñas para garantizar accesibilidad.

---

## Resultado

Gracias a estas implementaciones, el sitio mantiene una experiencia de usuario coherente y profesional en todo tipo de dispositivos, cumpliendo con los principios fundamentales del diseño web moderno y accesible.
