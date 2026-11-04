# Portafolio Profesional - Lucía Quesada

Este proyecto consiste en el desarrollo de un portafolio personal interactivo de una sola página (single-page). Está diseñado bajo el enfoque **Mobile-First** y estructurado con **HTML semántico moderno** y **CSS avanzado**, garantizando una adaptabilidad óptima tanto en dispositivos móviles (360px) como en pantallas de escritorio grandes (1440px).

---

## Enlaces del Proyecto

*   **Sitio Web Publicado (GitHub Pages):** 
*   **Video Explicativo (YouTube Unlisted):** https://youtu.be/zzPF7jiwh_8

---

## Tecnologías y Conceptos Implementados

### 1. Estructura y Semántica HTML5

*   Uso estricto de contenedores semánticos principales: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` y `<footer>`.
*   Uso de elementos multimedia correctos como `<figure>` y `<figcaption>` para el manejo de imágenes y metadatos visuales.
*   Formularios de contacto accesibles con validación nativa de tipos y campos obligatorios (`required`, `type="email"`).

### 2. Estilos y CSS Arquitectónico (Mobile-First)

*   **Selectores Avanzados:** Implementación obligatoria de selectores de hijo directo (`.nav-container > ul`), hermano adyacente (`h2 + p`), selectores de atributos (`a[href^="https"]`) y pseudoclases estructurales (`:first-child`, `:hover`, `:focus`).
*   **Flexbox Layout:** Control absoluto de layouts bidimensionales y unidimensionales flexibles en la barra de navegación, la cuadrícula de habilidades (`flex-wrap`) y la galería responsiva de proyectos.
*   **Z-Index y Contexto de Apilamiento:** Fijación de la cabecera mediante `position: sticky` administrando capas con `z-index` para evitar superposiciones no deseadas.
*   **Diseño Responsivo Empleando Breakpoints:** Estilos por defecto adaptados a dispositivos móviles de 320px a 767px, con escalabilidad controlada mediante Media Queries a 768px (Tablets), 1024px (Desktop) y 1440px (Pantallas grandes).

---

## Estructura de Archivos del Entregable

```text
portafolio/
├── index.html
├── style.css
├── images/
│   ├── progra.jpg
│   ├── yo.jpeg
│   ├── clinica.jpg
│   ├── inventario.jpg
│   └── tec
