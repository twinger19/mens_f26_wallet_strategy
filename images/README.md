# Image map

Every image slot on the site, in the order it appears. **The filename is the slot** — drop a replacement in with the same name and path and it appears automatically. No HTML edit needed.

Two files are marked **TEMP** and should be replaced before this is presented.

| Where it appears | File | What it should show | |
|---|---|---|---|
| **Strategy 2027 — in page order** | | | |
| Hero, full-bleed background | `images/01-hero/hero-main.jpg` | Wide crop, dark enough for white type. Text sits bottom-left. |  2400x2113 · 300KB |
| The Shift — split image | `images/02-shift/payment-shift.jpg` | Phone and wallet together. Portrait-ish crop, fills the left half. |  1800x982 · 205KB |
| Category 01 card | `images/03-categories/category-01-extra-capacity.jpg` | Extra Capacity wallet. 16:10. |  1200x750 · 113KB |
| Category 02 card | `images/03-categories/category-02-new-classic.jpg` | New Classic bifold. 16:10. |  1182x738 · 94KB |
| Category 03 card | `images/03-categories/category-03-front-pocket.jpg` | Front Pocket / slim. 16:10. |  1400x875 · 290KB |
| Category 04 card | `images/03-categories/category-04-phone-companion.jpg` | MagSafe on a phone. 16:10. |  1400x875 · 228KB |
| Category 05 card | `images/03-categories/category-05-gift-special.jpg` | Gift set or boxed wallet. 16:10. | **TEMP** 1400x875 · 185KB |
| Image break — after categories | `images/04-breaks/break-carry-lifestyle.jpg` | Wide lifestyle. Gold quote overlays it, so keep the centre calm. |  1182x842 · 75KB |
| Image break — after gifting | `images/04-breaks/break-gift-packaging.jpg` | Wide gift packaging. Quote overlays it. |  2000x1091 · 316KB |
| Current state — split | `images/05-display/display-current-kohls.jpg` | Our fixture as it stands today. Tall crop, min 700px high. |  1600x1200 · 350KB |
| Opportunity — split | `images/05-display/display-opportunity.jpg` | Future display concept. Tall crop, anchored top. |  896x1200 · 219KB |
| Reference strip 1 | `images/05-display/reference-feature-icons.jpg` | Phone-case shelf card with feature icons. 4:3. |  1400x1050 · 138KB |
| Reference strip 2 | `images/05-display/reference-rail-labels.jpg` | Amika shelf rail labels. 4:3. |  1400x1050 · 259KB |
| Reference strip 3 | `images/05-display/reference-dockers-signage.jpg` | Dockers table signage at Kohl's. 4:3. |  1400x1050 · 274KB |
| Packaging 3-up, left | `images/06-packaging/packaging-brand-identity.jpg` | Packaging carrying brand identity. 4:3. |  1200x900 · 220KB |
| Packaging 3-up, centre | `images/06-packaging/packaging-premium-clean.jpg` | Clean premium packaging. 4:3. |  1200x900 · 119KB |
| Packaging 3-up, right | `images/06-packaging/packaging-gift-ready.jpg` | Gift-ready structured packaging. 4:3. |  1200x900 · 173KB |
| Packaging & Online — right | `images/06-packaging/ecomm-product-page.jpg` | Product in hand, the eComm standard. 4:3. |  1400x1050 · 156KB |
| **Brand Architecture — one per brand card** | | | |
| Cole Haan | `images/brands/cole-haan-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  1400x781 · 151KB |
| Calvin Klein | `images/brands/calvin-klein-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  1182x842 · 119KB |
| Kenneth Cole | `images/brands/kenneth-cole-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  974x632 · 65KB |
| Haggar | `images/brands/haggar-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  1400x933 · 121KB |
| Tommy Hilfiger | `images/brands/tommy-hilfiger-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  1400x939 · 226KB |
| Tommy Bahama | `images/brands/tommy-bahama-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  1400x781 · 214KB |
| Dockers | `images/brands/dockers-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. | **TEMP** 1400x933 · 144KB |
| Levi's | `images/brands/levis-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  1400x933 · 404KB |
| Columbia | `images/brands/columbia-lifestyle.jpg` | Lifestyle shot. Fills a 340px-wide column, any aspect. |  1182x842 · 58KB |

## Folder structure

```
images/
  01-hero/        full-bleed hero
  02-shift/       The Shift split image
  03-categories/  the five carry-category cards
  04-breaks/      full-width image breaks with quote overlays
  05-display/     fixture photography + in-store reference shots
  06-packaging/   packaging 3-up and the eComm shot
  brands/         one lifestyle image per brand
    logos/        brand logos (not currently placed on the page)
```

Folders are numbered in page order, so the folder list reads top-to-bottom the same way the page does.

## Conventions

- **Lowercase, hyphens, `.jpg`.** No spaces, no underscores, no `.JPG`.
- **Name by slot, not by source.** `category-03-front-pocket.jpg`, not `archetype-craftsman.jpg` — the name should say where it lands.
- **Sizes:** hero and breaks up to 2400px on the long edge; cards, reference and packaging 1200–1600px. Quality 85, progressive.
- **Keep it under ~6MB total.** This is a GitHub Pages site and every image loads over the wire.

## The two TEMP files

- `images/03-categories/category-05-gift-special.jpg` — a crop of the gift-packaging photo, taken from a different region so it does not duplicate the image break directly below it. Fine for now, but the Gift & Special card deserves its own shot of an actual gift set.
- `images/brands/dockers-lifestyle.jpg` — a generated placeholder, since there is no Dockers imagery in the folder. Needs a refined-casual, khaki/twill lifestyle shot.

## History

Reorganised 2026-09-07. Originals were flat in `images/` and `packaging-reference/` at 47MB total; they are preserved in git history if a higher-resolution version is ever needed.
