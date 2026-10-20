# Compositional Architecture & Spatial Systems

*Used in Phase 3 of `SKILL.md`.*

This reference guide establishes the principles for grid-based spatial layout, zoning derivation, typographic hierarchy, visual reading flow, and focal point construction across diverse print media substrates.

---

## 1. Grid Systems & Aspect Ratio Spatial Mapping

A design's physical shape governs how visual weight, information blocks, and negative space must be distributed. Structure layouts using explicit geometric zoning derived from the physical media, not from a preset template.

### 1. Zoning Derivation
1. **Read the canvas:** Take the dominant axis and the visibility map from `01` (Canvas Shape & Visibility).
2. **Form zones from content groups:** Zones follow groups of related content and the number of groups the brief actually has, not a fixed zone count.
3. **Size zones by tier:** Each zone's area follows the attention tier and weight of its content (Section 5), not a default share. A zone holding lower-tier content stays compact or merges with another.
4. **Set the path:** Choose a reading pathway (Section 3) that suits the axis and anchor, and arrange zones along it.

### 2. Tendencies Along the Canvas Axis
These are tendencies on a continuum, not categories. Intermediate and unconventional formats interpolate between them or follow `01` for non-standard constructions.
* **Dominant horizontal axis:** Reading flows along the long axis. Distribute tiers along it so weight balances across its length, with the entry anchor at the start of the path.
* **Dominant vertical axis:** Content stacks along the long axis in the order of the reading path, with the entry anchor in the region of best visibility.
* **Near-equal axes:** A central or radial anchor with supporting content placed around it, in positions that stay visible when people or objects stand in front of the piece.
* **Extreme ratios:** Commit to the axis. Concentrate weight where the piece is most reliably visible and let elements and type compress to follow the shape.

---

## 2. Typographic Systems & Contrast Hierarchy

Print readability depends on extreme scale contrast and disciplined font pairings. Prevent flat, unreadable copy layouts by enforcing strict scale ratios and structural weight variations.

### 1. The Scale Contrast Ratio Principle (>2:1 Scale Jump)
To create immediate visual order from a distance, the primary headline must maintain a **minimum 2:1 scale ratio** (ideally wider) over the next level, and every level steps down from the one above with clear contrast. Ratios are minimums that set relationships between levels; they are not size targets:
* **Primary Display Headline / Brand Wordmark:** The top of the scale, sized for the farthest distance at which Tier 1 is read.
* **Secondary Headers / Category Labels:** A clear step below the headline, in the weight and treatment the movement calls for.
* **Body Copy / Detailed Descriptions:** Sized from its legibility floor (Section 5), in clean, high-legibility type with generous tracking. The ratio to the headline widens as the medium grows, because the headline scales with distance while body copy does not.
* **Prices & Special Highlights:** Scaled independently by their tier.

### 2. Typographic Personality Pairing Logic
Never pair fonts with identical visual weight or personality traits. Enforce strict functional contrast:
* **Roles:** The display voice carries identity; the supporting voice carries information.
* **Derivation:** Choose each voice from the brand's character, the selected movement (Phase 2), and the reading distance of the tier it serves.
* **Contrast:** The pair must differ in weight, structure, or personality, and neither may compromise legibility at its tier's floor.

---

## 3. Visual Eye-Tracking & Focal Anchors

Direct the viewer's eye sequentially through deliberate visual anchors and structural contrast. The reading pathway is a consequence of weight gradients and anchor positions: the eye moves from higher weight to lower along directional cues. Design the path deliberately for the canvas. The two patterns below illustrate the principle and are not a closed set.

```
┌───────────────────────────────────────────────────────────────────────────┐
│                      VISUAL EYE-TRACKING PATHWAYS                         │
└───────────────────────────────────────────────────────────────────────────┘

     Z-PATTERN (Diagonal Sweep)               FOCAL HUB & SPOKE (Radial)
  ┌───────────────────────────────┐          ┌───────────────────────────────┐
  │  (1) BRAND ───────► (2) BADGE │          │       (2) SECONDARY           │
  │         \                     │          │              ▲                │
  │          \                    │          │              │                │
  │           ▼                   │          │  (3) INFO ◄─(1)─► (4) ACTION  │
  │  (3) HERO ────────► (4) CTA   │          │          BRAND HUB            │
  └───────────────────────────────┘          └───────────────────────────────┘
```

### 1. Directional Reading Pathways
* **Z-Pattern Reading Flow:** The eye enters at top-left (Primary Brand), moves right to top-right (Key Badge), cuts diagonally down-left across the center hero visual, and terminates at bottom-right (Contact CTA).
* **Focal Hub & Spoke Flow:** The eye lands first on the center hero graphic/emblem (Hub), then radiates outward to perimeter information modules (Spokes).

### 2. Grouping & Separation of Information
* **Group by relationship:** Related information is grouped through relationship cues: proximity, similarity, alignment, continuity, and common region. Enclosure is only one of these, and the heaviest.
* **Lightest sufficient device:** Use the weakest cue that achieves the grouping or separation against the background and competing content. Every added device (enclosure, rule, field) adds weight that the tier budget must pay for, so none is applied by habit.
* **Form follows concept:** Where a boundary is warranted, its form (edge, corner behavior, line quality, shape, or a change of field or texture) is derived from the movement's form language and the brand, never from a default shape. Absence of any boundary is a valid choice.

---

## 4. Negative Space & Breathing Room Allocation

Negative space is a structural design tool that ensures legibility and elevates brand perception.

* **Macro Negative Space (Canvas Boundaries):** Maintain a margin buffer around outer edges, proportional to the canvas and sized to protect against trim, mounting, folds, and edge crowding. Never crowd text or critical logos against canvas borders.
* **Micro Negative Space (Content Padding):** Maintain generous internal padding within groups, badges, and textual blocks to prevent visual compression.
* **Allocation Principle:** Total negative space is a continuous variable, not a category. It rises with quieter positioning, longer reading time, and surplus canvas relative to floor-sized content. It falls with fast-read, value-driven, high-density contexts and with small canvases where the floor binds. Derive it from these factors in combination, not from business type alone.
* **Scale Modifier:** When floor-sized content leaves surplus canvas, the surplus becomes negative space and hero/Tier 1 scale, never larger secondary content.

---

## 5. Attention Balance & Scale-Aware Sizing

Zones and ratios are only a skeleton. Final layout is resolved by the Attention Tiers (`01`, Section 3) and the physical scale of the medium.

### 1. Balance by Attention, Not by Element Type
* **Tier 1** forms the dominant anchor(s). **Tier 2** elements are distributed to support and counterweight the anchor and to carry the eye along the reading pathway (Section 3), rather than being stacked beside it. **Tier 3** is consolidated into one compact, quiet block.
* **Distribute weight:** Visual weight (mass, contrast, chroma) is balanced around the focal anchor across the canvas. Clustering many text elements into one zone creates a text dump and leaves other zones inert. Elements that belong together by meaning (such as the logo mark and its descriptor) stay together; elements that are merely the same kind of content do not have to.
* **Weight dimensions:** Scale is only one carrier of weight. Color relationship, placement on the reading path, proximity to the focal anchor, isolation, and detail density each transfer attention. A lower-tier element must be quieter than higher-tier elements across the dimensions in play; sharing a higher-tier element's color relationship or occupying a prime position competes with it unless other dimensions clearly subordinate it.
* **Ornament:** Ornament has no content tier. It ranks below all content in weight, and its color relationships, scale, and placement stay recessive, supporting the composition without drawing the eye off the reading path.

### 2. Scale-Aware Sizing
* **Size is a band, not a point:** Each element's size is bounded below by its legibility floor (at the distance its tier is actually read) and above by its tier (it never out-weighs a higher tier). Choose within the band by hierarchy and balance. Viewing distance never requires going above the floor for an element whose tier does not call for it.
* **Large media:** The floor is small relative to the canvas, so lower-tier elements sit near their floors and stay compact. Tier 1 takes the scale its distance demands, and the headroom becomes negative space and hero presence. No element is enlarged merely because the canvas is large. Crowded layouts on a large canvas indicate sizing from canvas proportion instead of from the floor.
* **Small media:** The floor binds. Keep every element readable at its floor, reduce element count, and group related content instead of shrinking below the floor.
* **Tier 3 information:** It serves readers who have chosen to engage, so it needs legibility, not recognition. It is never scaled up to compete for attention.
