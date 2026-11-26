# kory-mockup

Visual reference for the KORY website redesign (Spanish-language mockup, 25 pages).

- Purpose: reference for rebuilding sections in Shopify (Liquid). This is not production code and is not meant to be deployed as is.
- How to view: open `index.html` in a browser. Paths are relative, and images are in `assets/`.
- Blue highlights mark content that is still unconfirmed (marked "por confirmar" / "propuesta"). Prices and names are drafts.
- Phase 1 pages (proposed): the three kit pages, the two Christmas bundles (`navidad.html`), and the welcome coupon. Everything else is later.
- Shopify keeps cart, checkout, coupons and orders. Only the visual sections are meant to be reused.
- Private repository. Please do not share the link or the content outside the team.
- `ASSETS_AND_LINKS.md`: fonts, colors, image list and link targets (Shopify URLs still to be defined).
- `sections/`: the same pages split into one HTML file per section (hero, cards, FAQ, footer...), with `sections/README.md` as the index and `sections/base.css` for shared rules. Use these as the unit when rebuilding sections in Shopify.
