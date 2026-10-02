# Instrumento Visual - Flow Field

Experiencia audiovisual interactiva basada en p5.js. La aplicación está separada
en archivos estáticos para facilitar su mantenimiento y publicación:

- `index.html`: estructura de la interfaz y controles, y entrada de GitHub Pages.
- `styles.css`: estilos de la interfaz.
- `sketch.js`: lógica p5.js, interacción, audio y pista embebida.

## Ejecutar localmente

Abre `index.html` en un navegador moderno. Para que la carga de audio funcione
correctamente en todos los navegadores, es recomendable servir la carpeta con
un servidor HTTP local.

## Publicar con GitHub Actions

El workflow `.github/workflows/deploy-pages.yml` despliega automáticamente el
contenido a GitHub Pages cada vez que se hace push a `main`. También puede
ejecutarse manualmente desde la pestaña **Actions**.

En el repositorio, selecciona **Settings > Pages > Source: GitHub Actions**.
Después de completar el primer workflow, la URL publicada aparecerá en la
salida del job **Deploy to GitHub Pages**.
