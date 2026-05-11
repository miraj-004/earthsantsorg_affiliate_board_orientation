# 🐜 Earth's Ants — Affiliate Board Orientation
### Interactive Presentation · Operation GreenForce · Season 6.0

---

## 📋 Overview

This is a fully interactive, single-file HTML presentation built for the **Earth's Ants Affiliate Board Orientation**. It covers everything a new Affiliate Member needs to know — from their role and responsibilities to org guidelines, code of conduct, and policy snapshots — wrapped in an engaging, quiz-driven experience that ends with a surprise gift box. 🎁

---

## 🗂️ Slide Structure

| # | Slide Title | What's Inside |
|---|---|---|
| 1 | **Hero — Welcome** | Orientation intro, Ant Philosophy cards, confetti on load |
| 2 | **Your Role** | Affiliate Member definition, 3 contribution paths, Flexible Workflow model |
| 3 | **Mission & Purpose** | 6 organizational pillars — Awareness, Advocacy, Research, Biodiversity, Sustainability, Renewable Energy |
| 4 | **Guidelines** | Punctuality, Confidentiality, Communication Protocol, Digital Ethics, Efficiency, Recommendation Policy |
| 5 | **Quiz #1** | Interactive policy puzzle — recommendation letter scenario |
| 6 | **Quiz #2 & #3** | Digital ethics scenario + professional self-introduction scenario |
| 7 | **Code of Conduct** | Side-by-side Do's ✅ and Don'ts ❌ |
| 8 | **Policy Snapshot** | Key numbers: 6 months, 50%, 2 weeks, 5 days, 3 steps, 0 salary |
| 9 | **Surprise Gift Box 🎁** | Click-to-open animated box with confetti explosion and welcome message |

---

## ✨ Features

- **Single HTML file** — no dependencies, no install, just open in any browser
- **Smooth slide transitions** with fade + translate animations
- **Keyboard navigation** — use `←` `→` arrow keys to move between slides
- **Click navigation** — Prev/Next buttons and dot indicators at the bottom
- **Interactive quizzes** — click an option to get instant right/wrong feedback
- **Confetti burst** on the hero slide (load) and gift box slide (click)
- **Animated gift box** — lid flies open with a spring animation on click
- **Scrollable slides** for content-heavy sections
- **Fully self-contained** — Google Fonts loaded via CDN, everything else is inline

---

## 🚀 How to Use

### Open Locally
```bash
# Just double-click the file, or:
open earths_ants_orientation.html
```

### Open in Browser
Drag and drop `earths_ants_orientation.html` into any modern browser (Chrome, Firefox, Edge, Safari).

### Present Full Screen
Press `F11` (Windows/Linux) or `Cmd + Ctrl + F` (Mac) for full-screen presentation mode.

### Navigate
| Action | How |
|---|---|
| Next slide | `→` arrow key or **NEXT →** button |
| Previous slide | `←` arrow key or **← PREV** button |
| Jump to slide | Click any dot in the nav bar |
| Answer quiz | Click any option card |
| Open gift box | Click the box on Slide 9 |

---

## 🎨 Design System

| Property | Value |
|---|---|
| Background | `#080c08` (near black) |
| Primary accent | `#6bff8a` (pastel neon green) |
| Surface | `#0f1a10` |
| Border | `#1e3a25` |
| Text | `#e8ffe8` |
| Muted text | `#4a7a52` |
| Heading font | Bebas Neue |
| Body font | DM Sans |
| Mono font | Space Mono |

---

## 📁 File Info

```
earths_ants_orientation.html    ← The entire presentation (single file)
README.md                       ← This file
```

---

## 🛠️ Customization

### Change member names / roles (Slide 2, 3, etc.)
Search for the relevant text in the HTML and update directly.

### Add a new slide
1. Copy an existing `<div class="slide" id="sN">` block
2. Update the `id` to the next number (e.g. `s10`)
3. Update `const TOTAL = 9;` in the `<script>` to `10`

### Change colors
All colors are defined as CSS variables at the top of the `<style>` block:
```css
:root {
  --green: #6bff8a;      /* change accent color here */
  --black: #080c08;      /* change background here */
}
```

### Update quiz questions
Find the `id="q1opts"` (or `q2opts`, `q3opts`) sections and edit the `<span>` text inside each `.quiz-option`. Mark the correct answer with `'correct'` in the `onclick` attribute.

---

## 📌 Notes

- This presentation is intended for **internal orientation use only**
- Content is based on the official Earth's Ants Affiliate Member offer letter and organizational guidelines
- All quiz answers align with the **Earth's Ants Constitution and CEC policies**
- No backend or server required — 100% static HTML

---

## 🌿 About Earth's Ants

> *"Think, Live and Work Like Ants"*

Earth's Ants is a nationally and globally recognized youth-led environmental organization operating under the **Ant Philosophy** of Unity, Discipline, and Efficiency. Operation GreenForce Season 6.0 marks a new chapter in mobilizing passionate young individuals to protect, innovate, and lead in the environmental sector.

**Central Executive Council (CEC)**
Earth's Ants · Season 6.0 · 10 May 2026

---

*Built with 💚 for the planet — and for the ants.*
