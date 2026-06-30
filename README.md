# Anclora Insights

Repositorio contenedor del sello editorial digital de Anclora Group.

## Organización

- `brand/`: identidad visual compartida del sello.
- `products/`: fuentes, recursos y entregables de cada producto.
- `shopify-themes/`: espacio local para temas Shopify, cada uno con su propio repositorio Git.
- `archive/`: versiones anteriores conservadas solo como referencia.

Cada producto usa un slug estable y separa sus archivos por plataforma. Los temas Shopify no
forman parte del historial Git de este repositorio: se versionan de forma independiente y se
conectan desde su propio repositorio de GitHub a Shopify.

## Productos

| Producto | Estado | Plataformas |
| --- | --- | --- |
| [Éxito sin compañía](products/exito-sin-compania/README.md) | Publicado | Shopify, Amazon KDP |

## Repositorios Git

Este directorio es el repositorio contenedor `anclora-insights`. Cada carpeta situada bajo
`shopify-themes/` es otro repositorio, con historial y remoto propios.

Cuando el repositorio remoto de un tema exista en GitHub, puede añadirse al contenedor como
submódulo. Hasta entonces permanece ignorado por el repositorio raíz para impedir que sus
archivos entren accidentalmente en el historial del sello.

