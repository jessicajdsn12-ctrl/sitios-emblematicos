# Sistema de Diseño: Sitios Emblemáticos

## Identidad Visual
- **Inspiración**: Brutalismo elegante (estilo Apple / Endcap.design).
- **Paleta de Colores**:
  - Primary Background: `#d4f279` (Verde Lima)
  - Text & Accents: `#111111` (Negro profundo)
  - Contrast/Footer: `#ffffff` (Blanco)
- **Tipografía**: `Inter`, pesos 400 (cuerpo), 700 (menús/subtítulos) y 900 (Titulares gigantes). Letras muy juntas (letter-spacing negativo).

## Reglas de Layout
- **Estructura**: `max-width: 2000px`, `min-width: 1000px`. Todo el posicionamiento está gestionado estrictamente con CSS Flexbox.
- **Unidades**: Uso de `px` para restricciones de contenedor padre. Uso de `rem` y `%` para padding, gaps, márgenes y tipografía.
- **Imágenes**: Filtro escala de grises en CSS. Deben contar siempre con atributos `alt` descriptivos de los pasajes o monumentos mostrados.
- **Interacciones**: Botón flotante inferior derecho constante y efectos de opacidad `0.3s` en hovers de menú y redes sociales.