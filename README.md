# OPERADORES PRO — Temporada 2026–2027

Aplicación web instalable para Windows (Edge/Chrome) e iPhone (Safari). Se publica desde GitHub Pages y, tras la primera carga, permite el uso sin conexión.

## Funciones
- 12 operadores iniciales, gestión de operadores, edición, desactivación y eliminación de quienes no tengan evaluaciones
- Evaluación por cargo con seis competencias, barras de 1–5, compromiso y responsabilidad
- Nota mínima de aprobación de 4,0/5
- Historial e informes individuales guardables como PDF mediante **Imprimir → Guardar como PDF**
- Ajustes de apariencia con seis temas de colores dobles, colores personalizados y restauración
- Respaldo e importación JSON

## Publicar en GitHub Pages
1. Descomprimir el ZIP. Subir **el contenido** de esta carpeta a la raíz del repositorio. Deben quedar `index.html`, `manifest.webmanifest`, `sw.js` y `icons/` en la raíz.
2. Repositorio → Settings → Pages → Deploy from a branch → main → / (root) → Save.
3. Abrir la URL publicada bajo HTTPS. Para instalar en iPhone: Safari → Compartir → Añadir a pantalla de inicio. En Windows: Edge/Chrome → Instalar aplicación.

**Privacidad:** La información queda en `localStorage` del dispositivo/navegador. No se sincroniza entre equipos; exporta respaldos con regularidad. No subas registros reales, respaldos ni PDFs personales al repositorio GitHub. La impresión debe seleccionarse como «Guardar como PDF», no se crea el PDF en un servidor.
