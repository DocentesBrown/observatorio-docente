# Observatorio de Precios - Docentes Brown

Herramienta autogestiva para visualizar el poder adquisitivo docente en base a una canasta básica de 40 productos indispensables.

## 📊 Gestión de Datos (Google Sheets)
La aplicación consume los precios en tiempo real desde una hoja de cálculo.

### Estructura de la Hoja
La hoja debe contener 4 columnas obligatorias en este orden:
1.  **producto**: Nombre del artículo (ej: Leche).
2.  **marca**: Detalle y medida (ej: La Serenísima 1L).
3.  **precio**: Número sin símbolos (ej: 1250.50).
4.  **categoria**: Rubro (ej: Lácteos).

### Cómo actualizar precios
1. Abre el Google Sheet vinculado.
2. Modifica los valores en la columna **C (precio)**.
3. Los cambios se reflejarán automáticamente en la app al recargar (Google puede tardar hasta 5 min en refrescar el CSV público).

### Publicación
Para obtener el enlace:
`Archivo > Compartir > Publicar en la Web > [Seleccionar Hoja] > Formato CSV`.

## 🛠️ Tecnologías
- HTML5 / CSS3 (Variables CSS, Flexbox, Grid)
- JavaScript Vanilla (Fetch API, Async/Await)
- Google Sheets como DB NoSQL.
