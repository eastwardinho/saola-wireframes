# Saola Website Wireframes — Summary

*Created: February 16, 2026*

---

## Overview

Seven complete mobile-first wireframes for the Saola website, designed to tell the brand story while driving conversions. Each wireframe includes layout structure, copy suggestions, imagery requirements, and implementation notes.

**View locally:** Open any HTML file in a browser. They're self-contained with linked CSS.

---

## Pages Created

### 1. Homepage (`01-homepage.html`)
**Purpose:** The first impression — tells the whole story in one scroll

**Key Sections:**
- Hero with "Find Your Saola Spirit" tagline
- Story hook (the Saola animal metaphor)
- Featured products (4-6 hero items)
- Cafe teaser (showroom concept)
- Membership CTA (the flywheel)
- Social proof (#SaolaLife UGC)
- Vietnamese craft story (artisan content)
- Newsletter capture

**Critical Copy:**
> "Like the elusive Saola antelope, Vietnamese craftsmanship is a hidden treasure. We're here to share it with the world."

---

### 2. Shop/Collections (`02-shop-collections.html`)
**Purpose:** Shopping experience — filterable, story-driven

**Key Sections:**
- Collection tabs with unique personalities
- Filter chips (product types)
- Product grid with quick-add
- "See in Cafe" persistent banner
- Collection story interstitials

**The Four Collections:**
1. 🎨 **Colorful Creator** — Bold & Playful
2. 🧪 **Experimental Rebel** — Avant-garde
3. 🌍 **Cosmopolitan Expert** — Sustainable & Refined
4. ✨ **Pretty & Posh** — Classic Elegant

---

### 3. Product Detail (`03-product-detail.html`)
**Purpose:** The conversion page — images, story, specs, action

**Key Sections:**
- Swipeable image gallery (5 images ideal)
- Collection tag linking
- Price in USD + VND
- Color/size variants
- Sticky add-to-cart
- "See in Cafe" CTA
- QR code explanation
- Specs accordion
- Vietnamese craft story
- Related products
- Customer reviews

**Critical Features:**
- Member pricing display (when logged in)
- Cafe location where item is displayed
- QR code strategy explanation

---

### 4. Our Story (`04-our-story.html`)
**Purpose:** The emotional heart — Saola animal, Vietnam, craft, team

**Key Chapters:**
1. **The Saola Animal** — "The Asian Unicorn" metaphor
2. **Hidden Treasures** — Vietnamese craft underappreciated
3. **Where We Source** — Binh Duong, Dong Nai, Binh Dinh, Thanh Hoa
4. **Four Collections** — Design personalities
5. **The Team** — Joe, Sammy, future hires
6. **Our Journey** — Timeline from concept to launch

**Critical Copy:**
> "You've never seen Vietnamese design like this. Because no one's shown you. Until now."

**Conservation Angle:**
Consider donating % of sales to Saola animal protection (WWF/IUCN) — adds authenticity.

---

### 5. Cafes (`05-cafes.html`)
**Purpose:** Where the brand comes alive — showroom meets coffee shop

**Key Sections:**
- Concept cards (coffee, touch & try, scan & buy, member perks)
- Featured location card (Thao Dien flagship)
- "Everything for Sale" banner
- Menu preview
- Membership teaser
- Coming soon locations
- Gallery and map

**The Tom Dixon Model:**
Every item has a QR code. Customers experience products naturally while enjoying coffee. Scan to buy, delivered next day.

**Critical Copy:**
> "Walk in for a coffee. Leave with inspiration. (And maybe a new lamp.)"

---

### 6. Membership (`06-membership.html`)
**Purpose:** The loyalty flywheel — mug, discounts, community

**Key Sections:**
- Mug hero showcase
- Perks list (6 benefits)
- Savings calculator (makes value tangible)
- Price card (500,000₫ one-time)
- Eco/sustainability angle
- Testimonials
- FAQ section

**The Offer:**
- 500,000₫ one-time (~$20 USD)
- Premium insulated mug included
- 10% off all F&B, forever
- 10% off all products, forever
- Early access, birthday perks, events

**Critical Copy:**
> "This isn't a subscription. It's an investment in better coffee, better design, and a community that gets it."

---

### 7. About/Contact (`07-about-contact.html`)
**Purpose:** Company info, values, press, careers

**Key Sections:**
- Mission statement
- Values grid (4 pillars)
- Contact cards (email channels)
- Contact form
- Social links
- Press section with downloadable kit
- Sustainability commitment
- Careers CTA
- Legal links

---

## Design System

### Brand Colors
- **Primary Orange:** #FFA400
- **Warm White:** #FEFCF8
- **Cream:** #FFF9F0
- **Charcoal:** #2D2D2D
- **Gray:** #6B6B6B

### Typography
- **Headings:** Inter (web substitute for Basel Classic)
- **Body:** Inter, 14-16px
- **Buttons:** 600 weight, uppercase for labels

### Mobile-First
- Max width: 428px (iPhone 14 Pro Max)
- Bottom tab navigation
- Touch-friendly tap targets (44px min)
- Swipeable galleries

---

## Images Needed (Priority Order)

### High Priority (for launch)
1. **Product hero shots** — 10-15 items, white background, professional
2. **Lifestyle shots** — Products in beautiful Vietnamese homes
3. **Cafe interior** — Showing products for sale with QR codes
4. **Membership mug** — Multiple angles, premium feel
5. **Hero image** — Saola lamp in Vietnamese apartment

### Medium Priority
6. **Saola animal** — The actual antelope, high quality
7. **Artisan photos** — 3-5 craftspeople at work
8. **Material close-ups** — Ceramic, bamboo, wood, terrazzo
9. **Team headshots** — Joe, Sammy, key team

### Nice to Have
10. **Vietnamese landscapes** — Annamite mountains
11. **Workshop/factory** — Behind the scenes
12. **UGC/Instagram** — Real customer content
13. **Video content** — 15-30s product loops

---

## Implementation Notes

### Shopify Structure
```
Collections:
├── All Products
├── Colorful Creator
├── Experimental Rebel
├── Cosmopolitan Expert
└── Pretty & Posh

Products:
├── Images (5 per product)
├── Variants (color, size)
├── Metafields (collection story, cafe location)
└── Tags (type, material)

Membership:
└── Single product (500,000₫)
    └── Customer tag triggers discounts
```

### Key Integrations
- **Payments:** VNPay, MoMo, COD, cards
- **Email:** Klaviyo or similar for automation
- **Reviews:** Judge.me or Loox
- **Membership:** Loyalty Lion or custom tagging
- **Analytics:** Meta Pixel, Google Analytics 4

### Mobile Performance
- Lazy load images
- Optimize for mobile data (Vietnam has variable speeds)
- AMP consideration for key landing pages
- Core Web Vitals compliance

---

## The Story Arc (Every Page)

Every page reinforces the same narrative:

1. **The Saola** — Rare, beautiful, Vietnamese treasure
2. **The Craft** — Quality the world doesn't know exists
3. **The Design** — Belongs in your home
4. **The Experience** — Cafe → trust → buy online
5. **The Community** — Membership, belonging
6. **The Impact** — Sustainable, local, meaningful

---

## Next Steps

1. **Review wireframes** — Joe approves direction
2. **Product photography** — Hero shots for 10-15 launch items
3. **Cafe interior shoot** — When location secured
4. **Mug render/photo** — For membership marketing
5. **Shopify theme selection** — Find base theme that matches
6. **Content writing** — Full copy for each page
7. **Development** — Build on Shopify with custom sections

---

## Files in This Folder

```
wireframes/
├── 00-wireframe-styles.css    — Shared styling
├── 01-homepage.html           — Homepage wireframe
├── 02-shop-collections.html   — Shop & collections
├── 03-product-detail.html     — Product detail page
├── 04-our-story.html          — Our Story page
├── 05-cafes.html              — Cafes page
├── 06-membership.html         — Membership page
├── 07-about-contact.html      — About & Contact
└── WIREFRAMES-SUMMARY.md      — This document
```

---

*Wireframes designed to be premium but warm, Vietnamese soul with international quality. Mobile-first, Shopify-compatible, story-driven.*

— Frank, February 2026
