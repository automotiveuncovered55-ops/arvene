# ARVENE — Photography brief & drop-in guide

**Status: none of these image files exist yet.** The site currently shows tonal placeholder illustrations. Every path below is already wired into `index.html`; add a file at the exact path and it replaces its placeholder automatically. Missing files fall back to the placeholder, so you can add images gradually.

## How to use
1. Create each image (shoot, commission, or generate with a tool you have rights to use) to the brief below.
2. Save as WebP, 1600 px on the long edge for campaign/editorial, 1200×1500 for products (4:5). Keep originals elsewhere.
3. Put files in the folders shown. Host the folder with `index.html` (Netlify, Vercel, GitHub Pages). *The sandboxed Claude preview cannot load external or relative images, so photos will only appear on your own hosting.*
4. If you generate images with AI, state that on the site; do not imply it is a real campaign. Check the tool's licence for commercial/portfolio use.
5. Product photos must show the exact garment and colour named in the filename. If you cannot make a colour, remove that colour in the `P` data (or leave the placeholder) rather than show a different garment.

## HOUSE STYLE (apply to every image): quiet, architectural, expensive. Pale concrete, travertine, plaster and stone; soft directional daylight from camera-left at roughly 45°, long soft shadows; palette of ivory, stone, taupe, charcoal and the garment colour only. Subtle filmic grade, low saturation, no teal/orange. Adult models, natural skin texture, calm expressions, no smiling-at-camera stock poses. Real fabric weight and drape. No text, logos, watermarks, labels or props. Same grade and lens character across all images (≈85mm look for portraits, ≈50mm for full length).

## Tier 1 — campaign, editorial, collections (do these first)
| File | Ratio | Focal point (desktop / mobile) | Brief |
|---|---|---|---|
| `images/campaign/campaign-autumn-hero.webp` | 3:2 (wide) | 60% 30% / 55% 20% | Full-length model in a long, straight camel wool overcoat, relaxed stance, in a pale-concrete modernist space with a single beam of daylight. Camera slightly low. Large clear negative space bottom-left for headline; keep face and coat lapels clear of the bottom 35%. Shoot wide (≈3:2) so mobile can crop to the model. |
| `images/editorial/editorial-tailoring-shadow.webp` | 1:1 | 50% 35% / 50% 35% | Three-quarter shot of a model in an unlined dark charcoal blazer and relaxed trousers, interior with sculptural shadow falling across stone. Emphasise shoulder line and drape. Square-ish crop. |
| `images/collections/collection-outerwear.webp` | 3:4 | 50% 25% / 50% 25% | Collection cover for Outerwear: one model or a still-life of 2–3 pieces from the category, same stone/daylight world, garment fills the frame, space around it to crop. |
| `images/collections/collection-tailoring.webp` | 3:4 | 50% 25% / 50% 25% | Collection cover for Tailoring: one model or a still-life of 2–3 pieces from the category, same stone/daylight world, garment fills the frame, space around it to crop. |
| `images/collections/collection-knitwear.webp` | 3:4 | 50% 30% / 50% 30% | Collection cover for Knitwear: one model or a still-life of 2–3 pieces from the category, same stone/daylight world, garment fills the frame, space around it to crop. |
| `images/collections/collection-essentials.webp` | 3:4 | 50% 30% / 50% 30% | Collection cover for Essentials: one model or a still-life of 2–3 pieces from the category, same stone/daylight world, garment fills the frame, space around it to crop. |
| `images/collections/collection-accessories.webp` | 3:4 | 50% 50% / 50% 50% | Collection cover for Accessories: one model or a still-life of 2–3 pieces from the category, same stone/daylight world, garment fills the frame, space around it to crop. |

## Tier 2 — products (75 images; start with every `-front`)
Product brief: single garment, fully visible, on a neutral ivory-stone backdrop, soft overhead-left studio light, natural contact shadow, true colour, 4:5, same framing and distance across all products. `front` = straight-on; `detail` = close crop of the real fabric/seam/button of the same garment; `back` = back view (also used as the hover image — if absent, no hover swap is shown).

| Product | Colour | Files |
|---|---|---|
| Orvane Overcoat — 100% double-faced virgin wool | Ink (#1d1c1a) | `images/products/product-orvane-overcoat-ink-front.webp`<br>`images/products/product-orvane-overcoat-ink-detail.webp`<br>`images/products/product-orvane-overcoat-ink-back.webp` |
| Orvane Overcoat — 100% double-faced virgin wool | Camel (#b08d63) | `images/products/product-orvane-overcoat-camel-front.webp`<br>`images/products/product-orvane-overcoat-camel-detail.webp`<br>`images/products/product-orvane-overcoat-camel-back.webp` |
| Tallow Blazer — 98% wool, 2% elastane twill | Slate (#4a4f55) | `images/products/product-tallow-blazer-slate-front.webp`<br>`images/products/product-tallow-blazer-slate-detail.webp`<br>`images/products/product-tallow-blazer-slate-back.webp` |
| Tallow Blazer — 98% wool, 2% elastane twill | Ink (#1d1c1a) | `images/products/product-tallow-blazer-ink-front.webp`<br>`images/products/product-tallow-blazer-ink-detail.webp`<br>`images/products/product-tallow-blazer-ink-back.webp` |
| Verge Pleated Trouser — 100% tropical wool | Slate (#4a4f55) | `images/products/product-verge-trouser-slate-front.webp`<br>`images/products/product-verge-trouser-slate-detail.webp`<br>`images/products/product-verge-trouser-slate-back.webp` |
| Verge Pleated Trouser — 100% tropical wool | Stone (#cfc6b6) | `images/products/product-verge-trouser-stone-front.webp`<br>`images/products/product-verge-trouser-stone-detail.webp`<br>`images/products/product-verge-trouser-stone-back.webp` |
| Loom Fine Knit — 100% extra-fine merino, 14-gauge | Oat (#d9cdb4) | `images/products/product-loom-knit-oat-front.webp`<br>`images/products/product-loom-knit-oat-detail.webp`<br>`images/products/product-loom-knit-oat-back.webp` |
| Loom Fine Knit — 100% extra-fine merino, 14-gauge | Olive (#5b5a40) | `images/products/product-loom-knit-olive-front.webp`<br>`images/products/product-loom-knit-olive-detail.webp`<br>`images/products/product-loom-knit-olive-back.webp` |
| Loom Fine Knit — 100% extra-fine merino, 14-gauge | Ink (#1d1c1a) | `images/products/product-loom-knit-ink-front.webp`<br>`images/products/product-loom-knit-ink-detail.webp`<br>`images/products/product-loom-knit-ink-back.webp` |
| Quiet Tee — 100% 240gsm combed cotton | Ecru (#e7e0d2) | `images/products/product-quiet-tee-ecru-front.webp`<br>`images/products/product-quiet-tee-ecru-detail.webp`<br>`images/products/product-quiet-tee-ecru-back.webp` |
| Quiet Tee — 100% 240gsm combed cotton | Ink (#1d1c1a) | `images/products/product-quiet-tee-ink-front.webp`<br>`images/products/product-quiet-tee-ink-detail.webp`<br>`images/products/product-quiet-tee-ink-back.webp` |
| Field Overshirt — 100% brushed cotton canvas | Olive (#5b5a40) | `images/products/product-field-overshirt-olive-front.webp`<br>`images/products/product-field-overshirt-olive-detail.webp`<br>`images/products/product-field-overshirt-olive-back.webp` |
| Field Overshirt — 100% brushed cotton canvas | Tan (#9a6b45) | `images/products/product-field-overshirt-tan-front.webp`<br>`images/products/product-field-overshirt-tan-detail.webp`<br>`images/products/product-field-overshirt-tan-back.webp` |
| Ledger Linen Shirt — 100% European flax linen | Ecru (#e7e0d2) | `images/products/product-ledger-shirt-ecru-front.webp`<br>`images/products/product-ledger-shirt-ecru-detail.webp`<br>`images/products/product-ledger-shirt-ecru-back.webp` |
| Ledger Linen Shirt — 100% European flax linen | Stone (#cfc6b6) | `images/products/product-ledger-shirt-stone-front.webp`<br>`images/products/product-ledger-shirt-stone-detail.webp`<br>`images/products/product-ledger-shirt-stone-back.webp` |
| Ashlar Roll Neck — 70% merino, 30% cashmere | Ink (#1d1c1a) | `images/products/product-rollneck-ink-front.webp`<br>`images/products/product-rollneck-ink-detail.webp`<br>`images/products/product-rollneck-ink-back.webp` |
| Ashlar Roll Neck — 70% merino, 30% cashmere | Camel (#b08d63) | `images/products/product-rollneck-camel-front.webp`<br>`images/products/product-rollneck-camel-detail.webp`<br>`images/products/product-rollneck-camel-back.webp` |
| Plain Belt — Vegetable-tanned leather, brushed steel | Ink (#1d1c1a) | `images/products/product-plain-belt-ink-front.webp`<br>`images/products/product-plain-belt-ink-detail.webp`<br>`images/products/product-plain-belt-ink-back.webp` |
| Plain Belt — Vegetable-tanned leather, brushed steel | Tan (#9a6b45) | `images/products/product-plain-belt-tan-front.webp`<br>`images/products/product-plain-belt-tan-detail.webp`<br>`images/products/product-plain-belt-tan-back.webp` |
| Daybook Tote — Full-grain calf leather, cotton lining | Ink (#1d1c1a) | `images/products/product-daybook-tote-ink-front.webp`<br>`images/products/product-daybook-tote-ink-detail.webp`<br>`images/products/product-daybook-tote-ink-back.webp` |
| Daybook Tote — Full-grain calf leather, cotton lining | Tan (#9a6b45) | `images/products/product-daybook-tote-tan-front.webp`<br>`images/products/product-daybook-tote-tan-detail.webp`<br>`images/products/product-daybook-tote-tan-back.webp` |
| Straight Everyday Trouser — 100% cotton gabardine | Ink (#1d1c1a) | `images/products/product-straight-trouser-ink-front.webp`<br>`images/products/product-straight-trouser-ink-detail.webp`<br>`images/products/product-straight-trouser-ink-back.webp` |
| Straight Everyday Trouser — 100% cotton gabardine | Stone (#cfc6b6) | `images/products/product-straight-trouser-stone-front.webp`<br>`images/products/product-straight-trouser-stone-detail.webp`<br>`images/products/product-straight-trouser-stone-back.webp` |
| Heavyweight Sweatshirt — 100% 450gsm loopback cotton | Stone (#cfc6b6) | `images/products/product-heavy-sweat-stone-front.webp`<br>`images/products/product-heavy-sweat-stone-detail.webp`<br>`images/products/product-heavy-sweat-stone-back.webp` |
| Heavyweight Sweatshirt — 100% 450gsm loopback cotton | Slate (#4a4f55) | `images/products/product-heavy-sweat-slate-front.webp`<br>`images/products/product-heavy-sweat-slate-detail.webp`<br>`images/products/product-heavy-sweat-slate-back.webp` |
