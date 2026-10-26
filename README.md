# ✦ DormGlow — Colorful Pinterest-Inspired Dorm & Hostel Glow-Up Studio

> **Pinterest × Dreamy Dorm Decor × Startup Product Portfolio × Personalized Room Makeover Studio**

DormGlow is a modern, interactive, student lifestyle platform designed to help college and hostel students transform their 10×10 ft. rooms into aesthetic sanctuaries on a student budget.

---

## 🌟 What's New: Premium UI/UX, Immersive Dorm Hero & Sound Effects

1. **Full-Bleed Realistic Dorm Room Hero Background**
   - High-resolution, cozy, warm student dorm photograph featuring fairy lights, polaroid photo wall, layered textiles, and ambient warm lighting.
   - Elegant dark plum-to-warm translucent gradient overlay ensuring high contrast, clean typography, and responsive mobile-to-desktop presentation.
   - Polished hero copy:
     - **Headline**: *Your Dream Dorm Starts Here.*
     - **Supporting Copy**: *Discover your aesthetic, plan your budget, and transform your room into a space that feels like you.*
     - **Primary CTA**: **Explore Room Ideas** (smooth scroll to `#designs`).
     - **Secondary CTA**: **Find My Aesthetic** (smooth scroll to `#aesthetic-quiz`).
     - **Micro-Support**: *Personalized inspiration • Student-friendly budgets • Your style, your space.*
   - **Floating Glassmorphic Studio Card**: Showcasing live counters (24 Room Ideas, 6 Signature Aesthetics, ₹0 Wall Damage), student proof, and 1-click aesthetic jump pills.

2. **Interactive Acoustic Lo-Fi Sound Effects System**
   - Built with lightweight, zero-dependency **Web Audio API** (zero 404s, zero external audio network requests).
   - Synthesizes gentle, cozy, lo-fi UI feedback:
     - **Recommendation cards**: Soft pleasant tap.
     - **Aesthetic cards & Quiz options**: Gentle 2-note confirmation chime.
     - **Buttons & Filter pills**: Subtle UI click.
     - **Saving an idea / adding to My Board**: Shimmering 4-note arpeggio chime.
     - **Budget slider & Color swatches**: Throttled subtle tick (max 1 per 70ms).
     - **Keyboard typing**: Delicate mechanical key click, scoped strictly to text inputs and ignoring modifier/navigation keys.
     - **Modals & Drawer**: Gentle open/close sweep tones.
     - **100% Makeover checklist completion**: Celebratory melodic chime.
   - **Sound On / Sound Off Toggle**: Prominently accessible in the top navigation and mobile drawer with local storage persistence (`dg_sound_enabled`), silent fallback, and zero autoplay annoyance.

3. **Restructured Visual Hierarchy & Logical Flow**
   1. **Hero Section** with immersive dorm room background & glassmorphic studio card.
   2. **Featured Room Inspiration & Aesthetics Showcase** (`#designs` — 24 verified cards, masonry grid, search, tags, sort).
   3. **Find Your Dorm Aesthetic Quiz** (`#aesthetic-quiz` — 5-step visual studio with multi-style blending).
   4. **Visual Room Makeover Budget Studio** (`#calculator` — aesthetic-aware essentials & budget math).
   5. **Interactive Color Studio** (`#color-studio` — palette explorer & live mini-room SVG mockup).
   6. **DIY Idea Generator** (`#diy` — 18 student-tested hacks with step-by-step instructions and safety tips).
   7. **My Room Makeover Journey** (`#room-journey` — hostel photo upload & draggable before-and-after slider).
   8. **My Board Drawer** (`#boardsDrawer` — multi-board management & saved pins).
   9. **Polished Final Call-To-Action Banner** before the footer.

---

## 🌸 6 Signature Aesthetics (Single Source of Truth)

- 🕯️ **Clean Girl Sanctuary** (`Minimalist Luxe`): Crisp white organic cotton, oatmeal linen, clear acrylic organizers, minimalist daylight focus.
- 🎀 **Coquette Dream** (`Soft Romantic`): Soft blush ruffle bedding, sheer chiffon fairy canopy, satin ribbon bows, arched gilded vanity mirror.
- 🌿 **Pinteresty Boho Sanctuary** (`Warm & Earthy`): Handwoven macramé, natural terracotta pottery, trailing pothos, pinewood crates, warm ochre and sage tones.
- 📐 **Scandinavian Minimalist Zen** (`Functional Zen`): Pure uncluttered surfaces, monochrome linen, foldaway wall desks, magnetic under-shelf task lighting, concealed wire tracks.
- ☕ **Dark Academia Vintage Study** (`Moody & Scholarly`): Secondhand classical book stacks, literary book page focal wall, warm amber banker lamp (2200K), forest green tartan throw.
- 🎨 **Pinterest Core Dreamland** (`Curated & Playful`): Curated polaroid & baker twine memory wall, white wire memo grid, wavy squiggly accent mirrors, subtle behind-desk bias lighting.

---

## 🧪 Automated Test Suite

A comprehensive 12-suite automated test verifies aesthetic consistency, data integrity, audio triggers, and responsive layout:

```bash
python tests/test_dormglow_suite.py
```

### Verified Test Suites:
- [x] Zero broken or 404 image URLs.
- [x] Full-bleed dorm hero background, headline, copy, CTAs, and glassmorphic card.
- [x] Restructured section flow and final CTA banner.
- [x] Centralized SoundFX engine, sound toggle button, and input-scoped typing sounds.
- [x] Exactly 4 cards per aesthetic with complete metadata (24 total cards).
- [x] 0% aesthetic contamination across incompatible styles.
- [x] Exactly 3 DIY projects per aesthetic with materials and safety notes (18 total DIYs).
- [x] All 7 budget plans verified with 4 categories and 2 authentic items each.
- [x] Deterministic quiz scoring isolating aesthetics and supporting intentional blends.

---

## 🚀 Running Locally

Serve the application locally with Python:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000) in your browser.

---

## 📄 License

MIT License. Crafted for hostel survivors 🌸
