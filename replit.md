# Chawndra — Professional "Hire Me" Website

A polished, single-page professional website for Chawndra, an Account Executive open to new opportunities.

## Stack
- **Runtime:** Node.js 20
- **Server:** Express (serves static files from `/public`)
- **Frontend:** Vanilla HTML/CSS/JS (no framework)
- **Fonts:** Inter + Playfair Display (Google Fonts)

## How to run
```
node server.js
```
Runs on port 5000. The workflow "Start application" handles this automatically.

## Project structure
```
├── server.js          # Express server (serves /public)
├── public/
│   ├── index.html     # Full single-page site
│   ├── style.css      # All styles (design tokens, layout, responsive)
│   └── main.js        # Nav, scroll, form, fade-in animations
└── package.json
```

## Sections
1. **Hero** — Name, status tag, headline, CTA button
2. **Roles & Employment Types** — Two-column checklist cards
3. **Work Style Banner** — Onsite / Hybrid / Remote strip
4. **Nutshell + Skills** — Bio paragraph + skill pills
5. **Stats Strip** — 4 highlight numbers
6. **10 Ways You Can Help** — Grid of action cards
7. **Contact** — Info + contact form (currently client-side only)
8. **Footer**

## User preferences
- Corporate & professional visual style (navy, gold, white)
- Content owner: Chawndra (B2B enterprise / startup Account Executive)
- Contact form is currently client-side only — needs a real backend or service (Formspree, EmailJS, etc.) to actually send emails
