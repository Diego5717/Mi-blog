# Mi Blog de Física

Blog hecho con [Quarto](https://quarto.org). Escribes en Markdown, el código
Python se ejecuta solo al renderizar, y se publica en GitHub Pages.

## Requisitos (una sola vez)
1. Instala Quarto: https://quarto.org/docs/get-started/
2. Instala Python y las dependencias:  `pip install -r requirements.txt`

## Trabajar localmente
    quarto preview        # abre el blog en tu navegador y se actualiza solo

## Crear una entrada nueva
Crea una carpeta dentro de `posts/` con un `index.qmd` adentro. Copia el
front-matter de un post existente como plantilla.

## Publicar en GitHub Pages
    quarto publish gh-pages

Tu blog quedará en: https://TU_USUARIO.github.io/mi-blog
