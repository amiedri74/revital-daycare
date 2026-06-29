# Revital Daycare — Agent Guide

## Project
Static daycare site — 6 flat HTML pages, 1 CSS, 1 JS. Open files directly in browser. No build step, no package.json.

## Current state
- All 22 images, favicon.ico, and og-image.jpg exist
- No remaining placeholders in HTML
- **Serves ages 2-5** (preschool only) — infant/toddler programs removed
- **Domain:** `websitedaycare.pages.dev`
- **Deployed** to Cloudflare Pages at the above domain
- **Staff**: Revital Edry (Teacher, founder) and Itamar Nadjar (Assistant)
- **Contact**: 20628 Londelius St, Winnetka, CA 91306 | (818) 943-5983 | revitaldaycare@gmail.com
- **Hours**: Mon-Fri 6:30 AM - 6:00 PM
- SEO score: **88/100** | GEO score: **82/100**

## Audit results
- `SEO-AUDIT.md` — Score 88/100, full analysis with prioritized action plan
- `GEO-ANALYSIS.md` — Score 82/100, AI search readiness with brand mention gaps

## Contact form
Uses `mailto:revitaldaycare@gmail.com` via JavaScript — opens email app. No server-side submission.

## Images
All 22 photos exist in `images/` with descriptive alt text and proper dimensions. Gallery organized into 3 categories (classrooms, activities, special moments).

## SEO files
- `robots.txt` — allows GPTBot, OAI-SearchBot, ClaudeBot, PerplexityBot; blocks CCBot, anthropic-ai
- `sitemap.xml` — 6 URLs, lastmod 2026-06-28
- `llms.txt` — AI crawler content summary with key business facts
- `GEMINI.md` — removed (was empty)

## Theming
CSS variables in `styles.css :root`:
- `--primary` (#2874A6), `--secondary` (#F4A66D), `--accent` (#F9D971)

## Lighthouse
index.html: 100/100/100/100 (Perf/A11y/BP/SEO)
Other pages: 85-99 across categories

## Known issues
1. Contact form uses mailto: (no server-side tracking)
2. `sameAs: []` empty on all 3 schema blocks — no GBP or social links
3. No BreadcrumbList schema
4. Person schema for staff lacks credentials/knowsAbout
5. No external brand presence (GBP not created yet, no social profiles)
