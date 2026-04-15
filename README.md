# ⚡ TejendraPresents

A sleek, dark-themed presentation hub for Cloud Computing & Cybersecurity — built with pure HTML, CSS, and JavaScript.

![Status](https://img.shields.io/badge/status-live-00d4ff?style=flat-square)
![Tech](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20JS-7b2ff7?style=flat-square)
![Deploy](https://img.shields.io/badge/deploy-Vercel-000?style=flat-square&logo=vercel)

---

## 🎯 About

**TejendraPresents** is a personal presentation portal where Tejendra shares curated presentations on Cloud Computing architectures and Cybersecurity case studies. The site features a cyberpunk-inspired design with glassmorphism, animated particle backgrounds, and neon accents.

## 📂 Presentations

| # | Title | Category | Link |
|---|-------|----------|------|
| 1 | Adobe Cloud Services Architecture | ☁️ Cloud Computing | [View →](https://www.canva.com/design/DAHG8M1KaoU/p-xVaGuPTkZzXy61FISFiQ/view?utm_content=DAHG8M1KaoU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd24e0a34c9#2) |
| 2 | Arup: A Cybersecurity Case Study | 🛡️ Cybersecurity | [View →](https://www.canva.com/design/DAHG8XjznUU/AsvkEIAqwbFcOQ1qKQIBAw/view?utm_content=DAHG8XjznUU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hbc33836c29#2) |

## 🛠️ Tech Stack

- **HTML5** — Semantic structure with SEO meta tags
- **CSS3** — Custom properties, glassmorphism, gradient animations, responsive breakpoints
- **Vanilla JavaScript** — Canvas particle system, IntersectionObserver scroll reveals, mobile nav
- **Google Fonts** — Inter + JetBrains Mono

## 📁 Project Structure

```
TejendraPresenting/
├── index.html        # Single-page website
├── css/
│   └── style.css     # Design system & all styles
├── js/
│   └── main.js       # Particles, animations, interactions
├── vercel.json       # Vercel deployment config
├── package.json      # Project metadata
└── README.md
```

## ✨ Features

- 🌑 Dark cyberpunk aesthetic with neon cyan/purple/pink accents
- 🔮 Glassmorphism cards with animated gradient borders on hover
- 🌌 Canvas-based particle network background
- 📱 Fully responsive — hamburger nav on mobile
- ⚡ Zero dependencies — no frameworks, no build step
- 🔒 Security headers configured via `vercel.json`
- 🎨 Custom scrollbar and selection colors

## 🚀 Deployment

### Vercel (Recommended)

**Option 1 — CLI:**

```bash
npx vercel
```

**Option 2 — GitHub Integration:**

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Import Project
3. Select your repo — Vercel auto-detects it as a static site
4. Done! 🎉

### Local Preview

Simply open `index.html` in your browser — no build step required.

## 🧑‍💻 Adding New Presentations

To add a new presentation, copy a card block inside the relevant section in `index.html`:

```html
<div class="pres-card cloud-card reveal reveal-delay-1">
  <div class="card-icon">
    <!-- SVG icon here -->
  </div>
  <div class="card-badges">
    <span class="badge cloud">Cloud Computing</span>
    <span class="badge platform">Canva</span>
  </div>
  <h3 class="card-title">Your Presentation Title</h3>
  <p class="card-description">Brief description of the presentation.</p>
  <a href="YOUR_LINK" target="_blank" rel="noopener noreferrer" class="card-link">
    View Presentation →
  </a>
</div>
```

> Use `cloud-card` / `badge cloud` for Cloud Computing, or `cyber-card` / `badge cyber` for Cybersecurity.

---

<p align="center">Built with 💜 by <strong>Tejendra</strong></p>
