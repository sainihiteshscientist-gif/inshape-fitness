# Inshape Fitness — Landing Page

A world-class, responsive landing page for **Inshape Fitness**, a premium strength & fitness studio in **Bharatpur, Rajasthan, India**.

![Inshape Fitness](./assets/hero.svg)

## ✨ Features

- Cinematic hero with real gym photography, Ken Burns motion & scroll progress bar
- Sticky navigation + mobile slide-in menu
- Animated stat counters and scroll-reveal animations
- Sections: About, **Programs** (Strength, Group HIIT & Cardio, Personal Training, Functional, **Zumba**, **Aerobics**), "Step Inside" photo gallery, **How It Works**, **Trainers**, **Membership pricing** (₹ INR), Facilities, **Testimonials**, **FAQ**, CTA, and a **Book-a-Free-Trial enquiry form** + location map
- High-energy premium aesthetic — bold display type, dark theme, orange→ember gradient accents, filmic grain
- Lightweight `index.html` (HTML + CSS + vanilla JS, no build step); every image is a separate file in `assets/`

## 📁 Structure

```
inshape-fitness/
├── index.html          # the landing page
├── README.md
└── assets/             # all photography, one file per image
    ├── hero.svg
    ├── about-lounge.svg
    ├── gallery-cardio.svg
    ├── gallery-strength.svg
    ├── gallery-reception.svg
    ├── program-strength.svg
    ├── program-hiit.svg
    ├── program-pt.svg
    ├── program-functional.svg
    ├── program-zumba.svg
    ├── program-aerobics.svg
    ├── cta-banner.svg
    ├── trainer-gaurav.svg
    └── trainer-anirudh.svg
```

> Images are stored as individual optimized files (SVG-wrapped JPEGs) so they render natively in browsers and on GitHub Pages. The only external dependency is the Google Maps embed in the Location section.

## 💳 Membership (current rate card)

| Duration | Men | Women | Couple (M+F) |
|---|---|---|---|
| 1 Month | ₹2,000 | ₹1,500 | ₹3,500 |
| 3 Months | ₹5,000 | ₹3,600 | ₹8,500 |
| 6 Months | ₹8,500 | ₹6,000 | — |
| 12 Months | ₹13,000 | — | — |

Personal Training — ₹5,000/month · Day Pass — ₹200/day

## 👥 Team

- **Gaurav Saini** — Co-Founder · Trainer — 📞 76650 30635
- **Anirudh Singh** — Co-Founder · Trainer — 📞 85600 93466

## 🚀 Run locally

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 🌐 Deploy with GitHub Pages (free)

1. **Settings → Pages**
2. **Source:** `main` branch, `/ (root)`, then **Save**
3. Live at: `https://sainihiteshscientist-gif.github.io/inshape-fitness/`

## 🖊️ Still to add (currently placeholders)

- 📍 Exact street address + PIN code
- ✉️ Email address and social media links
- 🕒 Exact opening hours (current times are assumed)

---

Get In Shape. Stay Inshape. — Bharatpur, Rajasthan 🇮🇳
