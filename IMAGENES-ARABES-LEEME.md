# Imágenes árabes completas

La categoría Árabes ya contiene 70 imágenes reales:

- 35 para Hombre.
- 35 para Mujer.
- 7 marcas por género.
- 5 productos por marca.

## Sistema central

Cada combinación de marca y perfume utiliza un solo archivo:

`assets/images/catalogo/<marca>/<Nombre del perfume>.webp`

Ejemplo:

`assets/images/catalogo/afnan/9PM.webp`

La imagen se reutiliza automáticamente en:

- Inicio.
- Catálogo.
- Buscador.
- Categorías.
- Marca.
- Colecciones.
- Quiz.
- Wishlist.
- Carrito.
- Ficha individual.
- Productos relacionados.

## Cómo reemplazar una imagen

1. Prepara la nueva foto en WebP.
2. Utiliza exactamente el mismo nombre del archivo.
3. Sustituye el archivo dentro de `assets/images/catalogo/`.
4. Actualiza con `Ctrl + F5`.

No es necesario editar HTML, JavaScript o JSON.

## Index autónomo

El `index.html` de la carpeta superior es una versión congelada y autónoma.
Cuando cambies imágenes en la carpeta editable, debe regenerarse el index autónomo
para incorporar esos cambios.
