# Strategic Analysis & Brief Deconstruction

*Used in Phase 1 of `SKILL.md`.*

This reference guide establishes the principles and analytical methods for deconstructing a business brief, physical media substrate, and operating context into actionable design constraints before synthesized visual direction occurs.

---

## 1. Business Brief Deconstruction Framework

Every print design brief contains structural variables that govern visual prioritization. Deconstruct the input brief across five core dimensions:

```
                  ┌───────────────────────────────┐
                  │      BUSINESS POSITIONING     │
                  │   Price Point & Market Tier   │
                  └──────────────┬────────────────┘
                                 │
      ┌──────────────────────────┼──────────────────────────┐
      │                          │                          │
┌─────┴───────────────────┐      │      ┌───────────────────┴─────┐
│     MEDIA SUBSTRATE     │      │      │    TARGET PSYCHOLOGY    │
│ Dimensions, Aspect Ratio│      │      │ Decision Speed, Trigger │
│ Material & Lighting     │      │      │ Points, Trust Signals   │
└─────┬───────────────────┘      │      └───────────────────┬─────┘
      │                          │                          │
      └──────────────────────────┼──────────────────────────┘
                                 │
                  ┌──────────────┴────────────────┐
                  │    CONTENT & COPY DENSITY     │
                  │  Hard Data, Hierarchy Levels  │
                  └───────────────────────────────┘
```

### 1. Business Domain & Market Positioning
* **Price Tier & Accessibility:** Identify whether the business operates as budget/mass-market, mid-tier accessible, or premium/artisanal. 
  * *Budget/Mass Market:* Demands immediate price visibility, high visual contrast, bold weights, and unmistakable value hooks.
  * *Mid-Tier/Trendy:* Requires contemporary visual polish, balanced typography, and strong product/service feature highlights.
  * *Premium/Artisanal:* Prioritizes negative space, refined typographic scale, subtle textures, and material authenticity over loud pricing.
* **Core Value Proposition (USP):** Isolate the single visual or message anchor that differentiates the business from competitors (e.g., speed, portion size, heritage recipe, technical precision, eco-friendliness, low price).

### 2. Target Audience Psychology & Viewing Context
* **Engagement Duration & Decision Speed:**
  * *Impulse / High-Speed (1–3 seconds):* Roadside banners, feather flags, car wraps. Requires high contrast, large display scale, single visual focal point, and maximum 3 information hierarchy levels.
  * *Considered / Medium-Speed (5–15 seconds):* Counter posters, window A-frames, pop-up backdrops. Allows structured menu blocks, secondary feature highlights, and sub-branding elements.
  * *Deliberate / Low-Speed (30+ seconds):* Handout flyers, door drop magnets, menu inserts, table tents. Accommodates detailed service matrices, fine typography, terms, and multi-channel contact blocks.
* **Environmental Noise & Viewing Distance:**
  * *Extreme Distance (5m–20m):* Visual elements must use thick boundary linework, high chroma contrast, and display fonts with wide counters.
  * *Arm's Length / Close Reading (30cm–1m):* Tactile paper textures, delicate line details, secondary body copy, and subtle background patterns become effective.

---

## 2. Media Substrate & Physical Mechanics

Print designs exist in physical space. Physical constraints dictate spatial zoning, typographic scale ratios, and margin requirements.

### Aspect Ratio Matrix
* **3:1 to 2.5:1 (Ultra-Wide Banners):** Demands horizontal 3-zone linear composition (Left Hook / Center Focus / Right Action) or strong central anchor flanked by balanced content blocks.
* **1:1 (Square Backdrops/Posters):** Requires radial or centered focal symmetry, strong central branding, and structured perimeter or corner information modules.
* **1:1.414 / 1:2 (Vertical Posters & Roll-Up Banners):** Demands a vertical top-to-bottom stack: Primary Brand Header (Top 25%), Hero Visual/Content Display (Middle 50%), Contact & Action Terminal (Bottom 25%).
* **1:3.5 (Feather Flags / Wind Banners):** Requires vertical text stacking, ultra-bold compressed display fonts, and strong visual weight concentrated in the upper two-thirds to counteract bottom flag motion.

### Physical Scale & Legibility Floor
Aspect ratio describes shape; physical dimensions and viewing distance determine how large content must actually be.
* **Legibility Floor:** For a given viewing distance, every element has a minimum physical size below which it stops being readable; this floor grows in proportion to distance. Derive it from the physical dimensions and the distance at which each element is meant to be read, never from canvas proportion.
* **Scale Relationship:** Compare the floor-sized content footprint to the canvas. On small formats the floor consumes most of the area, so content is constrained. On large formats the floor occupies a small share of the area, so a large surplus exists. Surplus area is not a reason to enlarge lower-priority content.
* **Distance Layering:** Large formats are often read at more than one distance (approach and close). Size each element for the distance at which it is meant to be read.

---

## 3. Content Filtering & Structural Hierarchy

Brief inputs combine non-negotiable requirements with soft preferences. The designer AI must filter and categorize all contents before spatial organization.

### Content Categorization Protocol

1. **Hard Content (Mandatory & Inviolable):**
   * Brand Name / Wordmark
   * Specific Descriptor or Category Tag
   * Required Copy / Taglines
   * Listed Menu Items, Services, or Variants (including exact names and ingredients if provided)
   * Stated Prices or Price Hooks
   * Exact Contact Details (Phone, WhatsApp, Instagram, Physical Address)
   * Explicit Badges or Trust Claims
   * *Rule:* Every piece of hard content provided in the brief MUST appear in the final prompt logic. Never drop, truncate, or alter hard copy unless reformatting for visual density.

2. **Soft Preferences (Directional Guidance):**
   * Suggested colors, mood descriptors, style ideas.
   * *Rule:* Evaluate soft preferences against design principles. Synthesize them if they reinforce brand goals; adjust or refine them if they create visual conflict or compromise print legibility.

3. **Content Density Management:**
   * High copy volume in constrained spaces requires grouping related data into **visual containers** (badges, ribbons, distinct color-blocked modules, rule-lined grids) rather than shrinking text into unreadable sizes.

4. **Attention Tiering (Reading Priority):**
   * After categorizing, rank every content element by *when the reader needs it*, not by what type of element it is:
     * **Tier 1 — Glance:** What must register at full viewing distance within the available reading time: the brand identity and the single message anchor (USP).
     * **Tier 2 — Scan:** Supporting content that builds interest while the reader approaches.
     * **Tier 3 — Deliberate:** Reference details needed only after the reader has decided to act.
   * *Rule:* Tier is decided by an element's role in this brief's decision path, not by its category. Visual weight (scale, contrast, chroma, area) is a budget allocated in descending order by tier; a lower tier never out-weighs a higher one, and raising one element's weight is paid for by others.
   * *Rule:* The reading time from Section 1 limits how many Tier 2 elements can be carried; surplus Tier 2 content is grouped into containers or demoted.

---

## 4. Regional & Local Market Dynamics (UMKM Contexts)

When designing for local micro, small, and medium enterprises (UMKM) and vibrant street-level commercial environments (e.g., Southeast Asian / Indonesian market contexts), specific environmental factors dictate design execution:

### 1. Street-Level Visual Competition
* **Visual Density:** Commercial streets, food centers, and traditional markets (*pasar*) present intense visual clutter (competing signs, overhead wires, varied lighting). 
* **Design Response:** Print pieces require heavy outer framing, high-chroma primary boundaries, thick dark-edged typography, and simplified background shapes to isolate the design from its surrounding physical environment.

### 2. Value Communication & Trust Signals
* **Immediate Price Anchoring:** In price-sensitive markets, prominent badges stating starting prices (e.g., *"Mulai Rp..."*) operate as vital visual hooks rather than secondary details.
* **Trust & Quality Badges:** Local trust markers (e.g., *"100% Halal," "Resep Warisan," "Gratis Antar-Jemput," "Garansi 30 Hari"*) require dedicated badge geometry (bursts, seals, ribbon frames) to signal authenticity instantly.
* **Direct Mobile Action:** WhatsApp handles and Instagram usernames serve as primary conversion channels and must be grouped with recognizable, high-visibility vector icons. They are used after the hook has landed, so they are sized to the legibility floor and kept subordinate in weight unless contact itself is the brief's message anchor.

### 3. Cultural Authenticity vs. Modern Polish
* **Preserving Heritage:** Traditional food, craft, or service businesses (e.g., Bakso, Jamu, Batik) must communicate mastery and authenticity without appearing outdated or unhygienic.
* **Modern Refinement:** Combine heritage visual motifs (woodcut textures, arch shapes, traditional color accents) with clean grid structures, vector linework, and sharp typographic hierarchy to project professional reliability.
