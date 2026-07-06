# Industrially Powered Magic — website

Source for [industriallypoweredmagic.com](https://industriallypoweredmagic.com), the home of Industrially Powered Magic: speculative fiction by Patrick & Sam Seim.

Plain HTML and CSS, no build step. What's in the repo is exactly what gets served. Live since July 2026.

## Structure

```
index.html            Homepage — who we are, what we write, the books
clean-breath.html     The Clean Breath Pays the Debt (standalone SF)
camera-six.html       Camera Six (standalone supernatural horror)
consent-engine.html   The Consent Engine trilogy (forthcoming)
contact.html          Email, Instagram, Substack, PO Box
css/style.css         Single shared stylesheet (design tokens at the top)
images/               Covers, logo/badge, artwork crops
CNAME                 Custom domain for GitHub Pages — do not delete
```

Every page duplicates the same header and footer markup. When editing either, change all five pages identically.

## Hosting & deployment

Hosted on **GitHub Pages** from the `main` branch (root folder). Every push to `main` triggers the "pages build and deployment" workflow (Actions tab); the live site updates a minute or two after a successful run. If a run fails with "Deployment failed, try again later," re-run it from the Actions tab — it's usually transient.

The domain is registered at Squarespace. DNS: four apex A records point to GitHub Pages IPs (185.199.108–111.153), `www` is a CNAME to `confusedbysmiles.github.io`. HTTPS is enforced via the Pages settings.

## Images

Referenced by the site:

- `ipm-badge.png` — round goblin-artificer token, header logo on every page
- `ipm-workshop.jpg` — full workshop scene, homepage showcase
- `cover-*.jpg` — book covers (~800 px wide JPEGs)
- `camera-six-banner.jpg` / `camera-six-eye.jpg` — crops from the Camera Six cover art (page hero band and medallion pull-quote)
- `favicon.svg`

`IMG_4855.PNG` and `ipm_logocomplete.png` are the original full-resolution artwork sources, kept for reference; the site doesn't load them. High-res masters also live in the book project folders.

## To-do

- [ ] Replace `href="#"` buy links: The Clean Breath (wide retailers), Camera Six (Amazon Kindle)
- [ ] Real cover art for The Consent Engine (placeholder in use)
- [ ] Approved blurb for consent-engine.html (current copy is marked placeholder)
- [ ] PO Box on contact.html (marked with an HTML comment)

## Contact

support@industriallypoweredmagic.com · [@industriallypoweredmagic](https://www.instagram.com/industriallypoweredmagic/) · [Sam on Substack](https://samseim.substack.com/)
