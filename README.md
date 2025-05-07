# 🖼️ Infinite Image Gallery - Draggable!

> A scrollable, draggable image grid with inertia, grid virtualization, and interactive expansion. Built with vanilla JavaScript, GSAP, and SplitType.

---

## 🖼 Preview

![Gallery Demo](media/infinite-gallery-preview.gif)

---

## ⚙️ Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/suzubu/infinite-image-gallery.git

# 2. Open the HTML file in your browser
open index.html
```

> No build tools needed — just HTML, CSS, and JS.

---

## ✨ Features

- 🧭 Infinite scrolling grid with dynamic item rendering
- 🖱 Drag-based momentum navigation for desktop and mobile
- ✨ GSAP-powered zoom-in expansion on image click
- 🧠 Grid virtualization for performance (renders only what's visible)
- 🔠 Animated title reveals using SplitType and staggered entrance

---

## 🧠 Technical Notes

### Core Files
- `index.html` — Base layout and DOM elements
- `script.js` / `new.js` — Handles drag, scroll, and grid interactivity
- `items.js` — Array of title strings used for project labels
- `styles.css` — Layout and hover/click styling
- `media/` — Folder for your GIF demo and images

### Animation Stack
- [GSAP](https://greensock.com/gsap/)
- [SplitType](https://www.npmjs.com/package/split-type)
- [CustomEase](https://greensock.com/docs/v3/Eases/CustomEase)

---

## 📚 Inspiration / Credits

- Grid concept and draggable inertia inspired by [Niklas von Hertzen](https://github.com/niklasvh/infinite-canvas)
- Expansion/zoom feel influenced by [Framer motion galleries](https://www.framer.com/motion/)
- Staggered text motion style from [Studio Freight](https://studiofreight.com/)

---

## 📂 Folder Structure

```bash
infinite-gallery/
├── index.html
├── script.js
├── new.js
├── items.js
├── styles.css
├── media/
│   └── infinite-gallery-preview.gif
└── README.md
```

---

## 📜 License

MIT — free to use, learn from, and remix.

---

## 🙋‍♀️ Author

Created by [suzubu](https://github.com/suzubu)
