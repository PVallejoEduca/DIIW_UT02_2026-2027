# Contenido accesible

## Imágenes

El atributo `alt` comunica la función o información relevante de una imagen. Si es decorativa, se usa `alt=""`. Una imagen compleja necesita una descripción equivalente cercana. El texto alternativo depende del contexto, no solo de los píxeles.

## Audio y vídeo

El vídeo con voz necesita subtítulos sincronizados; el contenido solo sonoro, una transcripción. Cuando la información visual no se deduce del audio, se proporciona audiodescripción o alternativa equivalente. Los controles deben funcionar con teclado.

## Color y contraste

El color no debe ser la única señal de error, estado o selección. El contraste se evalúa entre texto y fondo y también en componentes e indicadores de foco. Se comprueba tanto el estado normal como interacción, error y deshabilitado.

## Texto y lenguaje

Conviene usar frases directas, títulos informativos, enlaces cuyo propósito se entienda en contexto y siglas explicadas. La alineación, anchura de línea, espaciado y posibilidad de zoom afectan a la legibilidad.

## Movimiento

Las animaciones automáticas deben poder detenerse cuando corresponda. Se respeta `prefers-reduced-motion` y se evitan flashes que puedan provocar reacciones físicas.
