# Explicación de Cambios del CV Personal

## 1. Cambios en HTML (Contenido y Estructura)

El archivo `index.html` ha sido modificado para reemplazar el contenido genérico por mi información personal y profesional.

* **Contenido:** Se rellenaron todas las secciones con mis datos personales, incluyendo nombre, título, información de contacto (teléfono, email, ubicación).
* **Secciones Nuevas:** Se estructuró y completó la información de "Experiencia Profesional", "Formación Académica", "Habilidades", "Aptitudes" e "Idiomas".
* **Imagen:** Se añadió una etiqueta `<img>` para incluir mi foto de perfil.
* **Estructura Semántica:** Se organizó el contenido usando clases CSS (`.container`, `.header`, `.header-left`, `.header-right`, `.foto-perfil`, `.experience-item`, etc.) para poder aplicar estilos específicos.
* **Enlace a CSS:** Se enlazó correctamente la hoja de estilos externa (`<link rel="stylesheet" href="styles.css">`) para separar el contenido (HTML) de la presentación (CSS).

---

## 2. Cambios en CSS (Estilo y Diseño)

Se creó un archivo `styles.css` desde cero para aplicar un diseño visual moderno y profesional al CV.

* **Layout General:** Se utilizó un `.container` para centrar el CV en la página, dándole un fondo blanco, bordes redondeados y una sombra (`box-shadow`) para crear un efecto de "tarjeta" sobre un fondo de página gris claro (`#f4f4f4`).
* **Tipografía:** Se importó y aplicó la fuente 'Poppins' desde Google Fonts para un aspecto más limpio y moderno que la fuente por defecto.
* **Encabezado (Flexbox):** Se utilizó `display: flex` en el `<header>` para colocar la información de contacto (`.header-left`) y la foto de perfil (`.header-right`) una al lado de la otra, alineándolas verticalmente.
* **Foto de Perfil:** Se aplicó un `border-radius: 50%` a la clase `.foto-perfil` para que la imagen se muestre en un círculo perfecto, y se ajustó su tamaño (`width` y `height`).
* **Paleta de Colores:** Se definió una paleta de colores profesional, usando un azul (`#0056b3`) para los títulos (`h1`, `h2`) y tonos de gris oscuro para el texto, mejorando la legibilidad.
* **Espaciado:** Se utilizó `margin` y `padding` de forma consistente para asegurar una buena separación visual entre las secciones, mejorando la jerarquía y el orden de la información.
