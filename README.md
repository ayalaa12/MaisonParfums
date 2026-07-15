# Maison Parfums — Sitio HTML completo

Versión funcional y autónoma del proyecto universitario Maison Parfums.

## Qué incluye

- 210 productos exactos.
- 105 productos para Hombre.
- 105 productos para Mujer.
- 35 productos por categoría y género.
- Perfumes árabes, nicho y de diseñador.
- 7 marcas por categoría y 5 productos por marca.
- Inicio editorial.
- Catálogo dinámico con filtros y ordenamiento.
- Buscador de perfumes, marcas y notas.
- Páginas dinámicas de género, marca, categoría, producto y colección.
- Wishlist y carrito guardados en el navegador.
- Código demostrativo `MAISON15`.
- Quiz de recomendación.
- Cuenta simulada y compra como invitado.
- Checkout demostrativo con Visa, Mastercard y PayPal como opciones visuales.
- Newsletter simulada.
- Contacto, FAQ, políticas, privacidad, términos y página 404.
- Auditoría interna del catálogo.
- Diseño responsive.

## Cómo abrirlo

1. Descarga y descomprime `maison-parfums-completo.zip`.
2. Entra a la carpeta `maison-parfums-completo`.
3. Haz doble clic en `index.html`.
4. No necesitas instalar programas ni iniciar un servidor.

## Archivo principal

`index.html`

## Datos del catálogo

La fuente maestra es:

`data/productos.json`

Para permitir la apertura local mediante doble clic se incluye una copia técnica:

`data/productos-local.js`

También se incluye:

`data/catalogo-maestro.csv`

## Imágenes

Las 210 imágenes actuales son marcadores SVG locales generados para la demostración:

`assets/images/products/`

No representan el frasco o empaque oficial.

Para reemplazar una imagen:

1. Guarda la fotografía en `assets/images/products/`.
2. Se recomienda formato WebP.
3. Cambia `url_imagen_principal` en `data/productos.json`.
4. Regenera o actualiza `data/productos-local.js`.

## Precios y datos olfativos

Los precios son ficticios y están expresados en MXN con IVA incluido.

Las presentaciones, concentraciones, notas, duración y proyección se generaron como datos provisionales para que la web sea funcional. Cada producto muestra una advertencia de verificación.

## Carrito y wishlist

Se guardan mediante `localStorage`. Para borrar todos los datos puedes limpiar el almacenamiento del sitio desde las herramientas del navegador.

Código de descuento demostrativo:

`MAISON15`

## Pagos

La web no procesa pagos reales ni solicita números de tarjeta. Visa, Mastercard y PayPal son únicamente opciones visuales del checkout académico.

## WhatsApp

Busca el marcador:

`[AGREGAR NÚMERO DE WHATSAPP]`

Reemplázalo cuando exista el número final.

## Cómo revisar la versión móvil

1. Abre el sitio en Google Chrome.
2. Presiona `F12`.
3. Selecciona el icono de teléfono y tableta.
4. Prueba anchos como 390 px, 768 px y 1440 px.

## Publicación gratuita

La carpeta puede publicarse en GitHub Pages, Netlify o Cloudflare Pages. Debes subir todos los archivos conservando la estructura.

## Migración posterior a Wix

1. Usa `data/productos.json` o `data/catalogo-maestro.csv` como tabla maestra.
2. Adapta los campos comerciales a la plantilla vigente de Wix Stores.
3. Conserva notas, quiz y atributos ampliados en Wix CMS.
4. Reproduce la identidad visual de `css/styles.css`.
5. Activa pagos reales únicamente con un plan compatible.

## Auditoría

- Total: 210.
- Hombre: 105.
- Mujer: 105.
- Hombre Árabes: 35.
- Hombre Nicho: 35.
- Hombre Diseñador: 35.
- Mujer Árabes: 35.
- Mujer Nicho: 35.
- Mujer Diseñador: 35.
- SKU únicos: 210.
- Slugs únicos: 210.


## Imágenes centralizadas

Consulta `IMAGENES-LEEME.md`. Reemplazar un único archivo WebP actualiza todas las apariciones del perfume.
