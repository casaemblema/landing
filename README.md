# Casa Emblema — Landing

Archivos estáticos para publicar en **GitHub Pages**.

## Estructura
- `index.html` — página principal
- `style.css` — estilos del sitio
- `assets/logo_casa_emblema.png` — logo (versión fondo negro)
- `assets/favicon.ico` — ícono del sitio

## Cómo publicar en GitHub Pages
1. Sube estos archivos al repositorio (rama `main`).
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Branch: `main` — Folder: `/ (root)` → **Save**.
5. Abre la URL que te muestre GitHub (por ejemplo: `https://casaemblema.github.io/landing/`).

## Formulario (FormSubmit)
En `index.html`, busca el atributo `action` del formulario y **reemplaza**:
```
https://formsubmit.co/REEMPLAZA_TU_CORREO@ejemplo.com
```
por tu correo real (ej. `hola@casaemblema.com`).

Opcional: cambia `_next` por la URL final de tu sitio para redirigir tras envío.
