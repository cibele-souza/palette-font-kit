# Random Aesthetic Generator

A polished, static **Random Aesthetic Generator** that produces cohesive color palettes and font pairings, with accessibility feedback built in.

This project is designed first as a **front-end / UX portfolio piece** for hiring managers and recruiters, and second as a genuinely useful tool for designers and developers.

Everything runs client-side: no build tools, no frameworks, no servers.

---

## ✨ Features

### 🎨 Color Palettes

- Generates **4–6 color palettes** per shuffle
- Displays HEX values with **click-to-copy** (mouse or keyboard)
- Palette swatches are fully keyboard-navigable

### ♿ Accessibility & Contrast

- Inline **WCAG 2.1 AA contrast checks** for each color
- Checks contrast against **white and black** backgrounds
- Clear pass/fail badges with screen-reader friendly labels
- Helpful explanation of contrast ratings included on the page

### 🔤 Font Pairings

- Curated list of high-quality **Google Fonts** (no bad random combos)
- Heading + body font pairing generated together
- Fonts are **lazy-loaded only when selected**
- Live preview showing headline, paragraph, and button

### 🔁 Controls & Shortcuts

- **Shuffle** palette + fonts together
- Keyboard shortcuts:
   - `Space` → Shuffle
   - `S` → Save current aesthetic
   - `C` → Copy CSS variables

### ⭐ Favorites

- Save complete aesthetics (palette + fonts)
- Stored in `localStorage`
- Re-apply or delete favorites instantly

### 📤 Export Options

- **Copy CSS variables** for colors and fonts
- **Export JSON** for programmatic use

### 🌗 Light / Dark UI

- Light and dark modes for the app shell
- Theme preference persists across reloads
- Generated palettes and preview remain neutral and unaffected

---

## 🧱 Tech Stack

- **HTML5** (semantic, accessible)
- **Modern CSS** (CSS variables, grid, prefers-reduced-motion)
- **Vanilla JavaScript** (no frameworks, no dependencies)
- **Google Fonts** (loaded dynamically)
- **LocalStorage** for persistence

Everything lives in a **single `index.html` file** with embedded `<style>` and `<script>`.

---

## 📁 Project Structure

```text
/
├── index.html   # Full app (HTML + CSS + JS)
└── README.md    # Project documentation
```

---

## 🧠 Design Decisions

- **Curated randomness**: Fonts are selected from a vetted list to guarantee quality pairings.
- **UI neutrality**: The app chrome never alters or styles the generated palette output.
- **Accessibility first**: Contrast checks are visible, explained, and keyboard-friendly.
- **Static by design**: No build step, no server, easy to host anywhere.

Trade-offs and non-obvious logic are documented inline in code comments.

---

## 🎯 Intended Audience

- **Hiring managers & recruiters** evaluating front-end polish and UX thinking
- **Designers & developers** looking for quick palette + font inspiration

---

## 📜 License

Fonts are provided by **Google Fonts** and are subject to their respective licenses.

The project code is intended as a demo / portfolio artifact and may be reused or adapted freely.

---

## 💡 Possible Enhancements

- Shareable URLs encoding palette + font state
- Numeric contrast ratios on hover
- Palette generation based on hue anchors or color theory rules
- Export to design tools (Figma tokens, Tailwind config)

---

Built with care to demonstrate production-ready front-end engineering, accessibility awareness, and thoughtful UX.
