# Karathanasis Driving School — Σχολή Οδηγών Καραθανάσης

Jekyll site ready for GitHub Pages. Bilingual (Greek/English) with minima theme and Pages-safe plugins only.

## Structure
- `index.md`, `about.md`, `services.md`, `location.md`, `contact.md`: Pages with Greek/English sections (`#el`, `#en`).
- `_layouts/page.html`: Sticky header, nav, footer, OG meta.
- `_includes/head-extra.html`: JSON-LD LocalBusiness.
- `assets/css/site.css`: Minimal styling.
- `CNAME`, `favicon.ico`, `og-cover.jpg`: Placeholders to replace.

## Run locally
```sh
bundle exec jekyll serve
```
(If bundler/gems are not installed, run `gem install bundler jekyll` first.)

## Deploy to GitHub Pages
1. Push to `main` in this repository.
2. In GitHub repo Settings → Pages: select **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Save; wait for build to finish.
4. Replace `CNAME` content with your custom domain (optional) and ensure DNS A/ALIAS/ANAME to GitHub Pages + add `www` CNAME.
5. In Pages settings, enable **Enforce HTTPS** after certificate is issued.

## Contact form (Formspree)
- In `contact.md`, replace `https://formspree.io/f/REPLACE_ME` with your Formspree endpoint.
- Optionally add Formspree domain to allowed origins.

## Map
- Leaflet is loaded from unpkg on `location.md`. Coordinates center on Toumpa (Anatolikis Thrakis 49). Adjust if needed.

## SEO / Social
- Replace `og-cover.jpg` with a real 1200×630 image.
- Update `_config.yml` `url` if you add a custom domain (e.g., `https://example.gr`).

## Content edits
- Keep both Greek and English sections aligned; anchors are `#el` and `#en`.
- Navigation is defined via `header_pages` in `_config.yml`.

## Support
- Phone: +30 693 725 8280
- Facebook: https://www.facebook.com/KarathanasisAkis/about
- Instagram: https://www.instagram.com/karathanasissxoliodigon/
