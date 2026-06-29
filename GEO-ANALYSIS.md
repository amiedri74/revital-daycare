# GEO / AI Search Readiness — Revital Daycare

**Date:** 2026-06-28 (post-deployment)
**Analysis:** Generative Engine Optimization (AEO/GEO)
**AI surfaces:** Google AI Overviews, ChatGPT web search, Perplexity, Claude
**Domain:** `websitedaycare.pages.dev` (live)

---

## GEO Readiness Score: 82/100 ▲ (+6)

| Category | Weight | Score | Notes |
|----------|--------|-------|-------|
| Citability | 25% | 75 | FAQ, pricing (with $ amount), program descriptions are strong; no unique stats/data points |
| Structural Readability | 20% | 88 | Clean H1→H2→H3 hierarchy, lists, tables, FAQ, no heading skips |
| Multi-Modal Content | 15% | 80 | 22 deployed photos with descriptive alt text; no video or infographics |
| Authority & Brand Signals | 20% | 75 | Real staff names, contact info, JSON-LD; BUT `sameAs` empty (no external brand signals) |
| Technical Accessibility | 20% | 92 | Static HTML (SSR-native), AI crawlers allowed, llms.txt, canonicals, HTTPS |

---

## AI Crawler Access

| Crawler | robots.txt | Purpose |
|---------|-----------|---------|
| GPTBot | ✅ Allowed | ChatGPT web search |
| OAI-SearchBot | ✅ Allowed | OpenAI search features |
| ClaudeBot | ✅ Allowed | Claude web features |
| PerplexityBot | ✅ Allowed | Perplexity AI search |
| CCBot | ❌ Blocked | Training data |
| anthropic-ai | ❌ Blocked | Claude training only |

✅ `llms.txt` exists with 14 key facts and structured content navigation.
✅ Static HTML — no JavaScript dependency. Server-side rendered by nature.

---

## Brand Mention Analysis

| Platform | Presence | Impact on AI Citations |
|----------|----------|----------------------|
| Google Business Profile | ❌ None | **Critical gap** — GBP citations = strongest local AI visibility factor. ChatGPT sources Bing index + Yelp, not GBP directly, but GBP feeds Google AI Overviews. |
| Wikipedia | ❌ None | Wikipedia presence = strong AI citation signal (47.9% of ChatGPT citations from Wikipedia) |
| Reddit | ❌ None | 46.7% of Perplexity citations from Reddit; 11.3% of ChatGPT citations |
| YouTube | ❌ None | Strongest correlation with AI citations (~0.737 per Ahrefs Dec 2025 study) |
| LinkedIn | ❌ None | Moderate correlation; adds to brand mention portfolio |
| Yelp | ❌ None | ChatGPT sources Yelp for local business queries |

**Key insight:** Brand mentions correlate **3x more strongly** with AI citations than backlinks (Ahrefs Dec 2025, 75,000 brands studied). Zero external brand presence = missed AI visibility opportunity.

---

## Structured Data (All 6 Pages)

| Page | Schema Type | Key Properties | Status |
|------|------------|----------------|--------|
| index.html | ChildCare | name, address, telephone, url, openingHours, aggregateRating | ✅ `sameAs` empty |
| about.html | Organization | name, address, telephone, email, url, founder, employee | ✅ `sameAs` empty; Person entries minimal |
| programs.html | WebPage + ItemList | name, description, url, Service items | ✅ |
| gallery.html | WebPage | name, description, url | ✅ |
| contact.html | LocalBusiness | name, address, telephone, email, url, geo, openingHours | ✅ `sameAs` empty |
| privacy.html | WebPage | name, description, url | ✅ |

---

## E-E-A-T Assessment (Google's Who/How/Why Test)

| Question | Score | Detail |
|----------|-------|--------|
| **Who** created the content? | 7/10 | Founder named (Revital Edry), credentials listed (7 yrs experience, ECE degree, CPR certified) |
| **How** was it created? | 6/10 | Reggio Emilia approach described, curriculum detailed, but no methodology specifics or process documentation |
| **Why** does it exist? | 9/10 | Clear mission: quality daycare serving Winnetka families with play-based learning |

**Note:** E-E-A-T now applies to ALL competitive queries per December 2025 Core Update. This site is strong on Trustworthiness (physical address, phone, email, privacy policy) and moderate on Experience (original photos, named staff). Weakest on Authoritativeness (no external validation signals).

---

## Passage-Level Citability

### Strong candidates (134-167 word answer blocks):
- **Program description** (~150 words) — Clear positioning for preschool program
- **FAQ section** — 6 Q&A pairs in clear pattern, easily extractable
- **Pricing** — $1,300/month with sibling discount = concrete, citable data
- **Staff bios** — Revital and Itamar bios are self-contained paragraphs

### Needs improvement:
- **Homepage hero** — "Nurturing Growth, Building Community" is a tagline, not an answer block. Add a "What is Revital Daycare?" definition in first 60 words.
- **About "Our Story"** — Could open with a 50-60 word direct mission statement for AI extraction.

### Citability quick wins (Google's recommendation):
- Add "What is [topic]?" definition in first 60 words of homepage
- Create a 134-167 word self-contained answer block for "preschool Winnetka"
- Add specific statistics (e.g., "Over 50 families served", "100% kindergarten readiness rate")

---

## Platform-Specific Assessment

| Platform | Score | Key Gap |
|----------|-------|---------|
| Google AI Overviews | 80 | Traditional SEO foundation solid (canonicals, sitemap, schema). Needs more definition-style passages |
| ChatGPT | 65 | No Wikipedia/Reddit/LinkedIn brand presence. ChatGPT sources Wikipedia for 47.9% of citations |
| Perplexity | 65 | No Reddit/community validation. Perplexity favors Reddit (46.7% of citations) |
| Claude | 75 | Well-structured content, good for direct citation from crawled pages |

---

## Quick Wins Already Applied

- [x] robots.txt allows GPTBot, OAI-SearchBot, ClaudeBot, PerplexityBot
- [x] llms.txt created with structured content + 14 key facts
- [x] Staff names updated to real people (Revital Edry, Itamar Nadjar)
- [x] Contact info (NAP) consistent across all pages
- [x] FAQ section on contact.html with clear Q&A format
- [x] JSON-LD on all 6 pages (ChildCare, Organization, WebPage, LocalBusiness)
- [x] Canonical tags on all pages
- [x] Services consolidated to preschool (ages 2-5) with consistent messaging
- [x] Static HTML — zero JS dependency for AI crawlers
- [x] OG/Twitter cards complete on all pages
- [x] `<main>` landmark on all pages

---

## Top 5 Recommendations

| # | Action | Effort | Impact |
|---|--------|--------|--------|
| 1 | **Populate `sameAs`** with GBP, YouTube, Facebook, Instagram, LinkedIn URLs | 30 min | Very High — unblocks local SEO, E-E-A-T, AND AI visibility simultaneously |
| 2 | **Create Google Business Profile** | 1 hr | Critical — GBP = 32% of local ranking factors; feeds Google AI Overviews |
| 3 | **Add original statistic** — e.g., "100% kindergarten readiness", "Serving Winnetka families since 2020" | 10 min | High — unique data points dramatically improve citability |
| 4 | **Create YouTube channel** with 2-3 short videos (facility tour, daily routine) | 2 hrs | High — YouTube presence = strongest brand-mention correlation with AI citations |
| 5 | **Expand homepage intro** — Add 60-word "What is Revital Daycare?" definition block | 15 min | High — matches AI extraction patterns for featured snippets + AIO |

---

## Verification (ACCEPT)

- **sameAs fix succeeds if:** Business shows up in Google Knowledge Panel with social profile links within 2 weeks of submission.
- **YouTube presence succeeds if:** Brand gets cited by ChatGPT/Perplexity for "daycare Winnetka" queries within 3 months.
- **Statistic addition succeeds if:** The specific stat appears in AI Overviews for related queries within 1 month.
- **Next audit should look for:** Populated `sameAs`, GBP created and verified, YouTube channel with content, new statistic in homepage content.