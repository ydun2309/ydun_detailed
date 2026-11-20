# Ydun website

Static site (plain HTML/CSS, no build step), made from the "Ydun – website story" deck.

## Files
- `index.html` – all page text (hero, team, contact)
- `styles.css` – colours, fonts and layout (brand colours are at the top under `:root`)
- `assets/` – logo, hero photo, Hanken Grotesk font (self-hosted, no Google Fonts calls)
- `404.html`, `robots.txt`, `sitemap.xml`, `_headers` – Cloudflare Pages extras

## Deploy on Cloudflare Pages
**Via GitHub:** put these files at the root of the repo connected to the Pages project.
In the Pages settings use: Framework preset = None, Build command = (empty), Build output directory = `/`.

**Direct upload:** Workers & Pages → your project → Create deployment → drag in this folder (or the zip).

`sitemap.xml`, `robots.txt` and the canonical/og tags in `index.html` assume the site lives at https://ydun.com/ — change them if the domain differs.
