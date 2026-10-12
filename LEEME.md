# Llegó Farma · Onepage (llegofarma.cl)

Sitio estático en HTML, CSS y JavaScript, sin dependencias ni compilación. Los pasos completos para publicar se agregan en la entrega final (14.10).

## Estructura
- `index.html`: la página.
- `privacidad.html`: Política de Privacidad y Datos de Llegó con la gráfica de Llegó Farma.
- `css/`: `fuentes.css`, `base.css` (tokens, tipografía, retícula), `componentes.css`, `secciones.css`, `movimiento.css`, `transicion.css` (cambio entre páginas), `privacidad.css` y los tamaños (`celular.css`, `tablet.css`, `notebook.css`, `grande.css`).
- `js/`: `main.js` (header, scroll a secciones, ruta de tecnología, cifras, formulario, transición entre páginas) y `movimiento.js` (capas de animación).
- `fonts/`: Manrope y LF Mono (JetBrains Mono con el cero sin punto). Licencia en `fonts/LICENCIA-FUENTES.txt`.
- `img/`: `logos/` (Llegó Farma e íconos), `fotos/`, `clientes/` (logos en blanco), `og/compartir.jpg` (imagen para compartir, 1200 × 630).

## Formulario
- Se envía con Formspree a `https://formspree.io/f/xrpeaokz` (en `index.html`, atributo `action` del formulario).
- El correo de destino (contacto@llego.cl) se configura en formspree.io, no en el código.
- Para probarlo: completar el formulario en el sitio publicado y revisar que llegue el correo "Nuevo contacto desde llegofarma.cl".

## Medición
No se usa por ahora. El lugar para pegar Google Analytics o el píxel de LinkedIn está comentado en el `<head>` de `index.html`.
