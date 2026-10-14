# ¡appa! Media Kit

Web estática del Media Kit de ¡appa! ADS: audiencia, simulador de formatos con campañas reales, medidas de piezas y ecosistema.

**Link público:** https://luusemino-alt.github.io/appa-media-kit/

- `index.html`, `styles.css`, `app.js`: la web (sin dependencias ni build). Funciona en compu y en celular.
- `assets/`: logos, íconos, capturas de la app y piezas reales de marcas.
- Las medidas oficiales están en `app.js` (`FORMATS` y `SOCIAL`).

## Publicación
Se publica con GitHub Pages desde la rama `gh-pages`. Para actualizar la web, subir los cambios a `main` y copiarlos a `gh-pages`:

```
git push origin main
git push origin main:gh-pages
```

También está lista para Netlify (`netlify.toml`, publish directory `.`) si en algún momento se quiere usar un dominio de Netlify.
