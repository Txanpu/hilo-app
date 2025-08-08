# Contador Hi‑Lo — PWA iPhone de Txanpu

Esto es una **Web App instalable** (PWA) basada en tu `Contador_HiLo_LIMPIO.html`.
Funciona en iPhone incluso **offline** una vez instalada.

## Cómo publicarla (opción rápida sin código)
1) Sube esta carpeta a **GitHub** en un repositorio público.
2) Activa **GitHub Pages** con la rama `main` y carpeta `/` (root).
3) Tu app quedará en una URL HTTPS. Ejemplo: 


## Instalar en iPhone
1) Abre el enlace en **Safari**.
2) Pulsa el botón **Compartir** → **Añadir a pantalla de inicio**.
3) Se instala como app. Ya puedes abrirla desde el icono. Funciona offline.

## Enviar por WhatsApp
No se puede “adjuntar una app” para que se ejecute dentro de WhatsApp en iOS.
Lo correcto es **enviar el enlace** (URL) de la app. Tus contactos abren el enlace
en Safari y tocan “Añadir a pantalla de inicio”.

## Archivos
- `index.html` — tu app con metaetiquetas iOS y registro del Service Worker.
- `manifest.webmanifest` — nombre, iconos y colores de la PWA.
- `sw.js` — caché offline básica (cache-first).
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — iconos.

> Nota iOS: Las PWAs requieren **HTTPS** y abrirse en **Safari** para “Añadir a pantalla de inicio”.
