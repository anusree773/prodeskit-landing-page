# 🚀 Prodesk IT — Premium Digital Marketing Agency Landing Page

<div align="center">

![Prodesk IT Banner](screenshots/homepage.png)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**A modern, futuristic digital agency landing page — built with pure HTML, CSS & Vanilla JavaScript.**

[🌐 Live Demo](#) · [📸 Screenshots](#screenshots) · [⚡ Features](#features) · [🛠️ Setup](#setup)

</div>

---

## 📌 Project Overview

**Prodesk IT** is a premium single-file landing page crafted as part of the **Prodesk IT Internship — Week 1 Assignment**. The project focuses on advanced responsive layout techniques, modern CSS animations, glassmorphism design, and interactive vanilla JavaScript — producing a result comparable to agency websites built on Webflow or Framer.

> **No frameworks. No libraries. No shortcuts.** Pure HTML5, CSS3, and Vanilla JS.

---

## ✨ Features

### 🎨 Design & UI
- **Dark / Light Mode** — full theme toggle with `localStorage` persistence
- **Glassmorphism UI** — `backdrop-filter` glass cards across navbar, hero cards, and overlays
- **Animated Gradient Hero** — multi-layered drifting orbs + dot-grid background + noise texture
- **Cinematic Depth** — multi-layer box shadows, inset glows, and layered z-index architecture
- **Premium Typography** — Syne (display) + DM Sans (body) from Google Fonts

### 🖱️ Micro-Interactions
- **Custom Cursor** — glowing dot + lagging ring that scales on hover
- **Mouse Glow Orb** — large radial gradient that follows the cursor with eased lag
- **Service Card Spotlight** — mouse-tracked radial glow follows cursor inside each card
- **3D Tilt Effect** — `perspective()` + `rotateX/Y` on project and testimonial cards

### 🎬 Animations
- **Hero Particles** — 22 floating particles with randomised size, speed, and fade paths
- **Animated Stat Counters** — cubic ease-out count-up triggered by scroll
- **Scroll Reveal** — staggered `translateY` + `opacity` reveals via Intersection Observer
- **Parallax Orbs** — hero background orbs drift at different speeds on scroll
- **Dashboard Bar Chart** — staggered `scaleY` bar grow animation on load
- **Floating Dashboard Cards** — CSS `@keyframes` float loop on hero metric cards

### 🧭 Navigation
- **Sticky Navbar** — shrinks and shadow-elevates on scroll
- **Gliding Pill Indicator** — smooth sliding background pill follows active / hovered nav link
- **Scroll Spy** — active nav link updates automatically as sections enter the viewport
- **Mobile Hamburger Drawer** — slide-in panel with blur backdrop overlay

### 📑 Sections
| # | Section | Highlights |
|---|---------|------------|
| 1 | **Hero** | Animated gradient mesh, live analytics dashboard, floating KPI cards, particles |
| 2 | **Marquee** | Infinite scrolling tech-stack ticker strip |
| 3 | **About** | Image with hover zoom, floating award badge, stat chip |
| 4 | **Services** | 3 cards with spotlight effect, featured badge, hover lift |
| 5 | **Process Timeline** ⭐ | 5-step horizontal timeline, animated connector rail, sequential node activation |
| 6 | **Why Choose Us** | Animated stat counters, icon cards with spring hover |
| 7 | **Recent Projects** | 6 real project cards with image zoom, category chips, overlay reveal |
| 8 | **Testimonials** | Auto-advancing carousel, touch swipe, metrics panel, dot indicators |
| 9 | **CTA** | Gradient background with animated blobs and grid pattern |
| 10 | **Footer** | Giant ghost typography, gradient separator, social icons |

### 📱 Responsiveness
- Fully fluid layout using **CSS Grid** and **Flexbox**
- Breakpoints at `1024px`, `768px`, `600px`, and `480px`
- Mobile hamburger menu with slide-in drawer
- Touch swipe support on testimonial carousel
- Cursor effects disabled on touch devices

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Semantic markup, single-file architecture |
| **CSS3** | Custom properties, Grid, Flexbox, `@keyframes`, `backdrop-filter`, `clip-path` |
| **Vanilla JavaScript** | DOM manipulation, Intersection Observer API, carousel, cursor, parallax |
| **Google Fonts** | Syne (800) + DM Sans (300–600) |
| **Boxicons 2.1.4** | Icon system via CDN |
| **Unsplash** | Real project/team photography via URL |

---

## 📁 Folder Structure

```
prodeskit-landing-page/
│
├── index.html          ← Complete single-file app (HTML + CSS + JS)
├── README.md           ← This file
├── Prompts.md          ← Development prompts and AI collaboration log
└── screenshots/
    └── homepage.png    ← Project screenshot for README
```

---

## ⚡ Setup

No build tools, no dependencies, no `npm install`. Just open and run.

**Option 1 — Direct Open**
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/prodeskit-landing-page.git

# Open in browser
open index.html
# or double-click index.html in your file explorer
```

**Option 2 — Live Server (VS Code)**
1. Install the **Live Server** extension in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. Auto-reloads on any file save

**Option 3 — GitHub Pages**
1. Push to a GitHub repository
2. Go to `Settings → Pages → Source: main / root`
3. Your site will be live at `https://YOUR_USERNAME.github.io/prodeskit-landing-page/`

---

## 📸 Screenshots

> Add screenshots to the `screenshots/` folder and update paths below.

| Dark Mode | Light Mode |
|-----------|------------|
| *(add screenshot)* | *(add screenshot)* |

| Hero Section | Process Timeline |
|--------------|-----------------|
| *(add screenshot)* | *(add screenshot)* |

---

## 🎯 Learning Outcomes

This project demonstrates proficiency in:

- ✅ Responsive multi-breakpoint layout with Grid + Flexbox
- ✅ CSS custom properties (design token system)
- ✅ Advanced CSS animations and `@keyframes`
- ✅ `backdrop-filter` glassmorphism effects
- ✅ Intersection Observer API for scroll-triggered animations
- ✅ Vanilla JavaScript DOM manipulation (no jQuery)
- ✅ `localStorage` for persistent user preferences
- ✅ Touch event handling for mobile carousel
- ✅ Performance-conscious animation (GPU-accelerated transforms)
- ✅ Semantic, accessible HTML5 markup

---

## 🤝 Contributing

This is an internship assignment project. Feedback and suggestions are welcome via issues.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-improvement`
3. Commit changes: `git commit -m 'Add: your improvement'`
4. Push: `git push origin feature/your-improvement`
5. Open a Pull Request

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Anusree Chintala**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_PROFILE)

*Prodesk IT Internship — Week 1 Frontend Assignment*

---

<div align="center">

Made with ❤️ and lots of CSS variables

**⭐ Star this repo if you found it helpful!**

</div>
