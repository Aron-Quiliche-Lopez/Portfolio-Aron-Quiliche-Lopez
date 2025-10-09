# Portafolio Profesional (Template)
**Idioma:** Español  
**Autor:** Aron Alexander Quiliche López

Este repositorio contiene una plantilla lista para publicar en **GitHub Pages**. Incluye:
- `index.html` (presentación, habilidades, proyectos destacados, contacto)
- `projects.html` (detalle de proyectos con objetivos, tecnologías y reflexión)
- `assets/css/style.css` (estilos limpios y responsivos)
- `assets/img/placeholder_*.svg` (miniaturas de ejemplo)

## Cómo publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo: `portfolio`.
2. Sube todos los archivos de esta carpeta al repositorio.
3. En GitHub, ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Source: Deploy from a branch**.
5. Selecciona la rama **main** y la carpeta **/** (root). Guarda.
6. Espera a que GitHub cree el sitio. La URL será: `https://<tu-usuario>.github.io/portfolio/`.

### Subir con línea de comandos
```bash
git init
git add .
git commit -m "Portafolio inicial"
git branch -M main
git remote add origin https://github.com/<tu-usuario>/portfolio.git
git push -u origin main
```

### Personalización rápida
- Reemplaza textos de ejemplo con tu información real.
- Sustituye imágenes en `assets/img`.
- Agrega enlaces reales a tus repositorios en la sección “Código fuente”.

¡Éxito en tu presentación!
