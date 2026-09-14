# Specialty Subcontractors Landing Page

Static, mobile-first landing page for Van De Putte Advisors (commercial & specialty subcontractor M&A).

Private Atelier redesign — cream paper, ink text, deep olive primary CTAs, brass photo frames and chapter labels. Construction / specialty-trade photography; real headshots for Paul and Daniel.

## How to open

Open `index.html` in a browser:

- Double-click `/workspace/specialty-subcontractors-landing/index.html`, or
- From this folder: `xdg-open index.html` (Linux) / `open index.html` (macOS), or
- Serve locally if you prefer: `python3 -m http.server 8080` then visit `http://localhost:8080`

No build step. CSS is in `styles.css`. Form submit is stubbed in a small inline script (`preventDefault` + thank-you message).

## Files

- `index.html` — semantic page structure and copy
- `styles.css` — cream / ink / olive / brass styles + Newsreader + Source Sans 3
- `images/` — Unsplash construction / trade photos + real founder headshots (`paul.jpg`, `daniel.jpg`)
- `README.md` — this file

## Niche focus

**Include:** glazing, flooring, concrete, fencing, paving, welding, low-voltage, commercial painting  
**Not pitched as niches:** HVAC, plumbing, roofing, fire protection (called out as aggregator targets in problem copy)

## Design notes

- Sticky cream header: brand text only (no brass/gold circle mark) + “Talk with us”
- Chapter labels: Private counsel / Where value leaks / The work / Fit / Let’s talk
- Hero photo sits in a thick `.brass-frame` (0.95rem brass padding/gradient); caption “Succession, done properly” sits underneath the frame
- Problem + What we do share cream-deep `#F0EAD9`
- After bios + close line: centered chapter-break “Reach out to Paul and Daniel” (no arrow) in the middle of a horizontal rule
- Offer CTA is dark/black ink, not white
- Primary solid buttons only in hero + form submit; mid-page CTAs are underlined text links
- Headshots top-aligned (`object-position: center top`) with equal 4:5 crop
- Asymmetric layouts on tablet+ (offset bios, staggered photos)

## Palette

| Token | Hex | Use |
|-------|-----|-----|
| Cream | `#F7F3EA` | Page ground |
| Parchment | `#EFE9DD` | Alternating bands |
| Ink | `#1F1C18` | Headlines / primary text |
| Olive | `#2C4214` | Primary CTAs / links |
| Brass | `#B8924A` | Accents, focus rings |

## Typography

- Display / headlines: **Newsreader**
- Body / UI: **Source Sans 3**

## Photo credits (Unsplash License)

Free Unsplash photos downloaded into `images/`. Prefer linking back to the photographer when you publish:

| File | Source |
|------|--------|
| `hero-construction.jpg` | [unsplash.com/photos/photo-1541888946425-d81bb19240f5](https://unsplash.com/photos/photo-1541888946425-d81bb19240f5) |
| `concrete-work.jpg` | [unsplash.com/photos/photo-1589939705384-5185137a7f0f](https://unsplash.com/photos/photo-1589939705384-5185137a7f0f) |
| `site-scaffolding.jpg` | [unsplash.com/photos/photo-1503387762-592deb58ef4e](https://unsplash.com/photos/photo-1503387762-592deb58ef4e) |
| `commercial-fitout.jpg` | [unsplash.com/photos/photo-1562259949-e8e7689d7828](https://unsplash.com/photos/photo-1562259949-e8e7689d7828) |

Founder photos: `images/paul.jpg` and `images/daniel.jpg` (copied from job-shop landing; real headshots).
