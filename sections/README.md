# Sections

One file per section of the mockup, so each can be rebuilt as a Shopify section or theme block.

- Visual reference only. Rebuild in Liquid; do not paste as is. Most styling is inline in each file; shared rules are in `base.css`.
- Fonts: Amaranth (headings) and Montserrat (body). Image paths point to `../../assets/`; replace them with the real image URLs.
- `_shared/` holds sections that are identical on several pages (announcement bar, header, footer, newsletter, FAQ block...). The list of pages is in the file header.
- Files marked **unconfirmed** contain blue text with `por confirmar` or `propuesta`: do not treat that content as final.
- Page folders are named after the page file (for example `navidad` = `navidad.html`). Order inside a folder follows the page from top to bottom.

| Folder | File | Used on | Notes |
|---|---|---|---|
| _shared | `announcement-bar.html` | blog, carrito, componentes, confirmacion, cuenta, envios, faq, index, kitescudo, kitritual, marcas, micuenta, navidad, nosotros, origen, pago, politicas, post, presentacion, producto, productos, reclamaciones, regalo, seguimiento, set |  |
| _shared | `breadcrumb.html` | cuenta, micuenta |  |
| _shared | `cookie-bar.html` | blog, carrito, componentes, confirmacion, cuenta, envios, faq, index, kitescudo, kitritual, marcas, micuenta, navidad, nosotros, origen, pago, politicas, post, presentacion, producto, productos, reclamaciones, regalo, seguimiento, set |  |
| _shared | `footer.html` | blog, carrito, componentes, confirmacion, cuenta, envios, faq, index, kitescudo, kitritual, marcas, micuenta, navidad, nosotros, origen, pago, politicas, post, presentacion, producto, productos, reclamaciones, regalo, seguimiento, set | **unconfirmed** |
| _shared | `header.html` | blog, carrito, componentes, confirmacion, cuenta, envios, faq, kitescudo, kitritual, marcas, micuenta, navidad, nosotros, origen, pago, politicas, post, presentacion, producto, productos, reclamaciones, regalo, seguimiento, set |  |
| _shared | `preguntas-frecuentes.html` | kitescudo, kitritual | **unconfirmed** |
| blog | `01-hero-noticias.html` | blog |  |
| blog | `02-como-llegan-sus-cosmeticos-hasta-el-peru.html` | blog | **unconfirmed** |
| blog | `03-recibe-cada-articulo-en-tu-correo.html` | blog | form |
| carrito | `01-breadcrumb.html` | carrito |  |
| carrito | `02-hero-tu-carrito.html` | carrito |  |
| carrito | `03-resumen.html` | carrito | **unconfirmed** |
| componentes | `01-breadcrumb.html` | componentes |  |
| componentes | `02-componentes-de-la-tienda.html` | componentes | form |
| confirmacion | `01-breadcrumb.html` | confirmacion |  |
| confirmacion | `02-gracias-por-tu-pedido.html` | confirmacion | **unconfirmed** |
| cuenta | `01-hero-ingresa-o-crea-tu-cuenta.html` | cuenta |  |
| cuenta | `02-ya-tengo-cuenta.html` | cuenta | form |
| envios | `01-breadcrumb.html` | envios |  |
| envios | `02-hero-asi-llega-tu-pedido.html` | envios |  |
| envios | `03-paso-a-paso.html` | envios | **unconfirmed** |
| envios | `04-cambios-y-devoluciones.html` | envios |  |
| faq | `01-breadcrumb.html` | faq |  |
| faq | `02-hero-preguntas-frecuentes.html` | faq |  |
| faq | `03-no-encontraste-tu-respuesta.html` | faq | **unconfirmed**, form |
| index | `01-header.html` | index |  |
| index | `02-hero-piel-radiante-directo-desde-corea.html` | index |  |
| index | `03-sets.html` | index | **unconfirmed** |
| index | `04-garantias.html` | index |  |
| index | `05-cupon.html` | index | form |
| index | `06-resenas.html` | index | **unconfirmed** |
| index | `07-envios.html` | index | **unconfirmed** |
| index | `08-marcas.html` | index |  |
| index | `09-proximamente.html` | index | **unconfirmed** |
| index | `10-club.html` | index | **unconfirmed** |
| index | `11-se-el-primero-en-enterarte.html` | index | form |
| kitescudo | `01-breadcrumb.html` | kitescudo |  |
| kitescudo | `02-hero-kit-escudo-andino.html` | kitescudo | **unconfirmed** |
| kitescudo | `03-que-incluye.html` | kitescudo |  |
| kitescudo | `04-modo-de-uso.html` | kitescudo | **unconfirmed** |
| kitescudo | `05-tambien-te-puede-gustar.html` | kitescudo |  |
| kitritual | `01-breadcrumb.html` | kitritual |  |
| kitritual | `02-hero-kit-ritual-coreano.html` | kitritual | **unconfirmed** |
| kitritual | `03-que-incluye.html` | kitritual |  |
| kitritual | `04-modo-de-uso.html` | kitritual | **unconfirmed** |
| kitritual | `05-tambien-te-puede-gustar.html` | kitritual |  |
| marcas | `01-breadcrumb.html` | marcas |  |
| marcas | `02-hero-dos-marcas-un-mismo-cuidado.html` | marcas |  |
| marcas | `03-nolahour.html` | marcas | **unconfirmed** |
| marcas | `04-i-m-sorry-for-my-skin.html` | marcas | **unconfirmed** |
| marcas | `05-que-marca-quieres-ver-en-kory.html` | marcas | **unconfirmed**, form |
| micuenta | `01-hola-sarang.html` | micuenta | **unconfirmed** |
| navidad | `01-hero-paquetes-de-navidad-kory.html` | navidad | **unconfirmed** |
| navidad | `02-borrador-los-nombres-los-tex.html` | navidad | **unconfirmed** |
| navidad | `03-seleccion-tras-probar-muestras.html` | navidad |  |
| navidad | `04-p1.html` | navidad | **unconfirmed** |
| navidad | `05-p2.html` | navidad | **unconfirmed** |
| navidad | `06-precauciones.html` | navidad | **unconfirmed** |
| nosotros | `01-breadcrumb.html` | nosotros |  |
| nosotros | `02-hero-skincare-coreano-pensado-para-peru.html` | nosotros |  |
| nosotros | `03-nuestra-historia.html` | nosotros | **unconfirmed** |
| nosotros | `04-lo-que-nos-define.html` | nosotros |  |
| nosotros | `05-quienes-somos.html` | nosotros | **unconfirmed** |
| origen | `01-noticias-por-que-nace-kory.html` | origen |  |
| origen | `02-hero-por-que-nace-kory.html` | origen |  |
| origen | `03-sigue-leyendo.html` | origen |  |
| origen | `04-recibe-cada-articulo-en-tu-correo.html` | origen | form |
| pago | `01-breadcrumb.html` | pago |  |
| pago | `02-finalizar-compra.html` | pago | **unconfirmed**, form |
| politicas | `01-breadcrumb.html` | politicas |  |
| politicas | `02-hero-terminos-privacidad-y-devoluciones.html` | politicas |  |
| politicas | `03-terminos-y-condiciones.html` | politicas | **unconfirmed** |
| post | `01-noticias-como-llegan-sus-cos.html` | post |  |
| post | `02-hero-como-llegan-sus-cosmeticos-hasta-el-peru.html` | post | **unconfirmed** |
| post | `03-sigue-leyendo.html` | post |  |
| post | `04-recibe-cada-articulo-en-tu-correo.html` | post | form |
| presentacion | `01-noticias-buena-cosmetica-cor.html` | presentacion |  |
| presentacion | `02-hero-buena-cosmetica-coreana-a-la-medida-de-s.html` | presentacion | **unconfirmed** |
| presentacion | `03-sigue-leyendo.html` | presentacion |  |
| presentacion | `04-recibe-cada-articulo-en-tu-correo.html` | presentacion | form |
| producto | `01-breadcrumb.html` | producto |  |
| producto | `02-hero-vegan-gel-cleanser.html` | producto | **unconfirmed** |
| producto | `03-modo-de-uso.html` | producto | **unconfirmed** |
| producto | `04-opiniones.html` | producto | **unconfirmed** |
| productos | `01-breadcrumb.html` | productos |  |
| productos | `02-hero-todos-los-productos.html` | productos |  |
| productos | `03-vegan-gel-cleanser.html` | productos | **unconfirmed** |
| reclamaciones | `01-breadcrumb.html` | reclamaciones |  |
| reclamaciones | `02-hero-tu-opinion-nos-ayuda-a-mejorar.html` | reclamaciones |  |
| reclamaciones | `03-1-identificacion-del-consumidor.html` | reclamaciones | **unconfirmed**, form |
| regalo | `01-breadcrumb.html` | regalo |  |
| regalo | `02-hero-un-regalo-que-se-siente-especial.html` | regalo |  |
| regalo | `03-1-elige-el-kit.html` | regalo | **unconfirmed**, form |
| seguimiento | `01-breadcrumb.html` | seguimiento |  |
| seguimiento | `02-hero-donde-esta-mi-pedido.html` | seguimiento |  |
| seguimiento | `03-consultar.html` | seguimiento | **unconfirmed**, form |
| set | `01-breadcrumb.html` | set |  |
| set | `02-hero-kit-piel-clara-anti-imperfecciones.html` | set | **unconfirmed**, form |
| set | `03-secciones-del-producto.html` | set |  |
| set | `04-descripcion.html` | set | **unconfirmed** |
| set | `05-resenas.html` | set |  |
| set | `06-preguntas.html` | set | form |
| set | `07-tambien-te-puede-gustar.html` | set |  |
