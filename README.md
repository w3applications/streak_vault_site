# Streak Vault — marketing site

Static marketing site for [Streak Vault](https://streakvault.com), the calm daily brain-teaser by W3 Applications. Deployed on GitHub Pages with the custom domain `streakvault.com` (see `CNAME`).

- `index.html` — marketing landing page
- `privacy.html` — privacy policy
- `terms.html` — terms of service
- `404.html` — not-found page (GitHub Pages serves it automatically; uses root-absolute paths)
- `styles.css` — shared styles (palette mirrors the app's Midnight theme)
- `assets/` — app icon renditions, the link-preview image (`og-image.jpg`), and `screens/`, the captioned store screenshots from the app repo's `store_assets/appstore/iphone-6.3/` resized to 600 px WebP

The nav, footer, and `<head>` tags are repeated by hand in each page — change them in all four.

No build step — edit and push to `main`; GitHub Pages serves the files as-is.
