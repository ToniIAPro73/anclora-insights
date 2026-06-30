# Temas Shopify

Cada subcarpeta de este directorio debe ser un repositorio Git independiente, asociado a un
único tema de la tienda y normalmente a un producto editorial.

## Flujo recomendado

1. Trabajar y confirmar cambios dentro del repositorio del tema.
2. Publicarlo en un repositorio privado de GitHub.
3. En Shopify, abrir **Tienda online → Temas → Añadir tema → Conectar desde GitHub**.
4. Seleccionar el repositorio y la rama de publicación del tema.
5. Mantener el ZIP de importación manual en `products/<producto>/publishing/shopify/theme-packages/`.

No se debe ejecutar `git add` desde el repositorio contenedor sobre el contenido de un tema.
Cuando exista su remoto, la integración correcta con el contenedor es un submódulo Git.

