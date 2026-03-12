# CLAUDE.md — tuontimesta.fi

Business website for a Finnish car import company (personal/family). Production-ready static site.

## Tech Stack

- Pure HTML/CSS/JS, no build system
- DM Sans typography (Google Fonts)

## Structure

- `index.html` — main site
- `styles.css` — all styling with CSS variables
- `script.js` — navigation and smooth scrolling
- `robots.txt`, `sitemap.xml`, `.htaccess` — SEO and server config

## Content Sections

Hero → About (Meistä) → Services (Palvelumme) → Pricing (Hinnasto) → Links (Linkkejä) → Gallery → Contact

Contact info: phone, WhatsApp, email, addresses (Lahti + Berlin)

## Architecture

- JSON-LD LocalBusiness structured data
- `.htaccess`: HTTPS redirect, caching, compression, security headers
- Canonical URLs for non-www domain
- SVG favicon

## Development

No build step — edit files directly. See `SEO-CHECKLIST.md` for deployment guide.

## Deployment

Hosted on atk VPS (UpCloud Helsinki, `ssh atk`). Auto-deploys via GitHub webhook on push to main.

- Site root on server: `/var/www/static/tuontimesta.fi`
- Deploy script: `/var/www/static/deploy-tuontimesta-fi.sh`
- Webhook URL: `https://tuontimesta.fi/webhook`
- nginx config: `/etc/nginx/sites-available/tuontimesta.fi`

See atk server memory for full webhook setup details.

## Git

Identity: personal (`jani@laatunen.fi` / janilaatunen)

## Rules

- Never increment version numbers without explicit confirmation
