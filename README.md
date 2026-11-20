# The Red Fox — Diner & Tavern

Visual menu and immediate-ordering preview for **The Red Fox** at 1317 Border Lane, Washburn, North Dakota.

**GitHub Pages:** [https://weiszdev.github.io/red-fox-washburn/](https://weiszdev.github.io/red-fox-washburn/)

Static files only. No build step. Open `index.html` or serve the folder. Relative paths (`./images/...`, `./css/...`, `./js/...`) keep the site working under the `/red-fox-washburn/` subpath.

## What’s on the page

- Live Central Time open/closed status (Mon–Sat 7:00 AM–2:00 PM, Sun 9:00 AM–2:00 PM)
- All 61 printed menu items with descriptions and prices, including the **$13 Smoky BBQ Chicken Wrap**
- Tap-to-customize cards (size, milk, syrups, meat, eggs, toast, bacon +$2, hashbrowns +$3, extra steak +$5)
- Build-your-own drink studio with a live cup, quick-load presets, and signature vs. standard pricing
- Slide-out bag with ASAP pickup (15 / 25 / 40 minute kitchen throttle) or later-today slots
- Zero-charge order preview: guest status timeline and a kitchen/barista ticket
- Side-by-side look at the current Toast coffee page versus ordering on your own site
- Add-on revenue sliders
- Domain launchpad for the four `.com` names that were available on GoDaddy on Nov 19, 2026
- Hours, click-to-call `(701) 462-8175`, `redfoxwashburn@gmail.com`, map link, and Facebook

Photography in `images/` is generated preview art. Swap in real kitchen and bar photos by keeping the same file names.

## Preview locally

```bash
python3 -m http.server 4173
```

Then open [http://127.0.0.1:4173/](http://127.0.0.1:4173/).

## GitHub Pages

In the repository settings, set Pages to deploy from the `main` branch (root). The published URL is:

https://weiszdev.github.io/red-fox-washburn/

A `.nojekyll` file is included so GitHub Pages serves the folder as-is.

## Domain availability

Checked on GoDaddy, November 19, 2026. First year is $0.01 with a 3-year term. Renewal is $22.99/year. Availability can change.

| Domain | Note |
| --- | --- |
| redfoxwashburn.com | Top recommendation |
| theredfoxwashburn.com | Available |
| redfoxnd.com | Available |
| theredfoxnd.com | Available |

Also available that day, without a price in this check: `redfoxwashburn.net`, `redfoxwashburn.org`, `redfoxwashburn.us`, `redfoxwashburn.co`.

## Files

| Path | Role |
| --- | --- |
| `index.html` | Page structure, story, ordering pitch, domain launchpad |
| `css/styles.css` | Layout and brand styles |
| `js/menu-data.js` | The 61-item printed menu |
| `js/app.js` | Menu, studio, bag, and demo order |
| `images/` | 14 menu and atmosphere photos |
| `favicon.svg` | Fox mark |
