# Basecamp AI Consulting — Website

Live site for **Basecamp AI Consulting** (Basecamp Solutions LLC DBA Basecamp AI Consulting).

---

## Stack

- Plain HTML/CSS/JS — single file, no framework, no build step
- Hosted on **Netlify** (free tier), connected to this GitHub repo
- Auto-deploys on every push to `main`

---

## Folder Structure

```
basecamp-ai-site/
├── index.html       ← The entire site (single file)
├── README.md        ← This file
└── assets/          ← Logo files and any future images
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
| Booking link | https://calendar.app.google/c8P6Mfib5C5HwzKJ7 |
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

Stored in `/assets/`. Use the correct version per context:

| File | Use when |
|------|----------|
| `Basecamp_Full_Logo_Light.png` | Light/cream backgrounds (nav) |
| `Basecamp_Full_Logo_Dark.png` | Dark/navy backgrounds (footer) |
| `Basecamp_Chevron_Only_Logo.png` | Favicon or icon-only contexts |

> Note: Logos are currently embedded as base64 directly in `index.html` so the site works as a true single file. If the file gets too large, move them to `/assets/` and reference them with relative paths.

---

## Sections (in order)

1. **Nav** — Logo + business name + Book a Call CTA
2. **Hero** — Headline, subheadline, two CTAs
3. **Services** — Training / Strategy & Discovery / Implementation & Build
4. **About** — Founder background, stats, pull quote
5. **FAQ** — 5 objection-handling questions (accordion)
6. **CTA Banner** — Final push to book or email
7. **Footer** — Logo, tagline, email

---

## To-Do / Future Updates

- [ ] Add custom domain (`basecampai.io`) in Netlify
- [ ] Add testimonials/case studies once first clients close
- [ ] Swap Google Calendar link for Calendly if you switch tools
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

