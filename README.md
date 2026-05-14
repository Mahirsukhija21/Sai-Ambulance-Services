# 🚑 Sai Ambulance Services

A fully-featured, production-ready emergency ambulance booking website built as a single-page application in pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

**[🌐 Live Website →](https://Mahirsukhija21.github.io/Sai-Ambulance-Services)**

---

## What It Does

Sai Ambulance Services is a complete web presence for a 24/7 emergency medical transport company. It allows patients and families to:

- Learn about available ambulance types (ACLS, BCLS, ICU)
- Book an ambulance via a full enquiry form (wired to Web3Forms for real email delivery)
- Reach the team instantly via phone, WhatsApp, or email
- Understand the full range of services offered

---

## Features

**Multi-page SPA navigation** — Four pages (Home, About, Services, Contact) with smooth animated transitions, no page reloads, and active nav state tracking.

**Working booking form** — Captures patient name, phone, city, service type, condition, destination hospital, and additional notes. Submits via Web3Forms API and shows a success message on completion.

**Fleet detail section** — Full breakdown of all three ambulance types with equipment lists, key advantages, and descriptions:
- ACLS (Advanced Cardiac Life Support) — for cardiac emergencies
- BCLS (Basic Cardiac Life Support) — frontline emergency response
- ICU Ambulance — mobile intensive care unit

**Fully responsive** — Mobile-first layout that adapts from 400px to desktop. Collapsing grids, adjusted typography, and touch-friendly buttons throughout.

**Real contact integration** — Two phone lines, WhatsApp booking link, and email address wired up with `tel:` and `mailto:` links throughout.

---

## Tech Stack

| Layer | Tech |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, CSS Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Form delivery | Web3Forms API |
| Fonts | Google Fonts (Playfair Display, DM Sans) |
| Hosting | GitHub Pages |

No build tools. No npm. No frameworks. Opens directly in any browser.

---

## Project Structure

```
Sai-Ambulance-Services/
├── index.html    # Entire application — markup, styles, and JS in one file
└── README.md
```

The site runs as a single HTML file (~643 lines) with embedded CSS and JavaScript. All four "pages" are rendered in the DOM simultaneously and shown/hidden via class toggling, with CSS transitions handling the animations.

---

## Key Design Decisions

**Single-file architecture** — Keeps deployment dead simple (GitHub Pages, any static host, even just sharing the file). No build pipeline needed.

**SPA without a framework** — Page transitions are handled with a `showPage()` function that toggles CSS classes and `requestAnimationFrame` for smooth fade-in animations — no React, no Vue.

**Form without a backend** — Web3Forms handles email delivery, meaning the site has zero server costs while still being fully functional for real booking enquiries.

---

## Author

**Mahir Sukhija** — [@Mahirsukhija21](https://github.com/Mahirsukhija21)
