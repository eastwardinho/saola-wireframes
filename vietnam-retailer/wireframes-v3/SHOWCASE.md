# Saola V3 Wireframes — High-Fidelity Mobile Design

**Client:** Saola Vietnam  
**Version:** 3.0  
**Date:** February 17, 2026  
**Designer:** Frank Best (AI-Assisted)

---

## Overview

High-fidelity mobile wireframes for Saola, a Vietnamese lamp retailer. These wireframes are fully styled HTML/CSS prototypes that accurately represent the final brand application.

**Design Philosophy:** Product-first, warm and inviting, unmistakably Vietnamese yet globally refined.

---

## Brand Compliance ✓

| Element | Guideline | Implementation |
|---------|-----------|----------------|
| **Primary Color** | #FFA400 (CTAs only) | ✓ Orange used exclusively for buttons/CTAs |
| **Typography** | Basel Classic (Inter substitute) | ✓ Light headings, Book body text |
| **Tracking** | Headings -50, Body +10, Caps +100 | ✓ Proper letter-spacing applied |
| **Max Colors** | 2 per composition | ✓ Warm cream/blush gradients |
| **Product Photography** | Product as star, glowing, warm | ✓ All renders featured prominently |
| **Margin** | 5% breathing space | ✓ Consistent product spacing |

---

## Pages Included

### 1. Homepage
**File:** `01-homepage-v3.html`  
**Screenshot:** `01-homepage-v3.jpg`

Features:
- Promo strip (free shipping messaging)
- Hero with "Light Up Your Life" tagline
- Best Sellers grid (4 products)
- "Pretty & Posh" collection feature
- Brand story quote section
- Floor lamps feature banner
- Instagram section
- Full footer with navigation

### 2. Shop Page
**File:** `02-shop-v3.html`  
**Screenshot:** `02-shop-v3.jpg`

Features:
- Filter bar (All, Table, Floor, Pendant, New)
- Price range chips
- Sort & view toggle
- Full 12-product grid
- All lamp collections represented
- "New" and "Popular" product badges
- Load more functionality

### 3. Product Detail Page
**File:** `03-product-v3.html`  
**Screenshot:** `03-product-v3.jpg`

Features:
- Swipeable product gallery (3 images)
- Color variant selector
- Quantity selector
- Accordion specs (Specifications, Shipping, Care)
- Sticky "Add to Cart" button (orange CTA)
- Trust badges (Made in Vietnam, Free Shipping, 30-Day Returns)
- "See it in person" showroom prompt
- Related products carousel

### 4. About Page
**File:** `04-about-v3.html`  
**Screenshot:** `04-about-v3.jpg`

Features:
- Hero with "Designed & Made in Vietnam"
- Brand story and philosophy
- Name meaning explanation (sao + la = star + leaf)
- Craftsmanship feature
- Timeline (2019-2024)
- Values grid (Sustainable, Fair Trade, Quality First, Made for Life)
- Mission statement
- Showroom CTA

---

## Technical Details

**Framework:** Pure HTML5 + CSS3 (no dependencies)  
**Responsive:** Mobile-first (390px base)  
**Typography:** Inter (Google Fonts)  
**Icons:** Inline SVG  

### CSS Architecture
- CSS Custom Properties for brand tokens
- BEM-inspired naming
- Component-based structure
- Smooth transitions (cubic-bezier)

---

## Files

```
wireframes-v3/
├── 00-styles-v3.css      # Design system stylesheet
├── 01-homepage-v3.html   # Homepage
├── 01-homepage-v3.jpg    # Screenshot
├── 02-shop-v3.html       # Shop page
├── 02-shop-v3.jpg        # Screenshot
├── 03-product-v3.html    # Product detail
├── 03-product-v3.jpg     # Screenshot
├── 04-about-v3.html      # About page
├── 04-about-v3.jpg       # Screenshot
├── images/               # Product renders
│   ├── 220217-Lotus.*.jpg
│   ├── Dodeca-TL-Brown.jpg
│   ├── Geode-*.jpg
│   ├── 210831 Wander.*.jpg
│   ├── 220217-Clove.*.jpg
│   └── 220215 Marshmallow_*.jpg
└── SHOWCASE.md           # This file
```

---

## Viewing Instructions

1. Open any `.html` file in a modern browser
2. Best viewed at mobile viewport (390px) or use browser DevTools
3. All links between pages are functional
4. Horizontal scroll on gallery/filters works

---

## GitHub Repository

**Repository:** [github.com/eastwardinho/saola-wireframes](https://github.com/eastwardinho/saola-wireframes)

---

## What's New in V3

| V2 | V3 |
|----|-----|
| Basic typography | Proper tracking hierarchy (tight/loose) |
| Simple gray palette | Warm gradient treatments |
| Static product cards | Hover states, badges, transitions |
| Basic accordion | Refined accordion with animations |
| Simple footer | Rich footer with social icons |
| No promo strip | Free shipping promo strip |
| Basic nav icons | SVG icons with cart badge |
| No variant selector | Color variant selector |
| No related products | Related products carousel |
| No trust badges | Trust badges section |

---

## Quality Highlights

1. **Typography Precision** — Basel Classic guidelines followed exactly
2. **Orange Restraint** — #FFA400 appears only on CTAs (Shop Now, Add to Cart, Explore Collection)
3. **Warm Palette** — Cream (#F3CFB3) and blush (#F5D0C4) gradients throughout
4. **Real Imagery** — All 18 product renders incorporated
5. **Mobile-First** — iPhone 14 Pro viewport (390px)
6. **Interactive Feel** — Sticky buttons, scroll galleries, hover states
7. **Brand Story** — Name etymology, timeline, values grid

---

*Built with care. Designed to impress.*
