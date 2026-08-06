# Nyan Linnhtet · Portfolio Website

A single-page, animation-rich developer portfolio built with vanilla HTML, CSS, and JavaScript — styled with Tailwind CSS (CDN) and finished with custom glassmorphism, particle backgrounds, and micro-interactions.

**Live demo:** _add your deployed link here_

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

---

## ✨ Features

- **Dark / Light theme** — toggle with persistent CSS variable theming (no flash of unstyled content)
- **Animated loading screen** — typewriter intro, progress bar, and status log
- **Custom cursor** — dot + ring cursor with hover states (desktop only)
- **Canvas backgrounds** — animated constellation network and floating code-snippet particles
- **3D glitch avatar** — mouse/touch-reactive tilt, RGB split, scanlines, and click ripple/shatter effect
- **Tilt project & journey cards** — mouse-tracking 3D tilt with gradient border glow
- **Animated journey timeline** — scroll-driven progress line with a live position marker
- **Scroll-based UI** — reveal-on-scroll sections, active nav-link highlighting, scroll progress bar, back-to-top button
- **Working contact form** — submits via [Formspree](https://formspree.io/), with success/error toast notifications
- **Fully responsive** — mobile menu, adaptive layouts, and `prefers-reduced-motion` support

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Markup / Styling | HTML5, Tailwind CSS (CDN, JIT config), custom CSS (glassmorphism, keyframe animations) |
| Fonts & Icons | Google Fonts (Space Grotesk, Inter, JetBrains Mono), Devicon, Simple Icons |
| Scripting | Vanilla JavaScript (ES6+, no framework) |
| Form Backend | Formspree |
| Rendering | HTML5 Canvas (constellation + particle effects) |

No build step, bundler, or package manager is required — the entire site runs from a single `index.html` file.

---

## 📁 Project Structure

```
.
├── index.html        # Full site: markup, styles, and scripts
├── profile.png        # Profile photo used in the About section
├── LICENSE            # MIT License
└── README.md
```

> The project currently lives in one HTML file for simplicity. Feel free to split the `<style>` and `<script>` blocks into separate `styles.css` / `script.js` files if you'd like a more traditional structure.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/NyanLinnhtet2/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Add your profile photo

Place a `profile.png` in the project root (referenced by the About section avatar).

### 3. Open locally

Just open `index.html` in a browser — no server required:

```bash
# or use a simple local server, e.g.
npx serve .
```

### 4. Configure the contact form

The contact form posts to a Formspree endpoint. To use your own:

1. Create a form at [formspree.io](https://formspree.io/)
2. Replace the `action` URL in the `<form id="contactForm">` tag with your own endpoint

```html
<form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

## 🎨 Customization

- **Colors & theme** — edit the CSS custom properties in `:root` and `html:not(.dark)` at the top of the `<style>` block
- **Sections** — Home, About, Projects, Skills, Journey, and Contact are each a `<section>` with its own `id`; reorder or edit freely
- **Projects** — update the `.project-card-enhanced` blocks in the Projects section with your own title, description, tags, and links
- **Skills** — icons are pulled from [Simple Icons](https://simpleicons.org/) and [Devicon](https://devicon.dev/) CDNs; swap the `src` to add/remove technologies
- **Journey timeline** — each `journey-card-enhanced` block represents one milestone; add or remove cards as your story grows

---

## 📱 Browser Support

Built and tested for modern evergreen browsers (Chrome, Firefox, Safari, Edge). Some visual effects (custom cursor, backdrop blur) gracefully degrade on touch devices and older browsers.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE) — you're free to use, copy, modify, and distribute it, including for commercial purposes, as long as the original copyright notice is included. A credit/link back is appreciated but not required.

---

## 📬 Contact

**Nyan Linnhtet (Neon)** — Full Stack Developer
📍 Yangon, Myanmar

- Email: nlinnhtet146@gmail.com
- GitHub: [@NyanLinnhtet2](https://github.com/NyanLinnhtet2)
- Telegram: [@N30N2005](https://t.me/N30N2005)
