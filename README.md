# Mi Página Web Personal 2025

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Descripción

Este proyecto es un sitio web personal que incluye mi currículum, hobbies, información de contacto y un microjuego interactivo. Desarrollado como parte de un proyecto académico para demostrar habilidades en HTML semántico, CSS y JavaScript.

> [!NOTE]
> Esto es una tarea académica con la funcionalidad de aprender cómo funciona Markdown y GitHub Pages.

> [!WARNING]
> Es un proyecto educativo para aprender el funcionamiento y uso correcto de:
> - HTML semántico
> - GitHub Pages
> - CSS responsive
> - Archivos Markdown (.md)
> - JavaScript básico

## 🚀 Características

- **Diseño Responsive**: Adaptable a diferentes tamaños de pantalla
- **HTML Semántico**: Estructura optimizada para accesibilidad
- **Formulario de Contacto**: Con validación de campos
- **Microjuego**: Juego de adivinar números implementado con JavaScript
- **Navegación Intuitiva**: Menú de navegación consistente en todas las páginas

## 🔍 Estructura del Proyecto

- `index.html` - Página principal
- `cv.html` - Currículum Vitae
- `hobbies.html` - Sección de hobbies e intereses
- `contacto.html` - Formulario de contacto
- `microjuego.html` - Juego interactivo
- `proyectos.html` - Página de proyectos personales y académicos
- `style.css` - Estilos del sitio web
- `README.md` - Documentación del proyecto

## 📄 Descripción Detallada de Archivos

A continuación, se detalla el propósito y la estructura de los principales archivos del proyecto:

### HTML (`.html`)

Todos los archivos HTML comparten una estructura semántica común utilizando etiquetas como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, y `<footer>` para asegurar la accesibilidad y una correcta organización del contenido. Cada página incluye una barra de navegación consistente para facilitar el desplazamiento por el sitio.

#### `index.html`
- **Propósito**: Es la página de inicio del sitio web. Proporciona una bienvenida general y enlaces a las principales secciones.
- **Elementos Clave**: Suele contener un resumen o introducción al contenido del sitio.

#### `cv.html`
- **Propósito**: Presenta el Currículum Vitae del autor, detallando experiencia laboral y formación académica.
- **Elementos Clave**: Secciones para experiencia, formación, y potencialmente habilidades o certificaciones.

#### `hobbies.html`
- **Propósito**: Describe los hobbies e intereses personales del autor.
- **Elementos Clave**: Secciones para diferentes tipos de hobbies, posiblemente con imágenes o descripciones más detalladas.

#### `contacto.html`
- **Propósito**: Proporciona un formulario para que los visitantes puedan enviar mensajes o consultas.
- **Elementos Clave**: Un formulario HTML (`<form>`) con campos para nombre, email, mensaje, etc., y validaciones básicas.

#### `microjuego.html`
- **Propósito**: Alberga un microjuego interactivo, como el juego de adivinar números, implementado con JavaScript.
- **Elementos Clave**: Elementos HTML para la interfaz del juego (entrada de números, botones, mensajes de feedback) y un script de JavaScript (`<script>`) que contiene la lógica del juego.

#### `proyectos.html`
- **Propósito**: Este apartado extra detalla algunos de los proyectos personales o académicos que el autor ha realizado o tiene pensado realizar.
- **Elementos Clave**: Secciones o artículos (`<article>`) para cada proyecto, describiendo su objetivo, tecnologías utilizadas y estado actual (terminado, en desarrollo, sin comenzar).

### CSS (`.css`)

#### `style.css`
- **Propósito**: Define todos los estilos visuales del sitio web, asegurando una apariencia coherente y agradable en todas las páginas.
- **Estructura y Características**:
  - **Diseño Responsivo**: Utiliza media queries (`@media`) para adaptar el layout a diferentes tamaños de pantalla (móviles, tablets, escritorio).
  - **Selectores**: Emplea una combinación de selectores de tipo, clase, ID y descendientes para aplicar estilos de forma específica.
  - **Modelo de Caja**: Define márgenes, paddings, bordes y dimensiones de los elementos.
  - **Tipografía**: Establece fuentes, tamaños de texto, colores y alineaciones.
  - **Colores y Fondos**: Define la paleta de colores del sitio y los fondos de los elementos.
  - **Layout**: Puede utilizar técnicas como Flexbox o Grid para la disposición de los elementos principales de la página (aunque esto dependerá de la implementación específica).
  - **Estilos Generales**: Define estilos base para elementos comunes como `body`, `h1-h6`, `p`, `a`, etc.
  - **Estilos Específicos**: Contiene estilos para componentes particulares como la barra de navegación, tarjetas de proyectos, formularios, etc.

## 💻 Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- GitHub Pages

## 📝 Ejemplos de Código

<details>
<summary>Ejemplo de formulario HTML</summary>

```html
<form method="post" action="#" class="contact-form">
  <section class="form-section">
    <h3>Datos personales</h3>
    
    <p class="form-field">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>
    </p>
    
    <!-- Más campos del formulario -->
  </section>
</form>
