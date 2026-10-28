# Plantilla de landing page

Plantilla de una página para empresas: cabecera, propuesta de valor, funciones (`#features`), testimonios (`#testimonials`) y contacto (`#contact`).

## Tecnología

HTML estático con Tailwind CSS por CDN. No necesita compilación.

## Cómo adaptarla

1. Reemplaza los marcadores `[Enterprise Name]` y `[Enterprise Logo]` en `index.html`.
2. Cambia la paleta `brand` en la configuración de Tailwind, al inicio de `index.html`.
3. Ajusta textos, testimonios y datos de contacto.

## Ver en local

```bash
python -m http.server 8000
# abre http://localhost:8000
```

Se puede publicar tal cual en GitHub Pages, Netlify o Vercel.
