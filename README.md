# Для Marina 💗 — mini juegos

Sitio web con mini juegos (Tetris, memorama, atrapa corazones, palabras cálidas), en ruso y español.

## Estructura del repo (todo en la raíz, sin carpetas)

```
index.html       ← versión en ruso (se abre por defecto)
index-es.html    ← versión en español
.gitignore
README.md
```

## Cómo subirlo a GitHub Pages (sin usar terminal ni carpetas)

1. Entra a https://github.com/new y crea un repositorio nuevo (puede ser público o privado). Ponle el nombre que quieras, ej. `marina-games`.
2. En la página del repo recién creado, click en **"uploading an existing file"** (o el botón "Add file" → "Upload files").
3. Arrastra `index.html`, `index-es.html` y `README.md` directo ahí — todos sueltos, sin meterlos en ninguna carpeta.
4. Abajo, click **"Commit changes"**.
5. Ve a **Settings** (arriba en el repo) → en el menú lateral **Pages**.
6. En "Branch" selecciona `main` y carpeta `/ (root)` → **Save**.
7. Espera 1-2 minutos y recarga esa misma página de Settings → Pages. Ahí te va a aparecer el link, algo como:
   `https://tu-usuario.github.io/marina-games/`

Ese link ya sirve para mandárselo a Marina. Como el archivo se llama `index.html`, carga automático al entrar.

## Si luego quieres actualizarlo

Mismo proceso: entra al repo → "Add file" → "Upload files" → subes la nueva versión del archivo (mismo nombre) → Commit. GitHub lo sobreescribe y el link se actualiza solo, sin que tengas que tocar nada en Settings de nuevo.
