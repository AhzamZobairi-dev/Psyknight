# PSYKNIGHT — Landing Page

> Official website for [psyknight.in](https://psyknight.in)  
> An early-stage Generative AI brand. In development.

---

## About PSYKNIGHT

PSYKNIGHT is building at the intersection of AI capability and human need, with two core missions:

1. **GenAI Solutions** — Building practical AI tools, starting with AI-assisted translation of classical Arabic Islamic texts into English, and later Urdu, using efficient open language models with human and scholarly review.

2. **AI Education for the Underprivileged** — Planning free and low-cost AI learning content for learners who cannot access expensive courses or programmes.

---

## About This Repo

This repository contains the PSYKNIGHT landing page — a single-file, static website.

| File | Description |
|---|---|
| `index.html` | Complete website — all CSS and JS inline, zero dependencies |

**Stack:** Pure HTML · Vanilla CSS · Vanilla JavaScript  
**No** frameworks, libraries, external fonts, or images.

---

## Deploying

### Cloudflare Pages

1. Push this repo to GitHub.
2. Go to [Cloudflare Pages](https://pages.cloudflare.com) → **Create a project** → Connect to GitHub.
3. Select this repo.
4. Set **Build command** to *(leave blank)* and **Output directory** to `/` (or `.`).
5. Click **Save and Deploy**.
6. Point your `psyknight.in` domain to the Pages project in the Cloudflare DNS dashboard.

### GitHub Pages

1. Go to **Settings → Pages** in this repo.
2. Under **Source**, select the branch (e.g. `main`) and folder `/` (root).
3. Click **Save**. Your site will be live at `https://<username>.github.io/<repo>`.
4. To use a custom domain, add a `CNAME` file containing `psyknight.in` to the repo root, then configure DNS.

### Manual / Any Static Host

Upload `index.html` to any static file host (Netlify, Vercel, AWS S3 + CloudFront, etc.). No build step required.

---

## Development

No build tools are needed. Open `index.html` directly in a browser, or use any local static server:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

---

## Page Sections

| # | Section | Notes |
|---|---|---|
| 1 | **Hero** | Brand name, tagline, CTA button, decorative Arabic ترجمة |
| 2 | **Our Mission** | Two-card layout — GenAI Solutions & AI Education |
| 3 | **Flagship Project** | AI translation pipeline, features, disclaimer |
| 4 | **How We Work** | 3-step process |
| 5 | **Roadmap** | 3 phases — English, Urdu, Education & more tools |
| 6 | **Contact** | mailto link |
| 7 | **Footer** | Copyright, early-stage disclaimer, AI-assisted notice |

---

## Design Notes

- **Dark minimal** style with gold (`#c8a84b`) and teal (`#2dd4bf`) accents
- **System font stack** — no external font requests
- **Mobile-first** responsive layout; hamburger nav on ≤ 768 px
- Scroll-reveal animations via `IntersectionObserver` (degrades gracefully)
- `prefers-reduced-motion` respected
- Semantic HTML with `aria-*` labels throughout
- Full SEO meta, Open Graph, and Twitter Card tags

---

## Honesty Policy

This site intentionally avoids:
- Invented customer numbers, testimonials, or case studies
- Claims of funding, partnerships, or awards
- Named AI vendors or proprietary model names
- Claims of religious authority over translated content

All copy uses words like *building*, *developing*, and *planned*.  
Translations are described as AI-assisted drafts subject to human and scholarly review.

---

## Contact

**Ahzam Zobairi** — [ahzamzobairi@psyknight.in](mailto:ahzamzobairi@psyknight.in)

---

© 2026 PSYKNIGHT · [psyknight.in](https://psyknight.in)  
*An early-stage Generative AI company — products are in development and not yet launched.*
