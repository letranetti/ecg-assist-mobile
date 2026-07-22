# ECG Assist Mobile

Paquete instalable como aplicación web progresiva (PWA).

## Contenido

- index.html
- manifest.webmanifest
- service-worker.js
- icons/

## Importante

No basta con abrir index.html directamente desde el gestor de archivos.
Para que Android permita instalarla y usar la cámara correctamente, debe publicarse
en una dirección HTTPS o abrirse desde localhost durante pruebas.

## Instalación recomendada

Publica esta carpeta en GitHub Pages, Netlify, Cloudflare Pages o cualquier alojamiento HTTPS.
Después abre la URL en Chrome para Android y usa:

Menú ⋮ > Instalar aplicación

o:

Menú ⋮ > Añadir a pantalla de inicio

La aplicación quedará disponible con icono propio y podrá funcionar sin conexión
después de la primera carga.
