# Compositional Architecture & Spatial Systems

*Used in Phase 3 of `SKILL.md`.*

This reference guide establishes the principles for grid-based spatial layout, aspect ratio mapping, typographic hierarchy, visual reading flow, and focal point construction across diverse print media substrates.

---

## 1. Grid Systems & Aspect Ratio Spatial Mapping

A design's physical aspect ratio governs how visual weight, information blocks, and negative space must be distributed. Structure layouts using explicit geometric zoning tailored to physical media dimensions.

```
┌───────────────────────────────────────────────────────────────────────────┐
│                    ASPECT RATIO ZONING ARCHITECTURE                       │
└───────────────────────────────────────────────────────────────────────────┘

1:1.414 / 1:2 VERTICAL           3:1 ULTRA-WIDE LANDSCAPE           1:1 SQUARE / BACKDROP
┌───────────────────────┐   ┌─────────────┬─────────────┬─────────────┐   ┌───────────────────────┐
│  ZONE A: BRAND HEADER │   │   ZONE A    │   ZONE B    │   ZONE C    │   │ TOP PERIMETER: BRAND  │
│  (Primary Lockup, 25%)│   │ VISUAL HOOK │ HERO CONTENT│  ACTION CTA │   │                       │
├───────────────────────┤   │             │   & MENU    │   & INFO    │   │  CENTRAL CORE: HERO   │
│  ZONE B: HERO CONTENT │   │  (Left 30%) │ (Center 40%)│ (Right 30%) │   │  VISUAL / EMBLEM      │
│  (Visuals, Menu, 50%) │   └─────────────┴─────────────┴─────────────┘   │                       │
├───────────────────────┤                                                 │ BOTTOM: DETAILS & CTA │
│  ZONE C: ACTION FOOTER│                                                 └───────────────────────┘
│  (Contact, Badges 25%)│
└───────────────────────┘
```

The zone proportions below are default skeletons. Final zone sizes and contents follow Section 5 (attention balance and scale-aware sizing): a zone holding lower-tier content shrinks rather than filling its default share, and content may be redistributed across zones when balance requires.

### 1. Vertical Media Mechanics (1:1.414, 1:2, 1:3.5)
* **Standard Vertical Stack (Posters, Roll-Up Banners, A-Frames):**
  * **Zone A (Top 20–25%):** Primary Brand Header. Houses main logo lockup, primary descriptor, and top trust badge. Primary entry point for eye-level reading.
  * **Zone B (Middle 50–60%):** Hero Visual & Content Engine. Contains primary illustration/photography, menu offerings, pricing matrices, or key benefit callouts.
  * **Zone C (Bottom 15–20%):** Action Terminal. Dedicated container for WhatsApp handles, social accounts, store location, and high-contrast call-to-action (CTA) badges. Contact details here are Tier 3: contained, compact, and subordinate; high-contrast CTA badges are used only where the Attention Hierarchy ranks the action above Tier 3.
* **Extreme Tall Ratios (Feather Flags 1:3.5, Vertical Wind Banners):**
  * Concentrates visual weight and main brand text within the upper 65% of the canvas to maintain visibility above ground-level obstructions and counteract lower flag movement.

### 2. Horizontal Media Mechanics (3:1, 2.5:1, 2:1)
* **Three-Zone Linear Flow (Street Banners, Service Counters, Storefront Headers):**
  * **Zone A (Left 30–35%):** Visual Hook & Primary Branding. Large, bold brand mark and signature badge or hero visual.
  * **Zone B (Center 35–40%):** Modular Information Core. Cleanly structured menu blocks, service pricing tables, or core product highlights organized in 2 to 4 vertical columns with strong divider rules.
  * **Zone C (Right 25–30%):** Direct Conversion Terminal. Phone/WhatsApp numbers, address notes, and operating hours (Tier 3, sized to the legibility floor), alongside promotional badges (Tier 2) (e.g., *"Gratis Antar"*).

### 3. Square & Backdrop Mechanics (1:1, 4:3)
* **Radial / Focal Center Architecture (Pop-Up Backdrops, Event Booth Walls):**
  * Establishes a dominant central focal node (large hero emblem, collaborative logo lockup, or key event visual) surrounded by balanced corner or perimeter information modules (schedule, social tags, location markers) designed to remain visible when people stand in front of the backdrop.

---

## 2. Typographic Systems & Contrast Hierarchy

Print readability depends on extreme scale contrast and disciplined font pairings. Prevent flat, unreadable copy layouts by enforcing strict scale ratios and structural weight variations.

### 1. The Scale Contrast Ratio Principle (>2:1 Scale Jump)
To create immediate visual order from a distance, primary headlines must maintain a **minimum 2:1 scale ratio** (ideally 2.5:1 to 4:1) over secondary body text. These ratios set the relationship between levels; absolute sizes come from the legibility floor (Section 5):
* **Primary Display Headline / Brand Wordmark:** 100% relative scale baseline.
* **Secondary Headers / Category Labels:** 40%–50% of headline scale (bold, high-contrast, framed in containers or uppercase rules).
* **Body Copy / Detailed Descriptions:** 15%–20% of headline scale (clean, high-legibility sans-serif or refined serif with generous tracking).
* **Prices & Special Highlights:** Scaled independently at 60%–80% of headline scale using high-chroma accent colors or solid badge containers.

### 2. Typographic Personality Pairing Logic
Never pair fonts with identical visual weight or personality traits. Enforce strict functional contrast:
* **Artisanal / Heritage:** High-contrast display Serif or refined Linocut lettering paired with clean, ultra-readable modern Sans-Serif body copy.
* **High-Speed Street / Utilitarian:** Ultra-bold condensed Sans-Serif or Slab-Serif headline paired with geometric Monospace or highly legible Sans-Serif menus.
* **Modern Minimalist / Boutique:** Lightweight elegant Serif or geometric Display paired with widely tracked, clean Sans-Serif subtext.

---

## 3. Visual Eye-Tracking & Focal Anchors

Direct the viewer's eye sequentially through deliberate visual anchors and structural contrast.

```
┌───────────────────────────────────────────────────────────────────────────┐
│                      VISUAL EYE-TRACKING PATHWAYS                         │
└───────────────────────────────────────────────────────────────────────────┘

     Z-PATTERN (Banners / Flyers)             FOCAL HUB & SPOKE (Backdrops)
  ┌───────────────────────────────┐          ┌───────────────────────────────┐
  │  (1) BRAND ───────► (2) BADGE │          │       (2) SECONDARY           │
  │         \                     │          │              ▲                │
  │          \                    │          │              │                │
  │           ▼                   │          │  (3) INFO ◄─(1)─► (4) ACTION  │
  │  (3) HERO ────────► (4) CTA   │          │          BRAND HUB            │
  └───────────────────────────────┘          └───────────────────────────────┘
```

### 1. Directional Reading Pathways
* **Z-Pattern Reading Flow:** Used for wide banners and standard flyers. The eye enters at top-left (Primary Brand), moves right to top-right (Key Badge), cuts diagonally down-left across the center hero visual, and terminates at bottom-right (Contact CTA).
* **Focal Hub & Spoke Flow:** Used for square event backdrops and posters. The eye lands first on the center hero graphic/emblem (Hub), then radiates outward to perimeter information modules (Spokes).

### 2. Structural Information Containers
* **Visual Framing & Color Blocking:** Group complex data (e.g., multi-item menus, multi-tier service prices) into distinct geometric cards, pill containers, framed ribbons, or contrasting background blocks.
* **Divider Rules & Ornamental Accents:** Use subtle brass-line dividers, dashed technical borders, or geometric corner guards to separate distinct information tiers without creating visual clutter.

---

## 4. Negative Space & Breathing Room Allocation

Negative space is a structural design tool that ensures legibility and elevates brand perception.

* **Macro Negative Space (Canvas Boundaries):** Maintain a mandatory **margin buffer zone** (10%–15% of total canvas width/height) around outer edges. Never crowd text or critical logos against canvas borders.
* **Micro Negative Space (Content Padding):** Maintain generous internal padding within menu containers, price badges, and textual blocks to prevent visual compression.
* **Substrate Density Rules:**
  * *High-Density Commercial (Mass-Market Banners):* 20%–30% negative space (tight, packed, high-value visual energy).
  * *Balanced Mid-Tier (Cafes, Local Services):* 40%–50% negative space (structured, accessible, clear).
  * *Artisanal & Luxury (Boutique Studios, Premium Craft):* 60%+ negative space (spacious, quiet, elevated editorial presence).
* **Scale Modifier:** These ranges are set by business positioning and then adjusted by physical scale. When floor-sized content leaves surplus canvas, the surplus becomes negative space and hero/Tier 1 scale rather than larger secondary content.

---

## 5. Attention Balance & Scale-Aware Sizing

Zones and ratios are only a skeleton. Final layout is resolved by the Attention Tiers (`01`, Section 3) and the physical scale of the medium.

### 1. Balance by Attention, Not by Element Type
* **Tier 1** forms the dominant anchor(s). **Tier 2** elements are distributed to support and counterweight the anchor and to carry the eye along the reading pathway (Section 3), rather than being stacked beside it. **Tier 3** is consolidated into one compact, quiet block.
* **Distribute weight:** Visual weight (mass, contrast, chroma) is balanced around the focal anchor across the canvas. Clustering many text elements into one zone creates a text dump and leaves other zones inert. Elements that belong together by meaning (such as the logo mark and its descriptor) stay together; elements that are merely the same kind of content do not have to.
* **Weight ordering:** No element out-scales, out-contrasts, or out-chromas an element of a higher tier. Zone area follows the tier of its content, not its default proportion.

### 2. Scale-Aware Sizing
* **Size from the floor:** Size each element from the legibility floor (`01`, Section 2) of the distance at which its tier is read (Tier 3 is read by an engaged reader at a closer distance), then scale up only as needed to establish hierarchy.
* **Surplus is allocated, not filled:** On large canvases, floor-sized content is a small share of the area. Surplus goes to hero and Tier 1 scale and to negative space and margins, never to enlarging lower-tier elements or adding elements. Tight, crowded layouts on a large canvas indicate sizing from canvas proportion instead of from the floor.
* **Constrained canvases:** On small canvases the floor consumes most of the area. Reduce element count and group related content into containers rather than shrinking below the floor.

