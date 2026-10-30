# Anillos de Graduación JORVIC

Sitio estático de anillosgraduacionjorvic.com. Sin build: Vercel sirve los archivos tal cual.

- `index.html` — la página completa (estilos y script incluidos)
- `assets/logo-blanco.png` — logo blanco para fondos verdes
- `assets/fotos/` — fotos de productos en .webp (máx. 1200 px). Para cambiar una foto, reemplaza el archivo con el mismo nombre.
- `vercel.json` — redirige las URLs viejas de WordPress (`/inicio/...`) a la página nueva

## Vercel
New Project → importar este repo → Framework Preset: **Other** → sin build command → Deploy.
Luego en Settings → Domains agrega `anillosgraduacionjorvic.com` y `www.anillosgraduacionjorvic.com`.
