# Basecamp AI Consulting — Website

Live site for **Basecamp AI Consulting** (Basecamp Solutions LLC DBA Basecamp AI Consulting).

---

## Stack

- Plain HTML/CSS/JS — one `index.html` plus `/assets` for images (no framework, no build step)
- Hosted on **Netlify** (free tier), connected to this GitHub repo
- Auto-deploys on every push to `main`

---

## Folder Structure

```
basecamp-ai-site/
├── index.html       ← Page markup, styles, and scripts
├── README.md        ← This file
└── assets/          ← Logos and images (referenced from index.html)
```

---

## Making Updates

### Option A — Edit in Cursor, push to GitHub
1. Open the repo folder in Cursor
2. Make changes to `index.html`
3. `git add . && git commit -m "your message" && git push`
4. Netlify auto-deploys in ~30 seconds

### Option B — Build updates with Claude, paste into Cursor
1. Get updated code from Claude (this project chat)
2. Open `index.html` in Cursor
3. Replace the relevant section or full file
4. Push as above

---

## Key Details

| Item | Value |
|------|-------|
| Business name | Basecamp AI Consulting |
| Legal name | Basecamp Solutions LLC DBA Basecamp AI Consulting |
| Contact email | reid@basecampai.io |
| Booking link | https://calendly.com/reid-basecampai/30min |
| Netlify site | *(add your Netlify URL here after first deploy)* |
| Custom domain | *(add when ready)* |

---

## Brand Colors

| Name | Hex | Usage |
|------|-----|-------|
| Light Teal | `#55ADA2` | CTAs, links, highlights |
| Medium Teal | `#3D7371` | Hover states, secondary accent |
| Dark Teal | `#234552` | Dark accents |
| Dark Navy | `#1A2937` | Backgrounds, headers, primary text |
| White | `#FFFFFF` | Text on dark backgrounds |
| Medium Gray | `#A6A6A6` | Secondary text, captions |
| Warm Cream | `#F5F1EB` | Page background, card backgrounds |

---

## Fonts

- **Fraunces** (serif) — headlines and display text
- **DM Sans** — body copy, nav, buttons
- Both loaded via Google Fonts CDN

---

## Logo Files

Stored in `/assets/` and linked with relative paths (e.g. `assets/…`).

| File | Use |
|------|-----|
| `Basecamp_Chevron_only_logo.svg` | **Nav** — chevron mark next to the “Basecamp AI Consulting” wordmark (transparent background; teal artwork reads on the dark header) |
| `Basecamp_Full_Logo_Dark.png` | **Footer** — full wordmark on the dark footer (sized for readability) |
| Other PNGs in `/assets/` | Alternate or legacy exports (e.g. light/dark variants); swap paths in `index.html` if you change which file is used |

**Favicon:** Not set yet; you can point a `<link rel="icon">` at the chevron SVG or a small PNG in `/assets/`.

---

## Sections (in order)

1. **Nav** — Chevron SVG + wordmark + Book a Call (Calendly)
2. **Hero** — Headline, subheadline, primary CTA **Book a Free AI Strategy Call** + email
3. **Services** — Training / Strategy & Discovery / Implementation & Build
4. **Mid-page CTA strip** — Short copy + strategy call + email
5. **About** — Founder background, stats, pull quote
6. **FAQ** — 5 objection-handling questions (accordion)
7. **CTA Banner** — Final push to book (Calendly) or email
8. **Footer** — Full dark logo, tagline, email  
9. **Mobile** — Sticky bottom bar with Calendly + email (small screens)

---

## To-Do / Future Updates

- [ ] Add custom domain (`basecampai.io`) in Netlify
- [ ] Add testimonials/case studies once first clients close
- [ ] Add niche-specific headline once target market is locked in
- [ ] Consider adding a favicon (use chevron logo)

---

## Connecting Netlify to GitHub

1. Push this repo to GitHub
2. Go to [netlify.com](https://netlify.com) → New site → Import from Git
3. Select this repo, branch: `main`
4. Build command: *(leave blank)*
5. Publish directory: `/` (root)
6. Deploy — done

