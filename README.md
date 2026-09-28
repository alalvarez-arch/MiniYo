# MiniYo — paquete para GitHub Pages

Sube **el contenido de esta carpeta** (no la carpeta en sí) a la raíz del repo
https://github.com/alalvarez-arch/MiniYo  rama `main`.

## Cómo publicarlo

1. En GitHub: repo → Add file → Upload files.
2. Arrastra a la raíz: `index.html`, `sw.js`, `manifest.webmanifest`, `.nojekyll`, `README.md`, carpeta `img/` y carpeta `icons/`.
3. Commit a `main`.
4. Settings → Pages → Deploy from branch **main** / **/** (root).
5. En el móvil: recarga forzada. El service worker es **v12** y tira el caché viejo que devolvía 404.

URL: https://alalvarez-arch.github.io/MiniYo/

## Qué hay

- 6 caricaturas (hombre/mujer × tierno/serio/malote). Apariencia y personalidad se eligen por separado.
- Sitio: ciudad / pueblo / ciudad costera, cada uno con fondo y animación.
- Mascotas: varios perros y gatos; nombre, peso, raza, color, collar o pañuelo; cuidados (vet, comida, pastillas). Se ven a los pies del miniyo (el perro ladra, el gato araña).
- Casa, vehículo y trabajo con cuestionario.
- Listas + chat para apuntar / borrar / cambiar.
- PWA: `manifest.webmanifest` + `sw.js` (cache v12).
- `.nojekyll` para que Pages no pase por Jekyll.

Toca el nombre del sitio o el sello del día para volver al test inicial.
