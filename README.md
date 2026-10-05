# BeyoSticker static website

Production-ready static site for GitHub + Netlify.

## Structure

- `index.html` — complete landing page, Google Analytics, UI, and event tracking
- `assets/images/` — optimized WebP catalog and hero images
- `netlify.toml` — Netlify publish/cache configuration

## Analytics

GA4 Measurement ID: `G-VP7XDDBWG5`

Tracked events:
- `page_view` — sent automatically by GA4
- `theme_filter_click` — theme chip click
- `view_theme` — opens a theme detail modal
- `whatsapp_click` — WhatsApp CTA click, with theme + placement
- `faq_open` — FAQ question opened

## Deploy via GitHub + Netlify

1. Upload **the contents of this folder** to the root of the GitHub repository. `index.html` must be at repository root.
2. In Netlify, choose **Add new site → Import an existing project → GitHub**.
3. Select the repository.
4. Netlify will read `netlify.toml`; no build command is required.
5. Deploy.

All website images are local relative assets, so no Scalev CDN is required.
