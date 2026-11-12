# tuantruong.fyi

Personal website of Minh Tuan Truong: finance, FP&A and the AI systems I build for finance teams.

Live at **[tuantruong.fyi](https://tuantruong.fyi)**

## What it is

A single-page portfolio for finance and business leaders. It covers who I am, the projects I'm building, business impact from my finance work, my resume and how to get in touch.

## How it's built

- **One HTML file.** No framework, no build step, no dependencies. Markup, styles and scripts live in `index.html`.
- **Two languages.** English and German, switched with a dropdown. The choice is remembered in the visitor's own browser.
- **Light and dark mode.** Follows the system setting by default, with a manual switch.
- **Generative graphics.** The hero and section visuals are drawn live on a canvas from simple glyphs (dots, crosses, squares). They react to the cursor and respect reduced-motion settings.
- **Privacy first.** No analytics, no cookies, no tracking, no contact forms. Fonts (Archivo, IBM Plex Mono) are embedded in the page, so no requests go to Google or other font providers. A privacy policy under the Swiss FADP is built in at `#privacy`.
- **Responsive.** Tested on desktop and mobile, with no horizontal scrolling.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site |
| `og-image-5.jpg` | Preview image for LinkedIn and other link previews |
| `apple-touch-icon.png` | Icon for phone home screens |

## Deployment

Hosted on [Netlify](https://www.netlify.com). Every push to `main` deploys automatically, usually within a minute.

To update the site:

1. Edit or replace `index.html`.
2. Commit to `main`.
3. Netlify publishes the new version.

When the preview image changes, it gets a new file name (`og-image-6.jpg` and so on) so LinkedIn fetches the new one instead of a cached copy.

## Note on content

All project figures on the site use a fictional company with synthetic data. No employer data is used.

Text, photos and design © Minh Tuan Truong. All rights reserved.
