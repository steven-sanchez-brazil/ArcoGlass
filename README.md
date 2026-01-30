# ArcoGlass

Landing page moderna para Arco Glass construida con Astro.

## Requisitos
- Node.js 18+

## Desarrollo

```bash
npm install
npm run dev
```

Abre `http://localhost:4321` para ver el sitio.

## Producción

```bash
npm run build
npm run preview
```

## Deploy en GitHub Pages

El flujo de GitHub Actions ubicado en `.github/workflows/gh-pages.yml` genera el build y publica el sitio en GitHub Pages
al hacer push a la rama `main`. El workflow configura automáticamente `SITE_URL` y `BASE_PATH` para que Astro exporte el
sitio bajo la ruta del repositorio.

This repository contains a simple landing page for the Arco Glass company. The page showcases our products and services, with sections for contact information. The "Contact Us" section now includes a basic contact form.


Open `index.html` in your browser to view the landing page.
