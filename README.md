# ZeroWaste

App web móvil para organizar la despensa familiar, evitar el desperdicio de alimentos y planificar un menú semanal adaptado a condiciones médicas (ODS 2 y ODS 3).

**Usar la app:** https://pipesco7.github.io/zerowaste/

## Instalar en iPhone
1. Abre el enlace en **Safari**.
2. Toca **Compartir** → **Agregar a pantalla de inicio**.
3. La primera vez que escanees, acepta el permiso de cámara.

## Archivos
- `index.html`: la app completa (HTML, CSS y JavaScript en un solo archivo). Los datos se guardan solo en el teléfono (localStorage).
- `manifest.webmanifest` e `icon-*.png`: ícono y configuración para abrirla como app.

## Base de productos propia
En **Perfil → Base de productos** se puede importar una planilla CSV con las columnas
`codigo, nombre, marca, cantidad, unidad, categoria, ubicacion` (solo `codigo` y `nombre` son obligatorias).
