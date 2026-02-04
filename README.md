# The Way of It

A website combining Zen meditation with The Work of Byron Katie.

**Live site:** https://thewayofit.com

## Overview

This is a static website for Eduardo Kyōzen Zambrano's workshops and retreats that integrate Zen practice with The Work of Byron Katie. The site is hosted on GitHub Pages with a custom domain.

## Pages

- **index.html** — Home page with introduction, Bernie Glassman quote, The Four Questions, and workshop offerings
- **about.html** — About Eduardo, background in Zen and The Work
- **workshops.html** — Information about workshops and retreats
- **shoyoroku-45.html** — Study materials for Shoyoroku Case 45 (Hossen talk preparation for July 2025 at SLO Zen Circle)
- **resources.html** — Recommended reading and links for The Work and Zen
- **contact.html** — Contact information

## Structure

```
website/
├── css/
│   └── style.css          # Main stylesheet (Zen-inspired design)
├── images/
│   ├── enso.svg           # Calligraphy enso (Wikimedia Commons, public domain)
│   ├── mini-me-with-fan.png   # Avatar for Shoyoroku page
│   └── workandmeditation.jpg
├── resources/
│   ├── shoyoroku_45.pdf
│   └── the-sutra-of-complete-enlightenment.pdf
├── index.html
├── about.html
├── workshops.html
├── shoyoroku-45.html
├── resources.html
├── contact.html
├── CNAME                  # Custom domain configuration
└── README.md
```

## Design

- **Fonts:** Crimson Pro (serif), Inter (sans-serif)
- **Colors:** Ink wash inspired palette — ink (#1c1917), stone (#57534e), mist (#a8a29e), sand (#e7e5e4), paper (#fafaf9)
- **Motif:** Enso (Zen circle) as subtle background element in hero sections
- **Style:** Minimal, spacious, contemplative

## Hosting

- **Platform:** GitHub Pages
- **Repository:** https://github.com/eduardo-zambrano/thewayofit
- **Custom Domain:** thewayofit.com (DNS managed via GoDaddy)
- **HTTPS:** Enabled via GitHub Pages

## DNS Configuration (GoDaddy)

| Type  | Name | Value                      |
|-------|------|----------------------------|
| A     | @    | 185.199.108.153            |
| A     | @    | 185.199.109.153            |
| A     | @    | 185.199.110.153            |
| A     | @    | 185.199.111.153            |
| CNAME | www  | eduardo-zambrano.github.io |

## Deployment

Push to the `main` branch to deploy:

```bash
git add .
git commit -m "Your commit message"
git push
```

Changes typically appear on the live site within 1-2 minutes.

## License

Content © 2025 Eduardo Kyōzen Zambrano

Enso image: Public domain (CC0) from Wikimedia Commons
