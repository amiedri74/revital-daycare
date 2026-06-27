# Revital Daycare — Agent Guide

## Project
Static daycare site — 5 flat HTML pages, 1 CSS, 1 JS. Open files directly in browser. No build step, no package.json.

## Current state
- All placeholders in HTML files have been replaced with real content
- **Only remaining placeholder**: `[YOUR_FORM_ID]` in `contact.html:114`
- **Missing files that will break the site**: `images/` directory (22 images referenced), `favicon.ico`
- **Domain is still placeholder** `revitaldaycare.com` — must update in: `robots.txt`, `sitemap.xml`, OG URLs in all HTML `<head>`s, JSON-LD `url` fields
- **Staff**: Revital Edry (Teacher, founder) and Itamar Nadjar (Assistant) — do not reintroduce demo names
- **Contact**: 20628 Londelius St, Winnetka, CA 91306 | (818) 943-5983 | revitaldaycare@gmail.com
- **Hours**: Mon-Fri 6:30 AM - 6:00 PM

## Audit focus
User focus is "audit website". Key reference reports:
- `SEO-AUDIT.md` — Score 72/100, deployment checklist
- `GEO-ANALYSIS.md` — Score 73/100, AI search readiness

## Contact form
Form posts to Formspree (`https://formspree.io/f/[YOUR_FORM_ID]`). Requires a real Formspree form ID.

## Images
All photos use `<img src="images/...">` tags. The `images/` directory does not exist yet — must be created before deploy. Gallery images are organized into 3 categories (infants, toddlers, preschoolers).

## SEO files
- `robots.txt` — configured to allow AI search crawlers (GPTBot, OAI-SearchBot, ClaudeBot, PerplexityBot), block training crawlers (CCBot, anthropic-ai)
- `sitemap.xml` — 6 URLs, lastmod dates should be updated on deploy
- `llms.txt` — AI crawler content summary, update if content changes
- `GEMINI.md` — empty file, likely unused

## Theming
CSS variables in `styles.css :root`:
- `--primary` (#5DADE2), `--secondary` (#F4A66D), `--accent` (#F9D971)

## Mobile menu
`.nav-menu.active { display: flex; }` is already in `styles.css` (line 1035, inside `@media max-width: 768px`).

## Script.js
`data-src` lazy loading observer exists but no HTML uses `data-src` yet — images use standard `src` attributes.
