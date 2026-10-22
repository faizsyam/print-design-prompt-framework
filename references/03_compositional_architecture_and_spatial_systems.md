# Compositional Architecture & Spatial Systems

*Used in Phase 3 of `SKILL.md`. Every decision here follows the Decision Protocol in `SKILL.md`, Section 2.*

This reference guide establishes the principles for grid-based spatial layout, zoning derivation, typographic hierarchy, visual reading flow, and focal point construction across diverse print media substrates.

---

## 1. Zoning & Canvas Spatial Mapping

A design's physical shape governs how visual weight, information blocks, and negative space must be distributed. Structure layouts using explicit geometric zoning derived from the physical media, not from a preset template.

### 1. Zoning Derivation
1. **Read the canvas:** Take the dominant axis and the visibility map from `01` (Canvas Shape & Visibility).
2. **Form zones from content groups:** Zones follow groups of related content and the number of groups the brief actually has, not a fixed zone count; their position and form follow the placement logic (Section 5).
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
* **Primary Display Headline:** The top of the type scale. When a text element is the primary focus, it is sized for the farthest distance at which Tier 1 is read; otherwise the top text level is sized by its own tier.
* **Secondary Headers / Category Labels:** A clear step below the headline, in the weight and treatment the movement calls for.
* **Body Copy / Detailed Descriptions:** Sized from its legibility floor (Section 5), with type chosen for legibility at that size. The ratio to the headline widens as the medium grows, because the headline scales with distance while body copy does not.
* **Prices & Special Highlights:** Scaled independently by their tier.

### 2. Typographic Personality Pairing Logic
Never pair fonts with identical visual weight or personality traits. Enforce strict functional contrast:
* **Roles:** The display voice carries identity; the supporting voice carries information.
* **Derivation:** Choose each voice from the brand's theme and personality, the selected movement (Phase 2), and the reading distance of the tier it serves. Each voice is resolved to specific structural and stylistic traits (`02`, Section 2.2), not to a category.
* **Contrast:** The pair must differ in weight, structure, or personality, and neither may compromise legibility at its tier's floor.

---

## 3. Visual Eye-Tracking, Focal Anchors & Grouping

Direct the viewer's eye sequentially through deliberate visual anchors and structural contrast. The reading pathway is a consequence of weight gradients and anchor positions: the eye moves from higher weight to lower along directional cues. Design the path deliberately for the canvas. The two patterns below illustrate the principle and are not a closed set.

```
┌───────────────────────────────────────────────────────────────────────────┐
│                      VISUAL EYE-TRACKING PATHWAYS                         │
└───────────────────────────────────────────────────────────────────────────┘

     Z-PATTERN (Diagonal Sweep)               FOCAL HUB & SPOKE (Radial)
  ┌───────────────────────────────┐          ┌───────────────────────────────┐
  │  (1) ENTRY ───────► (2) NEXT  │          │       (2) SECONDARY           │
  │         \                     │          │              ▲                │
  │          \                    │          │              │                │
  │           ▼                   │          │  (3) SPOKE ◄─(1)─► (4) SPOKE  │
  │  (3) MID  ────────► (4) END   │          │          FOCAL HUB            │
  └───────────────────────────────┘          └───────────────────────────────┘
```

### 1. Directional Reading Pathways
* **Z-Pattern Reading Flow:** The eye enters at top-left (the entry anchor), moves right to top-right (the second anchor), cuts diagonally down-left across the center, and terminates at bottom-right (the final element of the path).
* **Focal Hub & Spoke Flow:** The eye lands first on the central anchor (Hub), then radiates outward to perimeter information modules (Spokes).

### 2. Grouping & Separation of Information
* **Group by relationship:** Related information is grouped through relationship cues: proximity, similarity, alignment, continuity, and common region. Enclosure is only one of these, and the heaviest.
* **Lightest sufficient device:** Use the weakest cue that achieves the grouping or separation against the background and competing content. Every added device (enclosure, rule, field) adds weight that the tier budget must pay for, so none is applied by habit.
* **Form follows concept:** Where a boundary is warranted, its form (edge, corner behavior, line quality, shape, or a change of field or texture) is derived from the movement's form language and the brand's theme, never from a default shape. Absence of any boundary is a valid choice.
* **Single items:** A device around one item is ornament, not grouping, and must pass the ornament test (`02`, Section 2.5). Text sits directly on its ground by default.
* **Device economy:** The piece uses one device language, and the number of distinct device types is kept to what the hierarchy requires.

---

## 4. Negative Space & Breathing Room Allocation

Negative space is a structural design tool that ensures legibility and elevates brand perception.

* **Macro Negative Space (Canvas Boundaries):** Maintain a margin buffer around outer edges, proportional to the canvas and sized to protect against trim, mounting, folds, and edge crowding. Never crowd text or critical logos against canvas borders.
* **Micro Negative Space (Content Padding):** Maintain generous internal padding within groups, badges, and textual blocks to prevent visual compression.
* **Allocation Principle:** Total negative space is a continuous variable, not a category. It rises with quieter positioning, longer reading time, and surplus canvas relative to floor-sized content. It falls with fast-read, value-driven, high-density contexts and with small canvases where the floor binds. Derive it from these factors in combination, not from business type alone.

---

## 5. Attention Balance & Scale-Aware Sizing

Zones and ratios are only a skeleton. Final layout is resolved by the Attention Tiers (`01`, Section 3) and the physical scale of the medium.

### 1. Balance by Attention, Not by Element Type
* **Tier 1** forms the dominant anchor(s). **Tier 2** elements are distributed to support and counterweight the anchor and to carry the eye along the reading pathway (Section 3), rather than being stacked beside it. **Tier 3** stays compact and quiet; whether it forms one group or several, and where it sits, follows the placement logic below.
* **Distribute weight:** Visual weight is balanced around the focal anchor across the canvas. Clustering many text elements into one zone creates a text dump and leaves other zones inert. Elements that belong together by meaning (such as the logo mark and its descriptor) stay together; elements that are merely the same kind of content do not have to.
* **Weight dimensions:** Hierarchy is judged across every weight dimension defined in `01` (Section 3, item 4), not scale alone. A lower-tier element must be quieter than higher-tier elements across the dimensions in play; sharing a higher-tier element's color relationship or occupying a prime position competes with it unless other dimensions clearly subordinate it.
* **Area is the last dimension spent:** Area is zero-sum with content and breathing room, so build the hierarchy first with contrast, isolation, placement, and color, and add area only where those cannot achieve the tier. An element can hold a high tier at modest area, and no element is owed area by its category or role.
* **Weight audit:** Once attributes are set, assess the weight each element actually produces (area, value contrast against its ground, chroma, detail density, isolation, position) and compare the resulting order with the tier order. Large-area elements (grounds, bands, borders, fields) carry weight through area alone, so they stay tonally close to their ground or small enough to remain below the content they frame. Any element that outweighs its tier is reduced or removed. A hierarchy declared in words does not substitute for one the attributes produce.
* **Ornament:** It ranks below all content (`01`), and its color relationships, scale, and placement stay recessive, supporting the composition without drawing the eye off the reading path.

### 2. Scale-Aware Sizing
* **Size is a band, not a point:** Each element's size is bounded below by its legibility floor (at the distance its tier is actually read) and above by its tier (it never out-weighs a higher tier). Choose within the band by hierarchy and balance. Viewing distance never requires going above the floor for an element whose tier does not call for it.
* **Large media:** The floor is small relative to the canvas, so lower-tier elements sit near their floors and stay compact. Tier 1 takes the scale its distance demands, and the headroom becomes negative space and Tier 1 presence. No element is enlarged merely because the canvas is large. Crowded layouts on a large canvas indicate sizing from canvas proportion instead of from the floor.
* **Small media:** The floor binds. Keep every element readable at its floor, reduce element count, and group related content instead of shrinking below the floor.

### 3. Placement Logic for All Information
Every element's position, extent, and grouping, at every tier, is a decision derived from the brief and never a default pattern:
* **Function:** Where the reader needs it in their journey (entry, along the path, or after engaging) and where the viewer is physically positioned when they need it.
* **Relationship:** Nearness to what it explains, qualifies, or completes. Related items share a region and unrelated items do not, regardless of content type.
* **Counterweight:** Its contribution to the canvas balance around the focal anchor (Section 5.1).
* **Form of the group:** The shape and extent of an information group (compact or spread, one group or several, how much of an edge or axis it spans, standing free or integrated with another element) is chosen for the composition. Spanning an entire edge or axis requires justification.
* **Overlap:** Elements never overlap or intrude on text. Overlap among non-text elements is a deliberate integration, not a by-product.

### 4. Pictorial Subject: Role, Scale & Placement
For a pictorial subject admitted in Phase 1 and designed in Phase 2 (`02`, Section 2.4):
* **Role:** It is the primary focal anchor, a supporting element, or ornament, as ranked by its tier. There is one primary anchor; a pictorial subject holds that role only when it is the Tier 1 element that serves the objective.
* **Scale:** Set by sufficiency within the band (Section 5.2): the smallest scale and weight at which the subject still does its job, within the area left after required content at its floor and breathing room. A primary anchor takes the scale its distance demands only where registering at that distance requires area, with contrast, isolation, and placement tried first; a supporting subject stays below the anchor, and ornament stays recessive. As the information load rises the subject recedes in scale, then in visibility, down to ambient or absent, and surplus canvas goes to the anchor's scale and negative space, never to the subject by default.
* **Placement:** Follows the Placement Logic above: function, relationship to what it depicts or relates to, and counterweight. Its extent and its relation to canvas edges and to other elements are chosen, not defaulted.
* **Hierarchy:** The weight dimensions in Section 5.1 apply to it like any element; as a supporting or ornamental subject it takes a recessive color relationship and position relative to the anchor.

### 5. Purpose, Presence & Visibility
Tier says when an element is read; purpose says what it does for the reader. Both set how it is treated.
* **Purpose:** Judge what the element is for: to be understood, to attract or persuade, to organize, or only to shape atmosphere. Elements to be understood are treated for clarity first and voice second; elements that attract or persuade carry the theme at their tier's full strength; atmospheric elements support the mood at reduced weight and compete with neither.
* **Presence is a continuum:** Whether an element exists, and how visible it is if it does, ranges from absent through barely perceptible and supporting to prominent. Purpose and tier set the degree together, at the lowest visibility at which the element still does its job.
* **Serving the foundation:** Every attribute of an element (size within its band, position, color relationship, type voice, rendering, finish, complexity) is derived from the foundational decisions it must express or stay subordinate to, then from its tier and purpose. An attribute that cannot be traced this way is a default.
* **Sibling consistency:** Elements of the same tier and purpose share a treatment unless their relationship demands otherwise; elements that differ in purpose differ in treatment by exactly that difference.

### 6. No Category Defaults
Treatments, positions, and dominance are never attached to element categories or repeated across briefs by habit. Each element receives its own size, position, grouping, color, and finish, derived through the Decision Protocol from its tier, its purpose, and the foundational decisions. No canvas edge or end of the reading path is reserved for a content category, and no category, including the logo mark, is dominant by default: dominance goes to what the tiering names as primary focus. The same category can legitimately look different across briefs, and different categories can share a treatment when their roles match.

