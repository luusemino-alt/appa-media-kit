# ¡appa! Media Kit

Web estática del Media Kit de ¡appa! ADS: audiencia, simulador de formatos, medidas de piezas y ecosistema.

- `index.html`, `styles.css`, `app.js`: la web (sin dependencias ni build).
- `assets/`: logos, íconos y capturas de la app.
- Las medidas oficiales están en `app.js` (`FORMATS` y `SOCIAL`).

## Publicar en Netlify
1. En Netlify: **Add new site → Import an existing project → GitHub** y elegí este repo.
2. Build command: vacío. Publish directory: `.` (ya está en `netlify.toml`).
3. Deploy. Cada cambio que se suba a `main` se publica solo.
