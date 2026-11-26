# Assets, fonts, colors and link targets

Reference list for rebuilding the mockup in Shopify. Visual reference only. Values marked **por definir** are not decided: do not guess them.

## Fonts

| Use | Font | Weights | Source |
|---|---|---|---|
| Headings | Amaranth | 400, 700 (500 is used in the mockup and renders as 400) | Google Fonts |
| Body | Montserrat | 400, 500, 600, 700, 800 | Google Fonts |

Google Fonts link used by the mockup:

```
https://fonts.googleapis.com/css2?family=Amaranth:wght@400;700&family=Montserrat:wght@400;500;600;700;800&display=swap
```

## Colors

| Name | Hex | Use |
|---|---|---|
| Red | `#DC0C23` | Primary buttons, announcement bar, prices |
| Dark red | `#A8081A` | Hover, labels, footer background |
| Background | `#FFFBF2` | Page background |
| Yellow | `#FCF1C3` | Highlight sections |
| Pink | `#F9D2CB` | Cards, hero blocks |
| Text | `#2B1A1C` | Main text |
| Secondary text | `#5A3D40` | Descriptions |
| Border | `#F3E3CA` | Lines, card borders |
| Gold | `#F8B016` | Small badges |
| Blue | `#A8D4FF` | Review marks only ("por confirmar" / "propuesta"). Not part of the brand. Do not build. |

## Layout

- Container max width 1200 px. Breakpoints 1000 px (tablet, mobile menu) and 700 px (mobile).
- Arch shape on images and cards: `border-radius: 999px 999px 44px 44px`.
- Buttons are pill-shaped (`border-radius: 999px`), minimum height 46 to 56 px.
- Headings use `clamp()` sizes that scale with the viewport; see the inline styles in each section file.

## Logo

`assets/kory-logo.png` (header, 100×44 px as displayed). Footer logo is text-based in the mockup.

## Images

File names are the ones in the `assets/` folder. The originals are not in this repository: ask the team for the source files (Drive) before upload. Files over 400 KB should be compressed before upload.

| File | Alt text | Used on | Size (px) | KB |
|---|---|---|---|---|
| `kory-logo.png` | kory | blog, carrito, componentes, confirmacion, cuenta, envios, faq, index, kitescudo, kitritual, marcas, micuenta, navidad, nosotros, origen, pago, politicas, post, presentacion, producto, productos, reclamaciones, regalo, seguimiento, set | 684×300 | 29 |
| `6e921f775e064fafa6baf5edba744ef2.jpg` | Modelo sosteniendo una mascarilla de gel | index, nosotros | 2000×1500 | 1575 (large) |
| `339fe3786ca5d143c1cb7969cc632873.jpg` | UV Lacto Aqua Sun Cream de I'm Sorry For My Skin | index, navidad | 1000×1000 | 555 (large) |
| `d6bcc6c3576be92a1cd18f9ba63a07a8.jpg` | Jelly Mask Relaxing de I'm Sorry For My Skin | index, marcas | 1000×1000 | 426 (large) |
| `7bbc54a2b847087876ac8b558ab0a217.jpg` | Caja roja 3 STEPS rodeada de los parches Spot Eraser | set | 1500×1000 | 168 |
| `17dc120ad391b3cee908ae4b4bfb5f84.jpg` | Los tres parches y la caja, vista desde arriba | set | 1400×933 | 147 |
| `1f5b2942fa8a04198e88d302c8ab1c58.jpg` | Palacio tradicional coreano | blog | 1600×904 | 137 |
| `e28be85ac87cbb4680e7edabc924cbd5.jpg` | Dos cremas hidratantes NOLAHOUR sobre fondo amarillo | index, navidad | 933×1400 | 134 |
| `4b5ac01d361930818883278caf546c34.jpg` | Glowing Color Lip Balm de NOLAHOUR en cuatro tonos | index | 1600×1066 | 121 |
| `01703669e87d231e1e482931c7dc4495.jpg` | Parche verde | set | 1400×933 | 103 |
| `e9fc62125ec976e9091dba38c16a90a2.jpg` | Parches Spot Eraser de NOLAHOUR | index, navidad, set | 1400×933 | 102 |
| `fbad150bee882b281cadd30135102725.jpg` | Parche verde con su sobre | set | 1400×933 | 102 |
| `e62526108b33895a65a9492004fe6b7f.jpg` | Caja 3 STEPS del Kit PIEL CLARA | set | 933×1400 | 91 |
| `cb7863708587507ccf6feeb65355e8c1.jpg` | Parche verde con sobre | set | 1400×933 | 89 |
| `729c14e76686f463c454f43a8658244d.jpg` | Parche naranja | set | 1400×933 | 82 |
| `8572f639224b4abdfb74c72036f11b04.jpg` | Cremas hidratantes Vegan Watery Moisturizer de NOLAHOUR | index, marcas, set | 1400×933 | 74 |
| `f8e1a0be9842edc2fc6de10c04005123.jpg` | Parche AZUL del sistema Spot Eraser | set | 1400×933 | 61 |
| `8b64dbd0883161346c3a9ee32bf55299.jpg` | Parche VERDE del sistema Spot Eraser | set | 1400×933 | 55 |
| `62a218a86764b9a913ee63f4bdecd687.jpg` | Parche NARANJA del sistema Spot Eraser | set | 1400×933 | 55 |
| `ac2dd26fa03b04a2365329bfa8d30f6b.webp` | Kit Ritual Coreano | index, kitritual, regalo, set | 533×381 | 45 |
| `88e3f34fa9462a65967cfb09abe76f37.webp` | Kit PIEL CLARA | carrito, confirmacion, index, regalo | 533×381 | 40 |
| `12fb253d1b35ad5207d744d6b922fc53.webp` | Kit Escudo Andino | index, kitescudo, regalo, set | 533×381 | 28 |

## Internal links (mockup page → Shopify target)

The mockup links between its own pages. The Shopify URL for each one is **por definir**: Jose / Alonso to fill in.

| Mockup page | What it is | Shopify target |
|---|---|---|
| `index.html` | Home | **por definir** |
| `set.html` | Kit PIEL CLARA product page | **por definir** |
| `kitritual.html` | Kit Ritual Coreano product page | **por definir** |
| `kitescudo.html` | Kit Escudo Andino product page | **por definir** |
| `navidad.html` | Christmas bundles (2) | **por definir** |
| `regalo.html` | Gift page | **por definir** |
| `marcas.html` | Brands | **por definir** |
| `nosotros.html` | About us | **por definir** |
| `envios.html` | Shipping and returns | **por definir** |
| `faq.html` | FAQ | **por definir** |
| `blog.html` | News list | **por definir** |
| `post.html / presentacion.html / origen.html` | Articles | **por definir** |
| `carrito.html / pago.html / confirmacion.html` | Cart, checkout, confirmation (Shopify-controlled) | **por definir** |
| `cuenta.html / micuenta.html` | Login and account (Shopify-controlled, reference only) | **por definir** |
| `seguimiento.html` | Order tracking | **por definir** |
| `productos.html / producto.html` | All products and generic product page | **por definir** |
| `politicas.html / reclamaciones.html` | Policies and complaints form | **por definir** |
| `componentes.html` | Component sheet (design reference, not a page) | **por definir** |

## External links already in the mockup

| Link | Where |
|---|---|
| https://koryperu.com/ | Footer and share text |
| https://koryperu.com/pages/libro-de-reclamaciones | Footer (Libro de Reclamaciones) |
| https://koryperu.com/cdn/shop/files/TERMINOS_Y_CONDICIONES.pdf | Footer (terms) |
| https://koryperu.com/cdn/shop/files/Politica_de_Devoluciones.pdf | Footer (returns policy) |
| https://koryperu.com/cdn/shop/files/Politicas_de_Tratamiento_de_Datos.pdf | Footer (data policy) |
| https://www.instagram.com/kory.pe/ | Footer, articles |
| https://www.tiktok.com/@kory.pe | Footer |
| https://wa.me/?text=… | Share buttons (Navidad, Set) |

The footer WhatsApp number is marked **por confirmar** in the mockup.

