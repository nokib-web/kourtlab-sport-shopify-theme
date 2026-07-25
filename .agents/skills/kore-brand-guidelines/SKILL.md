---
name: kore-brand-guidelines
description: >
  Complete brand identity guidelines for KØRĒ (Kourtlab) — a premium performance
  and lifestyle padel apparel brand. Use this skill whenever working on any Shopify
  theme, content, copy, design, or code for the Kourtlab store (c:\pixelora\kourtlab).
  Provides exact colors, typography, logo rules, product lines, tone of voice,
  photography style, and social media standards.
---

# KØRĒ Brand Guidelines
## Complete Identity Reference for Kourtlab Shopify Store

---

## 1. BRAND IDENTITY

### Brand Name
- **Legal / Primary**: KØRĒ (with special Ø and Ē glyphs)
- **Simplified / URL**: KORE
- **Agency/Project Name**: Kourtlab

### Tagline
- **Primary tagline**: "SHOW UP AGAIN TOMORROW."
  - "SHOW UP AGAIN" — in white/off-white
  - "TOMORROW." — in **neon yellow-green** (accent color, #C8FF00)
- **Secondary tagline**: "Built for the Daring"
- **Sub-copy**: "Premium Performance & Padel Brand Apparel"

### Brand Positioning
- Premium performance and lifestyle brand
- Padel-first culture, athletic, urban, editorial
- References: On Running (layout quality), Lululemon (lifestyle crossover)
- NOT: generic sportswear / NOT: minimally branded basics
- IS: dark, editorial, daring, performance-driven, culturally aware

### Brand Symbol (Logo Mark)
- **K-mark**: Bold geometric "K" with diagonal slash cutting through it
  - Used as primary icon mark, favicon, app icon, signage
  - Always black on white OR white on black — never colored
  - The slash represents speed, precision, motion
- **Wordmark**: K Ø R Ē — spaced-out custom letterforms
  - Ø = O with horizontal slash
  - Ē = E with overbar (macron)
  - Wordmark is geometric, slightly condensed, monospaced feel

### Logo Usage Rules
- Logo always in pure Black (#000000) or pure White (#FFFFFF) only
- Never use color tints, gradients, or shadows on the logo
- Minimum clear space = height of the "K" on all sides

---

## 2. COLOR PALETTE

### Primary Colors
| Name | Hex | Usage |
|------|-----|-------|
| Pure Black | #0A0A0A | Primary background, hero, nav |
| True White | #FFFFFF | Primary text on dark |
| Off-White / Cream | #F0EDE6 | Light section backgrounds |
| Dark Charcoal | #111111 | Cards, panels, secondary dark |
| Near Black | #1A1A1A | Elevated surfaces, drawers |

### Accent Colors
| Name | Hex | Usage |
|------|-----|-------|
| Neon Yellow-Green | #C8FF00 | "TOMORROW." tagline, CTAs, key highlights |
| Electric Lime | #AAFF00 | Alternative accent, hover states |
| Deep Navy | #0A1628 | Brand guide section headers |

### Supporting Neutrals
| Name | Hex | Usage |
|------|-----|-------|
| Mid Gray | #888888 | Body copy, secondary text on dark |
| Light Gray | #CCCCCC | Borders, dividers |
| Stone | #D4CFC8 | Subtle backgrounds on light pages |

### Color Rules
- Dark-first: Default is black background, white text
- Neon accent ONLY on key moments: CTA buttons, tagline highlights, badges
- Never use generic blues, reds, or greens for UI

---

## 3. TYPOGRAPHY

### Type Hierarchy
| Role | Font | Weight | Style |
|------|------|--------|-------|
| Display / Hero | Barlow Condensed | 900 (Black) | Uppercase, wide tracking |
| Section Headlines | Barlow Condensed | 700 (Bold) | Uppercase |
| Sub-headlines | Barlow | 600 (SemiBold) | Sentence case |
| Body Text | Inter | 400 (Regular) | Sentence case |
| Labels / Tags | Inter | 600 (SemiBold) | Uppercase, tracked |
| Navigation | Inter | 500 (Medium) | Uppercase |
| Prices / Numbers | Barlow | 500 | Tabular numerals |

### Type Rules
- Hero type: All-caps, Barlow Condensed 900, 80-120px on desktop
- Letter-spacing headlines: 0.05em–0.1em; labels: 0.15em
- Line height display: 0.95–1.0 (tight); Body: 1.6–1.7
- No serif fonts anywhere
- Google Fonts: Barlow Condensed:wght@700;800;900 + Barlow:wght@500;600 + Inter:wght@400;500;600

---

## 4. PRODUCT LINES

### A. First Drop
- Limited edition launch capsule
- Dark backgrounds, editorial, product-forward photography

### B. Launch Collection
- Core seasonal collection
- Clean off-white/cream backgrounds, product layout grids

### C. Padel Collection
- Court-ready technical apparel

### D. Padel Duffle Bag
- Hero product — premium padel bag
- Overhead flat lay, detailed material shots, on-location court

### E. Pad'n Miguel (Collaboration)
- Ambassador collaboration line
- Personality-driven photography, individual portraits

### F. Unboxing Duffle Pack
- Launch activation / unboxing experience
- Video-forward content, packaging reveal

---

## 5. PHOTOGRAPHY & VISUAL STYLE

### Shoot Style
- Dark editorial: Moody, high-contrast, dramatic lighting on black backgrounds
- Clean light: Off-white/cream flat lays for product details
- Action/Lifestyle: Real athletes, real movement, court environments

### Photography Rules
- No stock photos — only brand-shot original content
- Color correction: Desaturated, rich blacks, controlled highlights
- No heavy retouching — authentic skin, real texture
- Preferred aspects: 4:5 (Instagram), 16:9 (hero), 1:1 (product grid)

### Background Usage
- Black background (#0A0A0A): hero sections, campaign shots, signage
- Cream/off-white (#F0EDE6): product detail shots, collection pages
- Court/location: secondary lifestyle imagery

---

## 6. TONE OF VOICE

### Brand Voice
- Confident — not arrogant
- Direct — no fluff
- Aspirational — pushes reader to be better
- Athletic — specific, technical when needed
- Cultural — aware of streetwear, sport, design

### Copy Examples
- GOOD: "Built for the court. Made for the city."
- GOOD: "Show up again tomorrow."
- GOOD: "Don't stop."
- BAD: "Discover your journey with our amazing collection!"
- BAD: "Premium quality at affordable prices."

### UI Copy Rules
- Buttons: Uppercase, max 3 words — "SHOP NOW", "VIEW COLLECTION", "ADD TO BAG"
- Section headings: Sentence case or ALL CAPS only — no Title Case
- Product descriptions: Technical first, lifestyle second

---

## 7. SHOPIFY THEME IMPLEMENTATION RULES

### Color Schemes (config/settings_data.json)
- scheme-1 (Primary Dark): bg=#0A0A0A, text=#FFFFFF, button=#FFFFFF, button_label=#0A0A0A
- scheme-2 (Card Dark): bg=#111111, text=#FFFFFF, button=#FFFFFF, button_label=#111111
- scheme-3 (Accent Neon): bg=#C8FF00, text=#0A0A0A, button=#0A0A0A, button_label=#C8FF00
- scheme-4 (Off-White): bg=#F0EDE6, text=#0A0A0A, button=#0A0A0A, button_label=#F0EDE6
- scheme-5 (Pure White): bg=#FFFFFF, text=#0A0A0A, button=#0A0A0A, button_label=#FFFFFF

### Typography Settings
- type_header_font: barlow_condensed_n7 (Barlow Condensed Bold)
- type_body_font: inter_n4 (Inter Regular)
- heading_scale: 130 (larger than default)

### Button Style
- buttons_radius: 0 — NO rounded corners, always sharp
- buttons_border_thickness: 1
- Uppercase text, letter-spacing 0.1em
- Hover: invert colors

### Cards
- card_corner_radius: 0 — sharp corners
- card_color_scheme: scheme-2 (dark cards)
- Image hover: scale(1.04) zoom, 0.4s ease

### Navigation
- Header: Always dark (bg: #0A0A0A)
- Logo: KØRĒ wordmark centered or left-aligned
- Nav links: uppercase, Inter 500, white

### Announcement Bar
- Background: #C8FF00 (neon yellow-green)
- Text: #0A0A0A (black)
- Content: "FREE SHIPPING OVER $150 · NEW COLLECTION JUST DROPPED · SHOW UP AGAIN TOMORROW"
- Animate as CSS marquee ticker

### Footer
- Full dark: bg=#0A0A0A
- Brand tagline "SHOW UP AGAIN TOMORROW." as statement element
- KØRĒ wordmark centered above footer links

### Page Width
- page_width: 1440 (editorial, wide-canvas)

---

## 8. WHAT TO AVOID

| AVOID | DO INSTEAD |
|-------|-----------|
| Rounded buttons or pill shapes | Sharp 0-radius buttons |
| Serif fonts | Barlow Condensed + Inter only |
| Warm orange, casual reds, vibrant blues | Black, white, cream, neon green |
| Generic stock lifestyle photos | Dark editorial or clean cream product shots |
| All-white website | Dark-first, off-white as secondary only |
| Generic "Add to Cart" styling | Uppercase "ADD TO BAG", sharp, branded |
| Drop shadows on products | Flat product photography |
| Busy grid layouts | Clean, minimal, editorial grid |
