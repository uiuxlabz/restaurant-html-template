# OLIVO — Trattoria & Wood-Fired Kitchen Website Template

**OLIVO** is a premium, handcrafted HTML template for neighbourhood trattorias, wood-fired restaurants, and natural-wine bars. Built around a single, stubborn idea — *good food, cooked over fire, made to share* — it pairs a warm editorial layout with a market-driven menu system, a reservation flow, and a slow-food brand voice that feels like a real place rather than a theme.

It is a complete, standalone front-end: pure HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no dependencies. Open `index.html` and it works.

---

## What's inside

- **4 fully designed pages** — Home, Story, Menu, and Visit — each with its own rhythm and a consistent design language.
- **Topic-native design system** — terracotta, ember, and olive tones drawn from fire, glaze, and the garden; Playfair Display for menus and Nunito Sans for the everyday voice.
- **Market-driven menu** — dish rows grouped by course (Antipasti, Pasta, From the fire, Dolci) with prices, vegetarian tags, and a photo gallery per section.
- **Reservation form** — date, time, party size, and notes, with inline validation and a confirmation message (no alert pop-ups).
- **Story & team** — the origin of the oven, four quiet kitchen rules, and the people by the pass.
- **Motion with restraint** — scroll reveals, count-up stats, and a slow marquee, all disabled under `prefers-reduced-motion`.
- **Responsive & accessible** — mobile drawer nav, semantic markup, visible focus states, and AA-contrast text.

All photography is the restaurant's own — wood-fired dishes, the dining room, the team, and guest portraits — so the meaning stays exactly where it belongs.

---

## Pages

| Page | File | What it shows |
|------|------|---------------|
| Home | [`index.html`](index.html) | Hero by the fire, "Why OLIVO" promises, signature plates, the room, guest voices, CTA. |
| Story | [`about.html`](about.html) | How it began, four kitchen rules, the team, and a stats band. |
| Menu | [`menu.html`](menu.html) | Course-by-course menu with prices, vegetarian tags, dish photography, and opening hours. |
| Visit | [`contact.html`](contact.html) | Reservation form, location, hours, private-hire info, and the room. |

---

## Quick start

1. Download or clone this folder.
2. Open `index.html` in any browser — that's it.
3. To preview locally with live reload, run `python3 -m http.server` in this folder and visit `http://localhost:8000`.

```
restaurant-html-template/
├── index.html
├── about.html
├── menu.html
├── contact.html
├── assets/
│   ├── css/base.css
│   ├── js/main.js
│   └── img/   (original restaurant photography)
└── README.md
```

---

## Customization

- **Colors & type** — every value lives in CSS custom properties at the top of `assets/css/base.css` (`--primary`, `--accent`, `--bg`, `--font-display`, …). Recolor the whole site from one block.
- **Copy** — all text is plain HTML; swap names, prices, and the story in minutes.
- **Menu** — each dish is a single `.dish` row (name, description, price, optional `V` tag). Add or remove rows freely.
- **Images** — replace files in `assets/img/` keeping the same names, or point the `src` attributes at your own.
- **Reservation** — the form is front-end only. Point `data-form` at your booking endpoint or email handler to go live.

---

## Tech stack

- HTML5 (semantic, accessible)
- CSS3 (custom properties, grid, modern resets)
- Vanilla JavaScript (IntersectionObserver reveals, count-up, nav, form validation)
- Google Fonts: Playfair Display + Nunito Sans

No Tailwind, Bootstrap, React, or build tooling. The only network request is the font stylesheet.

---

## SEO keywords

trattoria website template, wood-fired restaurant, Italian restaurant HTML template, restaurant menu template, reservation form template, slow food, natural wine bar, neighbourhood restaurant, handmade pasta, food template, cafe HTML, culinary landing page.

---

## License

Free to use for personal and commercial projects. Attribution is appreciated but not required. The original photography is licensed for use within this template.

---

Let's Build Something Together 🚀
https://tally.so/r/q4q1L9
