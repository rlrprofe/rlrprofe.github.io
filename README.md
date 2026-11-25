# rlrprofe.github.io · Home de los cursos

Página de inicio de `https://rlrprofe.github.io/`, con una tarjeta por cada curso. Creada con MkDocs Material.

> Este repositorio **debe llamarse exactamente `rlrprofe.github.io`** para que GitHub lo sirva en la raíz.

## Añadir un curso

Edita `docs/index.md`: copia una tarjeta (el bloque que empieza por `-   :material-...`), pégala antes de `</div>` y cambia icono, título, descripción y enlace. Al hacer `push` a `main` se publica solo.

## Puesta en marcha

```powershell
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Visita `http://127.0.0.1:8000/`.

## Publicación

El workflow `.github/workflows/deploy.yml` construye el sitio y lo publica en la rama `gh-pages` con cada `push` a `main`.

Solo la primera vez, en GitHub: **Settings → Pages → Source: Deploy from a branch → `gh-pages` / `(root)`**.

## Nota

Los cursos (`/git-github/`, `/AD-2627/`, `/poo/`...) son repositorios independientes y se publican en sus propias rutas; **no hay que copiarlos aquí**. Esta página solo enlaza a ellos.
