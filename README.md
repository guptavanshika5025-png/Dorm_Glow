# ✦ DormGlow — Colorful Pinterest-Inspired Dorm & Hostel Glow-Up Studio

> **Pinterest × Dreamy Dorm Decor × Colorful Lifestyle Magazine × Personalized Room Makeover Studio**

DormGlow is a colorful, interactive, lifestyle web application designed to help college and hostel students transform their 10×10 ft. rooms into aesthetic sanctuaries on a student budget.

---

## ✨ Design System & Visual Palette

- **Soft Lavender & Lilac**: `#C3B1E1`
- **Pastel Pink & Blush**: `#F9CAD2` / `#FFF0F4`
- **Butter Yellow**: `#FDE68A` / `#FEF9E7`
- **Mint Green & Sage**: `#70D6BC` / `#A8C9B9`
- **Peach & Warm Coral**: `#FDBA9B` / `#FA8C8C`
- **Sky Blue**: `#A0C8F0` / `#EDF5FD`
- **Cream & Warm Ivory**: `#FAF7F2` / `#FFFFFF`
- **Typography**: `Syne`, `Playfair Display`, and `Plus Jakarta Sans`
- **Visual Touches**: Washi tape stickers, Polaroid tilt frames, delicate drop shadows, and scrapbook accents.

---

## 🌸 Aesthetic Consistency, Image Accuracy & Recommendation Relevance

DormGlow is powered by a **Single Source of Truth (`AESTHETIC_DEFINITIONS`)** ensuring every image, color palette, budget item, DIY hack, and recommendation matches the chosen aesthetic with zero contamination:

1. 🕯️ **Clean Girl Sanctuary** (`Minimalist Luxe`)
   - *Colors*: Crisp White, Oatmeal Beige, Muted Sage, Warm Cream
   - *Focus*: Fresh, bright, linen bedding, organized clear acrylic desks, no loose cables, scandi calm.
   - *Excludes*: Cluttered maximalist posters, aggressive RGB gaming, dark heavy ornate decor.

2. 🎀 **Coquette Dream** (`Soft Romantic`)
   - *Colors*: Blush Pink, Petal Cream, Lavender Rose, Soft Butter Gold
   - *Focus*: Sheer chiffon cloud canopy, warm 3000K fairy lights, ribbon bows, vintage arched gilded vanity, delicate floristry.
   - *Excludes*: Cold industrial metal, neon battlestations, dark espresso timber.

3. 🌿 **Pinteresty Boho Sanctuary** (`Warm & Earthy`)
   - *Colors*: Warm Terracotta, Dusty Sage, Ochre Yellow, Oatmeal Cream
   - *Focus*: Rattan, handwoven macramé, terracotta pottery, trailing pothos, warm layered earth tones.
   - *Excludes*: RGB gaming setups, cold chrome, plastic neon furniture.

4. 📐 **Scandinavian Minimalist Zen** (`Functional Zen`)
   - *Colors*: Warm White, Neutral Sand, Slate Grey, Charcoal Accent
   - *Focus*: Pure uncluttered surfaces, monochrome linen, foldaway wall desks, magnetic under-shelf lighting, concealed cord channels.
   - *Excludes*: Decorative knick-knacks, busy prints, frilly ruffles.

5. ☕ **Dark Academia Vintage Study** (`Moody & Scholarly`)
   - *Colors*: Espresso Brown, Warm Amber, Antique Gold, Aged Parchment, Forest Green
   - *Focus*: Stacks of classical secondhand novels, vintage book page focal wall, antique brass banker lamp, tartan plaid lap blanket.
   - *Excludes*: Bright pastel pinks, pop-art stickers, rainbow streamers.

6. 🎨 **Pinterest Core Dreamland** (`Curated & Playful`)
   - *Colors*: Lilac Mist, Blush Glow, Butter Glow, Sky Mist
   - *Focus*: Polaroid twine memory grid, white wire memo panels, squiggly wavy mirrors, pastel bias lighting behind desk.
   - *Excludes*: Drab grey corporate cubicles, aggressive dark gamer caves.

---

## 🎨 6 Core Features

1. **💸 Visual Room Makeover Budget Studio**
   - **Aesthetic-Aware Mode**: Switch between *All Styles*, *Clean Girl*, *Coquette*, *Boho*, *Minimalist*, *Dark Academia*, and *Pinterest Core* to automatically load authentic makeover essentials.
   - Interactive budget slider with live total, spent, and remaining wallet balance.
   - Spending categories (*Bedding & Linens*, *Warm Ambient Lighting*, *Wall Decor & Hangings*, *Modular Storage & Plants*) with price items and live under/over budget alerts.
   - Preset challenges: *My Room Under ₹500*, *Dream Dorm Under ₹1,000*, *Cozy Glow-Up Under ₹2,000*, and *Study Desk Refresh*.
   - 1-click export to Shopping Checklist or board persistence.

2. **✨ Find Your Dorm Aesthetic Quiz & Multi-Style Blending**
   - 5-step visual studio quiz exploring signature vibe, palette, room challenge, budget tier, and priority zone.
   - **Multi-Aesthetic Blending**: Pair your primary style with a secondary aesthetic (e.g. *Boho + Coquette = Romantic Earthy Sanctuary*) with transparent rationale.
   - Deterministic scoring engine that ranks verified makeover cards, matching DIY weekend projects, and starter budget packages with **0% style contamination**.

3. **📌 Pinterest-Like Save Interactions and Boards**
   - Every inspiration card features an elegant hover/touch **Save** button.
   - Save to existing boards (*My Dream Dorm*, *Under ₹1,000*, *Desk Inspo*) or create new custom boards with 1 click.
   - Visual Boards Drawer displaying collage covers, pin counts, and individual board views.
   - Full backward compatibility with `dg_saved` and `dg_boards`.

4. **🎨 Interactive Color Studio (Palette Explorer)**
   - 6 curated aesthetic palettes matched 1:1 with the defined aesthetics.
   - Clickable large color swatches with one-click hex copying.
   - **Live Mini-Room SVG Visualizer**: Real-time room mockup that colors walls, bedding, pillows, and lamps according to the active palette.
   - "Show Matching Makeovers" filters the gallery directly to that palette's aesthetic.

5. **🛏️ My Room Makeover Journey**
   - Upload your current hostel room photo with replace/remove controls and personal notes.
   - Interactive **Before-and-After Draggable Slider** to compare bare rooms against aesthetic glow-ups.
   - Smart Makeover Task Checklist with progress bar and celebration on 100% completion.
   - Transparent, clearly labeled **AI Room Redesign — Coming Soon** preview.

6. **🛍️ Shop the Look / Recreate the Look**
   - Click "Shop the Look" on any of the 24 verified inspiration cards.
   - Authentic decor items with genuine estimated prices in INR.
   - **Affordable Alternatives** for every item to save money on a student budget.
   - 1-click addition of items to your Shopping Checklist or Budget Studio.

---

## 🔨 DIY Idea Generator

- 18 practical, student-tested hostel hacks (3 per aesthetic).
- Aesthetic filter pills to cycle within your room style.
- Detailed step-by-step instructions (1, 2, 3), materials lists, estimated time, difficulty, and **damage-free renter safety notes**.

---

## 🧪 Automated Test Suite

A comprehensive test suite verifies aesthetic consistency, data integrity, and recommendation accuracy:

```bash
python scratch/test_dormglow_suite.py
```

### Verified Checks:
- Zero broken or 404 images (all 24 photos tested and verified HTTP 200).
- Exactly 4 cards per aesthetic with complete metadata.
- 0% aesthetic contamination across incompatible styles.
- Exactly 3 DIY projects per aesthetic with materials and safety notes.
- All 7 budget plans verified with 4 categories and 2 authentic items each.
- Deterministic quiz scoring isolating aesthetics and supporting intentional blends.

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
