# 🎞️ Narrative Deck — Horizontal Scroll Story Layout

> **Day 9 Project  
> Tech Focus: `scroll-snap`, `sticky layout`, `container queries`, responsive UI

---

## 🔥 Overview

**Narrative Deck** is a horizontal scroll-based storytelling layout inspired by Notion, Stripe, and modern product marketing sites.

Each slide presents a distinct visual narrative, combining crisp typography with responsive visuals in a scrollable timeline format.  
The layout adapts seamlessly across devices using **CSS container queries**, and scroll bars are hidden for a premium feel.

---

## 🧪 Browser Support

> ⚠️ This layout is **best experienced in Chrome**.  
> Some features like `view-timeline` and scroll animations are still experimental and may not work in Firefox or Safari yet.  
> Chrome ensures smooth performance and full feature compatibility.

---

## 🧱 Features

- **Horizontal scroll with `scroll-snap-type: x mandatory`**
- **Container-based responsiveness** using `@container` + `cqw`, `cqh`, `cqi` units
- **Blurred glass cards** with backdrop filter
- **Mobile-optimized stacking via `flex-direction: column-reverse`**
- **Cross-browser scrollbar hiding** (Webkit + Firefox)
- Scroll-anchored content pacing for storytelling
- Minimalist, modern dark mode palette with strong contrast

---

## 🚀 Tech Stack

- HTML5  
- CSS3 (Vanilla, no frameworks)  
- CSS Container Queries  
- `scroll-snap`, `backdrop-filter`, `clamp()`  

---

## 📱 Responsiveness

- Breakpoint-free, fluid layout using container queries
- Slide content adapts using `max-inline-size`, `cqw`, and `min()` scaling
- Designed primarily for desktop, but clean fallback for mobile via vertical stacking

---

## 🌐 Live Demo

🔗 [View Live Project](https://narrative-deck.vercel.app)


