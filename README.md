# Inshape Fitness — Website

A world-class, responsive website for **Inshape Fitness**, a premium strength & fitness studio in **Bharatpur, Rajasthan, India**. Two pages: the main landing page and a supplements store.

![Inshape Fitness](./assets/hero.svg)

## ✨ Features

- Cinematic hero with real gym photography, Ken Burns motion & scroll progress bar
- Sticky navigation + mobile slide-in menu; premium dark theme with orange→ember gradients and filmic grain
- Sections: About, Programs (Strength, Group HIIT & Cardio, Personal Training, Functional, Zumba, Aerobics), "Step Inside" gallery, How It Works, Trainers, Membership pricing (₹ INR), Facilities, Testimonials, FAQ, and a WhatsApp Book-a-Trial form + location map
- **Supplements Store page** (`store.html`) — researched, evidence-based details for pre-workout, creatine, whey protein, mass gainer, L-carnitine, multivitamins and fish oil, with per-product WhatsApp enquiry links and a goal-based guide
- Lightweight, no build step; every image is a separate file in `assets/`

## 📁 Structure

```
inshape-fitness/
├── index.html          # main landing page
├── store.html          # supplements store page
├── README.md
└── assets/             # images (16 files)
    ├── hero.svg              ├── program-functional.svg
    ├── about-lounge.svg      ├── program-zumba.svg
    ├── gallery-cardio.svg    ├── program-aerobics.svg
    ├── gallery-strength.svg  ├── cta-banner.svg
    ├── gallery-reception.svg ├── trainer-gaurav.svg
    ├── program-strength.svg  ├── trainer-anirudh.svg
    ├── program-hiit.svg      ├── store-hero.svg
    ├── program-pt.svg        └── store-cta.svg
```

> Images are stored as individual optimized files (SVG-wrapped JPEGs) so they render natively in browsers and on GitHub Pages. Only external dependency is the Google Maps embed in the Location section.

## 💳 Membership (current rate card)

| Duration | Men | Women | Couple (M+F) |
|---|---|---|---|
| 1 Month | ₹2,000 | ₹1,500 | ₹3,500 |
| 3 Months | ₹5,000 | ₹3,600 | ₹8,500 |
| 6 Months | ₹8,500 | ₹6,000 | — |
| 12 Months | ₹13,000 | — | — |

Personal Training — ₹5,000/month · Day Pass — ₹200/day

## 👥 Team

- **Gaurav Saini** — Co-Founder · Trainer — 📞 76650 30635 (also handles supplement orders)
- **Anirudh Singh** — Co-Founder · Trainer — 📞 85600 93466

## 🧴 Supplements store

The Book-a-Trial form and all supplement enquiries open WhatsApp to Gaurav with a pre-filled message. Product info is general guidance (evidence-based, sourced on the page) — not medical advice.

## 🚀 Run locally

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 🌐 Deploy with GitHub Pages (free)

1. **Settings → Pages** → Source: `main` branch, `/ (root)` → **Save**
2. Live at `https://sainihiteshscientist-gif.github.io/inshape-fitness/`

## 🖊️ Still to add (currently placeholders)

- 📍 Exact street address + PIN code
- ✉️ Email address and social media links
- 🕒 Exact opening hours (current times are assumed)

---

Get In Shape. Stay Inshape. — Bharatpur, Rajasthan 🇮🇳
