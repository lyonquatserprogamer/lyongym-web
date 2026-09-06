# Gimnasio LyonGym — Sitio estático

Sitio mínimo para publicar en GitHub Pages.

Cómo publicar en GitHub Pages (rápido):

1. Crear un repositorio en GitHub y subir estos archivos (o `git init` + `git add .` + `git commit`).
2. `git remote add origin <url-del-repo>`
3. `git push -u origin main`
4. En la configuración del repositorio (Settings) > Pages, seleccionar la rama `main` y la carpeta `/ (root)`.

Alternativa con `gh` (GitHub CLI):

```bash
git init
gh repo create mi-usuario/mi-repo --public --source=. --remote=origin
git add .
git commit -m "Sitio inicial"
git push -u origin main
```

Reemplaza el teléfono y la dirección en `index.html` por los datos reales del local.
