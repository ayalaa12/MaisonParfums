# Maison Parfums — Sitio HTML completo

Versión funcional y autónoma de la boutique digital Maison Parfums.

## Qué incluye

- 201 fragancias únicas: 96 para Hombre, 96 para Mujer y 9 Unisex.
- 70 perfumes Árabes, 61 Nicho y 70 de Diseñador.
- Catálogo dinámico con búsqueda, filtros y ordenamiento.
- Fichas con notas, acordes y barras de intensidad, duración y proyección.
- Inicio editorial con imágenes por categoría, colecciones y carrusel de cinco dúos interactivos.
- Páginas de Hombre, Mujer y Unisex con tarjetas visuales, descripción y revelado al pasar el cursor o tocar en celular.
- Wishlist y carrito guardados en el navegador.
- Envío gratuito desde $2,000 MXN, visible en carrito y proceso de pago.
- Quiz de recomendación con selección exacta de tres notas.
- Compra como invitado y selección visual de Visa, Mastercard o PayPal.
- Newsletter, contacto, preguntas frecuentes y políticas.
- Diseño responsive para celular, tableta y computadora.

## Cómo abrirlo

1. Descarga y descomprime el ZIP.
2. Abre el `index.html` ubicado junto a `LEEME-PRIMERO.txt`.
3. También puedes abrir `ABRIR-SIN-DEPENDENCIAS.html` dentro de esta carpeta.
4. No necesitas instalar programas ni iniciar un servidor.

## Proyecto editable

El archivo de entrada editable es `index.html` y utiliza:

- `css/styles.css`
- `js/app.js`
- `data/productos.json`
- `data/productos-local.js`
- `data/site-data.json`
- `data/catalogo-maestro.csv`

## Imágenes

Las fotografías de producto se encuentran en:

`assets/images/catalogo/<marca>/<Nombre del perfume>.webp`

Las imágenes editoriales del inicio se encuentran en:

- `assets/images/home/`
- `assets/images/categories/`
- `assets/images/collections/`
- `assets/images/genders/`

Para reemplazar una fotografía de producto, conserva el mismo nombre y ruta del archivo. Consulta también `IMAGENES-LEEME.md`.

## Carrito, wishlist y cuenta

La selección se conserva mediante `localStorage` en el dispositivo. El código de bienvenida es `MAISON15`.

## Cómo revisar la versión móvil

1. Abre el sitio en Google Chrome.
2. Presiona `F12`.
3. Selecciona el icono de teléfono y tableta.
4. Prueba anchos como 390 px, 768 px y 1440 px.

## Publicación

La carpeta puede publicarse en GitHub Pages, Netlify o Cloudflare Pages conservando toda la estructura de archivos.

## Auditoría del catálogo

- Total: 201.
- Hombre: 96.
- Mujer: 96.
- Unisex: 9.
- Árabes: 70.
- Nicho: 61.
- Diseñador: 70.
- SKU únicos: 201.
- Slugs únicos: 201.
