# Piano 6 — PWA

Piano táctil web de seis octavas (MIDI 36–107, Do2–Si7), pensado para Android.

## Cómo verlo
Abre `index.html` en un navegador para una vista previa. Para instalar como PWA y habilitar funcionamiento sin conexión, debe publicarse en HTTPS (por ejemplo, GitHub Pages) y abrirse con Chrome.

## Publicar gratis con GitHub Pages
1. Crea un repositorio en GitHub y sube los archivos de esta carpeta a la raíz.
2. En Settings → Pages, activa publicación desde la rama `main`, carpeta `/root`.
3. Abre la URL HTTPS que GitHub Pages te proporciona en Chrome Android.
4. Menú ⋮ → **Instalar aplicación** o **Añadir a pantalla de inicio**.

La primera visita necesita Internet para descargar la app. Después, el service worker guarda los archivos para abrirla offline.

## Estado del sonido
Este prototipo usa síntesis Web Audio con armónicos. Para sonido acústico limpio y realista, se debe integrar un banco de muestras de piano con licencia compatible. Este proyecto no incluye muestras comerciales.
