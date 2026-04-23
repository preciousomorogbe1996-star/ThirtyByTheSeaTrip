# #ThirtyByTheSea Design System

## Overview

**#ThirtyByTheSea** (also **#PreshsChillFlirty30**) is the brand identity for a 30th birthday trip to Albania — a coastal road trip from 19–26 May 2026. The brand was originally created in Canva and is being refined here into a full design system for trip collateral: stickers, t-shirts, itinerary cards, social graphics, and more.

**Two hashtags define the brand:**
- `#ThirtyByTheSea` — the main trip brand/event name
- `#PreshsChillFlirty30` — the personal birthday celebration hashtag

**Trip details:**
- London Heathrow → Tirana, Albania (British Airways)
- 3 hotels: Elite Bay Hotel (Lalez Durres), Arameras Resort (Ksmail), Arka Art Hotel (Tirana)
- Coastal road trip along the Albanian Riviera

**Source files:** `uploads/birthday_trip.pdf` (Canva-created trip guide, 8 pages)

---

## CONTENT FUNDAMENTALS

### Voice & Tone
- **Fun, hype, celebratory** — this is a birthday party on the road
- **All-caps throughout** — every headline, label, and body text is ALL CAPS; this is a core brand rule
- **First-person "I"** — the organiser speaks directly ("I WILL BE COVERING THIS HOTEL", "I WILL BOOK IT WITH MY FLIGHT")
- **Exclamation energy** — exclamations and rhetorical questions ("WHAT'S A ROAD TRIP WITHOUT THE CAR?!!!") add personality
- **Hashtag-first** — brand hashtags are used as headers and watermarks, not just social tags
- **No emoji** — the design uses white outline icons (airplane, car, house/pin, palm tree) rather than emoji
- **Casual British spelling/phrasing** — "PP" (per person), "£", colloquial tone

### Copy Examples
- `#THIRTYBYTHESEA — #PRESHSCHILLFLIRTY30 TO ALBANIA. ROAD TRIP ALONG THE COAST!`
- `THE IMPORTANT STUFF`
- `WHAT'S A ROAD TRIP WITHOUT THE CAR?!!!`
- `TOTAL FOR THE TRIP — £750.15`
- `COMING SOON.....`

### Casing
- Everything is **ALL CAPS** — no sentence case
- Hashtags retain the `#` prefix and CamelCase in social contexts (`#ThirtyByTheSea`) but appear fully uppercase in design (`#THIRTYBYTHESEA`)

---

## VISUAL FOUNDATIONS

### Color Palette
| Token | Hex | Description |
|---|---|---|
| `--sand` | `#C4A87A` | Primary background — warm sandy camel |
| `--sand-dark` | `#B08F60` | Darker variant for depth, dividers |
| `--sand-light` | `#D9C4A0` | Lighter highlight |
| `--white` | `#FFFFFF` | Primary text and icon color |
| `--watermark` | `rgba(180,150,100,0.35)` | Watermark text/logo color |
| `--dark` | `#1A1008` | Near-black for borders/dividers |

### Typography
- **Display (hero):** Wide, heavy, bold condensed all-caps — *Bebas Neue* (Google Fonts). Used for `#THIRTYBYTHESEA`, major headings. Very large scale.
- **Subheading:** Condensed, spaced, bold — *Josefin Sans* Bold or *Montserrat* ExtraBold. Used for hashtag taglines.
- **Body/Details:** Bold, condensed, all-caps — *Montserrat* Bold Condensed or *Barlow Condensed* Bold. Used for dates, details, descriptions.
- **Accent (ransom-note):** Cut-out letter collage style — mixed fonts, colors, and sizes for words like "trip". This is decorative/collage only.

**Note:** Glacial Indifference Bold is confirmed as the brand font (uploaded to `fonts/GlacialIndifference-Bold.otf`). It is used for all subheadings, body, and detail text. Bebas Neue (Google Fonts) is used for display/hero text — if you have a specific Canva display font, please share it for an exact match.

### Backgrounds
- **Solid camel/sand** (`#C4A87A`) is the primary page background — no gradients
- A **palm tree watermark** (ghosted, same-hue, ~35% opacity) floats behind content
- **Hashtag watermark** (`#THIRTYBYTHESEA` in large light type) appears bottom-left as a background element
- Full-bleed **photography** is used for section dividers — turquoise Albanian coastal water, resorts, palm trees

### Photography Style
- **Warm, saturated Mediterranean** tones — turquoise water, golden hour light
- **Polaroid framing** — photos displayed in a polaroid/instant-photo style with a white tape strip at the top
- **Collage/scrapbook overlaps** — photos overlap each other at angles (slight rotation)
- **Torn-edge effects** — some photo cutouts have rough torn paper edges

### Icons
- **White outline / line style** — not filled, minimal detail
- Subject matter: airplane ticket, vintage car, house/location pin, palm tree
- Icons are **large and decorative**, not small inline glyphs
- No icon font used; icons appear to be Canva's built-in library

### Layout
- **Single column**, centered content
- Sections divided by **full-bleed photography panels**
- **Wide margins** with centered text
- Hashtag logo always present as a **header identifier** on each page (small, upper-left or lower-right)
- No grid or card system — editorial/magazine layout

### Spacing & Shape
- **No rounded corners** on photos or panels — square/rectangular
- **No card shadows** — flat design
- **Polaroid tape strips** at top of photos (white rectangle)
- Thick **dark divider lines** between major sections

### Animation / Interaction
- Static print/social media design — no defined animation system
- For digital use: recommend **fade-in on scroll**, gentle **parallax** on background

### Collage Elements
- **Scrapbook aesthetic** — overlapping photos, stickers, mixed typography
- **Cut-out letter collage** for decorative words (ransom-note style, multi-colored)
- Travel memorabilia imagery (vintage maps, stamps, globes, cameras)

---

## ICONOGRAPHY

- **Style:** White outline icons, minimal, decorative-scale
- **Source:** Canva built-in icon library (not a specific named system)
- **Subjects used:** Palm tree, airplane/ticket, car (vintage outline), house/location pin
- **Usage:** Icons are large (100–200px equivalent) decorative elements placed alongside text sections, not inline glyphs
- **No icon font** — icons are embedded images from Canva export
- **Emoji:** Not used in design
- **Substitution:** For this design system, we reference similar-style SVG icons where possible

---

## FILES

| File | Description |
|---|---|
| `README.md` | This file — brand overview and guidelines |
| `colors_and_type.css` | CSS variables for colors, typography, spacing |
| `SKILL.md` | Agent skill definition |
| `assets/` | Visual assets (logos, icons, imagery) |
| `preview/` | Design system preview cards |
| `ui_kits/collateral/` | UI kit for stickers, t-shirts, social graphics |
| `uploads/birthday_trip.pdf` | Source Canva design (8 pages) |
