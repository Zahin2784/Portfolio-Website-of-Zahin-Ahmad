# Zahin Ahmad — Personal Portfolio Website

A single-page, editorial-style portfolio built entirely in one self-contained HTML file — no build tools, no dependencies beyond Google Fonts. Designed with large expressive serif/sans typography, scroll-triggered reveal animations, and a warm, muted charcoal-and-brass color palette.

**🔗 Live Site:** _add your deployed link here_

---

## ✨ Overview

This is `index.html` — a personal portfolio for **Zahin Ahmad**, a Computer Science and Engineering (CSE) undergraduate at the **Islamic University of Technology (IUT)**. It presents education, skills, achievements, and projects as a scroll-based narrative, aimed at recruiters, academic collaborators, and fellow developers.

### Design Inspiration
- **Layout & Interaction:** Inspired by [rafaelkurosawa.com](https://rafaelkurosawa.com) — full-viewport hero, sticky section labels, minimalist nav, and scroll-reveal motion.
- **Color Palette:** Inspired by [samuclima.com](https://samuclima.com/en) — deep ink backgrounds with brass/clay accents instead of typical bright "tech portfolio" colors.

---

## 🧩 Sections

| Section | Details |
|---|---|
| **Hero** | Full-viewport intro with name, role, and CTA |
| **About** | Narrative bio |
| **Education** | IUT (current, 3rd year), Saint Joseph HSC, Bangladesh International SSC — Golden GPA 5.00 across PECE/JSC/SSC/HSC |
| **Skills** | Grouped tag lists: Languages, Tools & Platforms, Graphics Design |
| **Achievements** | ICPC Asia Dhaka Regional 2025, LEDP, IUT contest placements, board exam honors |
| **Projects** | Arbitrator, Agriculture Import/Export site, COA Cache Controller FSM Simulator — each linking out to GitHub |
| **Contact** | Facebook, Instagram, LinkedIn, GitHub |

---

## 🛠️ Tech Stack

- **Pure HTML5, CSS3, and vanilla JavaScript** — a single `index.html` file, no framework or build step
- **CSS custom properties** for a centralized design token system (colors, type scale, spacing, easing)
- **Google Fonts:** [Fraunces](https://fonts.google.com/specimen/Fraunces) (serif, display) + [Manrope](https://fonts.google.com/specimen/Manrope) (sans, body)
- **IntersectionObserver** for scroll-triggered fade/slide-in reveals, with a timeout safety net so content never gets stuck hidden
- **CSS-only** scroll-adaptive navbar (`.is-scrolled` state toggled on scroll)
- No external JS libraries or CSS frameworks

---

## 🎨 Design Tokens

| Token | Value | Use |
|---|---|---|
| `--ink` | `#17140F` | Primary dark background |
| `--paper` | `#F3EEE1` | Warm ivory band |
| `--text` | `#EDE6D5` | Body text on dark |
| `--brass` | `#C4974F` | Primary accent |
| `--clay` | `#9C5B3C` | Secondary accent |
| `--serif` | Fraunces | Headings / display |
| `--sans` | Manrope | Body text |

---

## ♿ Accessibility & Performance

- Skip-to-content link for keyboard users
- Visible `:focus-visible` outlines throughout
- `prefers-reduced-motion` respected — animations disabled for users who request it
- Semantic sectioning (`<nav>`, `<main>`, `<section>`, `<footer>`) with `id` anchors for direct linking
- All external links use `target="_blank" rel="noopener noreferrer"`
- Inline SVG favicon (no extra image request)
- `og:title` / `og:description` meta tags for clean social link previews

---

## 📱 Responsive Behavior

- Two-column "sticky label + content" layout on desktop, collapsing to a single column on smaller screens (`≤ 820px`)
- Full-screen overlay navigation menu on mobile (`≤ 760px`) with a hamburger toggle, closable via click or `Esc`

---

## 🚀 Getting Started

No build step needed — it's one file.

```bash
# Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git

# Open it directly in a browser
cd <repo-name>
open index.html   # or just double-click the file
```

For live-reload during edits, optionally serve it locally:

```bash
npx serve .
```

---

## 📦 Deployment

Being a single static HTML file, it can be deployed anywhere with zero configuration:
- [GitHub Pages](https://pages.github.com)
- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)

---

## 📂 Project Structure

```
/
└── index.html   ← everything: markup, <style>, and <script> in one file
```

---

## 🔗 Connect

- **GitHub:** [github.com/Zahin2784](https://github.com/Zahin2784)
- **LinkedIn:** [linkedin.com/in/zahin-ahmad-1bb059364](https://linkedin.com/in/zahin-ahmad-1bb059364)
- **Facebook:** [facebook.com/ahmad.zahin.7186](https://facebook.com/ahmad.zahin.7186)
- **Instagram:** [instagram.com/za_hi_n08](https://instagram.com/za_hi_n08)

---

## 📄 Documentation

Full requirements and design rationale for this project are documented in the [Software Requirements Specification (SRS)](./Zahin_Ahmad_Portfolio_SRS.md).

---

## 📜 License

This project is personal portfolio work. Feel free to draw inspiration from the structure, but please do not reuse personal content, photos, or copy identifying details.
