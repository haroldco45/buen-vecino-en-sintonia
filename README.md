# Buen Vecino en Sintonía

Página de promoción del programa de convivencia ciudadana de **Radio Policía Nacional Caucasia**, con el apoyo de la app [Buen Vecino Bajo Cauca](https://buen-vecino-bajo-cauca.netlify.app/).

Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados.

## Publicar en GitHub Pages

1. Cree el repositorio `haroldco45/buen-vecino-en-sintonia`.
2. Suba todos los archivos de esta carpeta a la raíz de la rama `main`.
3. Settings → Pages → Source: `main` / `(root)`.
4. Queda en `https://haroldco45.github.io/buen-vecino-en-sintonia/`.

Si lo conecta a Netlify, cambie `og:url`, `og:image`, `twitter:image` y `CONFIG.sitio` en `index.html` por la dirección de Netlify.

## Datos que debe completar (index.html, bloque CONFIG)

- `horario`: días y hora confirmados por la emisora (ej. "Martes y viernes · 6:30 p. m.").
- `frecuencia`: frecuencia de la emisora en Caucasia (vacío = no se muestra).
- `whatsapp`: número que recibe la participación de los oyentes (hoy: 3117700431).

## Actualizaciones

- Si cambia el contenido, suba la versión del service worker en `sw.js` (`buen-vecino-sintonia-v1` → `v2`).
- Si cambia la imagen de vista previa, suba `?v=1` a `?v=2` en las etiquetas `og:image` y `twitter:image`.
- WhatsApp guarda en caché la vista previa por enlace: al compartir después de un cambio, agregue `?v=2` al final de la dirección.
- Los valores de multas son de 2026 (salario mínimo $1.750.905). Actualícelos en enero.
