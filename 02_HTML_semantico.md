# HTML semántico

HTML semántico describe el significado y la estructura del contenido. Los navegadores exponen esa estructura a las tecnologías de apoyo y permiten navegar por encabezados, regiones, listas, tablas y controles.

## Estructura de página

```html
<header>...</header>
<nav aria-label="Principal">...</nav>
<main>
  <article>
    <h1>Título de la página</h1>
    ...
  </article>
</main>
<footer>...</footer>
```

Los encabezados representan una jerarquía, no un tamaño visual. Cada página debe tener un título principal descriptivo y subsecciones ordenadas.

## Elementos nativos antes que ARIA

Un `<button>` ya incluye semántica, foco y activación mediante teclado. Un `<div>` con apariencia de botón no. La primera regla práctica de ARIA es no usarla si un elemento HTML nativo resuelve el caso.

## Aspectos clave

- Definir un `<title>` útil y el idioma con `lang`.
- Usar enlaces para navegar y botones para ejecutar acciones.
- Asociar cada campo con su `<label>`.
- Emplear listas y tablas solo cuando la relación de los datos lo requiera.
- Conservar un orden del DOM coherente con el orden visual.
- No ocultar el foco ni depender únicamente del color.

ARIA complementa la semántica cuando se construyen widgets que HTML no ofrece; no repara interacciones incompletas por sí sola.
