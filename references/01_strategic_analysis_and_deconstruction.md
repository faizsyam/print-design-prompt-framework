# Strategic Analysis & Brief Deconstruction

*Used in Phase 1 of `SKILL.md`.*

This reference guide establishes the principles and analytical methods for deconstructing a business brief, physical media substrate, and operating context into actionable design constraints before synthesized visual direction occurs.

---

## 1. Business Brief Deconstruction Framework

Every print design brief contains structural variables that govern visual prioritization. Deconstruct the input brief across five core dimensions:

```
      ┌───────────────────────────┐        ┌───────────────────────────┐
      │    BUSINESS POSITIONING   │        │  COMMUNICATION OBJECTIVE  │
      │   Market Position & Value │        │ Outcome the Piece Drives  │
      └─────────────┬─────────────┘        └─────────────┬─────────────┘
                    │                                    │
                    └─────────────────┬──────────────────┘
                                      │
        ┌─────────────────────────────┼─────────────────────────────┐
        │                             │                             │
┌───────┴─────────────────┐           │           ┌─────────────────┴───────┐
│     MEDIA SUBSTRATE     │           │           │    TARGET PSYCHOLOGY    │
│ Dimensions, Aspect Ratio│           │           │ Decision Speed, Trigger │
│ Material & Lighting     │           │           │ Points, Trust Signals   │
└───────┬─────────────────┘           │           └─────────────────┬───────┘
        │                             │                             │
        └─────────────────────────────┼─────────────────────────────┘
                                      │
                       ┌──────────────┴────────────────┐
                       │    CONTENT & COPY DENSITY     │
                       │  Hard Data, Hierarchy Levels  │
                       └───────────────────────────────┘
```

### 1. Business Domain, Market Positioning & Objective
* **Positioning:** Positioning is a spectrum across several axes (price accessibility, exclusivity, formality, audience, emotional register), not a fixed set of tiers; most brands sit between or across them. Resolve where the brand sits on each axis from the brief. The more price or value is the audience's decision driver, the more immediate price visibility, high contrast, and bold weight are required. The more perceived quality, craft, or exclusivity is the driver, the more restraint, negative space, refined scale, subtle texture, and material authenticity carry the message. Intermediate positions blend these.
* **Communication Objective:** Identify the single outcome the piece exists to produce in the reader, as implied by the brief. The objective, not the business category, decides which content is primary and whether conversion elements (price hooks, calls to action) belong in the hierarchy at all.
* **Core Value Proposition (USP):** Isolate the single visual or message anchor that differentiates the business from competitors.

### 2. Target Audience Psychology & Viewing Context
* **Reading Time & Decision Speed:** Reading time is continuous. It is set by how the reader encounters the piece: in motion or stationary, by choice or incidentally, and how much else competes for attention. The shorter the exposure, the fewer hierarchy levels and focal points the piece can carry (at the shortest exposures: a single focal point and roughly three levels or fewer, high contrast, large display scale). Longer exposure allows structured blocks, secondary features, sub-branding, fine typography, and detailed information.
* **Environmental Noise & Viewing Distance:** Distance is also continuous and differs per element (see Physical Scale below). The farther an element is read from, the heavier its linework, the higher its contrast, and the more open its letterforms must be. The closer it is read from, the more tactile textures, delicate detail, secondary copy, and subtle pattern become effective.

---

## 2. Media Substrate & Physical Mechanics

Print designs exist in physical space. Physical constraints dictate spatial zoning, typographic scale ratios, and margin requirements.

### Canvas Shape & Visibility
* **Dominant Axis:** The long axis of the canvas sets the primary reading direction and the natural flow of zones. Near-equal axes call for a centered or radial organization instead of a directional flow.
* **Visibility Map:** Determine which regions of the canvas are reliably seen and which are compromised by mounting, folds, trim, motion, eye-level or ground-level obstruction, or surrounding structure. Concentrate high-tier weight in reliable regions and keep critical content out of compromised ones.
* **Commitment to the Axis:** The more extreme the ratio, the more the composition must commit to its axis, with elements, type, and weight following it.
* **Non-Standard Formats:** For any other shape or construction (unconventional ratios, multi-panel, folded, wraparound, non-rectangular, dimensional), treat each independently seen face as its own canvas and design the continuity between faces.

### Physical Scale & Legibility Floor
Aspect ratio describes shape; physical dimensions and viewing distance determine how large content must actually be.
* **Legibility Floor (a lower bound, never a target):** Each element has a minimum physical size below which it stops being readable at the distance from which it is actually read. Derive it from the physical dimensions and that distance, never from canvas proportion. Any size at or above the floor is functionally legible; where within that range an element sits is decided by hierarchy and balance.
* **Distance Belongs to the Tier:** Viewing distance does not apply equally to every element. The farthest distance sets the size demanded by Tier 1 only. Tier 2 is read while approaching. Tier 3 is read by a reader who has chosen to engage, at the distance that reader then adopts.
* **Scale Relationship:** Compare the floor-sized content footprint to the canvas. On large media the floor is far below what the canvas can hold, so lower-tier elements can sit near their floors without losing function, and the headroom belongs to Tier 1 scale and negative space. On small media the floor binds, so every element must remain readable at its floor and content is constrained.
* **Distance Layering:** Large media are often read at more than one distance. Size each element for the distance at which it is meant to be read.

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
   * Any other copy or element the brief supplies or designates as required
   * *Rule:* Every piece of hard content provided in the brief MUST appear in the final prompt logic. Never drop, truncate, or alter hard copy unless reformatting for visual density.

2. **Soft Preferences (Directional Guidance):**
   * Suggested colors, mood descriptors, style ideas.
   * *Rule:* Evaluate soft preferences against design principles. Synthesize them if they reinforce brand goals; adjust or refine them if they create visual conflict or compromise print legibility.

3. **Content Density Management:**
   * High copy volume in constrained spaces requires grouping related data into **visual containers** rather than shrinking text below its legibility floor.

4. **Attention Tiering (Reading Priority):**
   * After categorizing, rank every content element by *when the reader needs it*, not by what type of element it is:
     * **Tier 1 — Glance:** What must register at full viewing distance within the available reading time: the primary identity and the single message anchor that serves the objective.
     * **Tier 2 — Scan:** Supporting content that builds interest while the reader approaches.
     * **Tier 3 — Deliberate:** Reference details needed only after the reader has decided to engage or act.
   * *Rule:* Tier is decided by an element's role in this brief's decision path, not by its category. Visual weight (scale, contrast, chroma, area) is a budget allocated in descending order by tier; a lower tier never out-weighs a higher one, and raising one element's weight is paid for by others.
   * *Rule:* Tier 3 content must be legible, not noticeable. It is never boosted for recognition at a glance.
   * *Rule:* The reading time from Section 1 limits how many Tier 2 elements can be carried; surplus Tier 2 content is grouped into containers or demoted.

---

## 4. Regional & Local Market Dynamics (UMKM Contexts)

When designing for local micro, small, and medium enterprises (UMKM) and vibrant street-level commercial environments (e.g., Southeast Asian / Indonesian market contexts), specific environmental factors shape design execution. Apply each only where it holds for the brief:

### 1. Street-Level Visual Competition
* **Visual Density:** Commercial streets, food centers, and traditional markets (*pasar*) present intense visual clutter (competing signs, overhead wires, varied lighting). 
* **Design Response:** The piece must separate itself from its surroundings through contrast, a simplified background structure, and clear boundaries. The means follow the brand's own identity (Phase 2) rather than a prescribed treatment.

### 2. Value Communication & Trust Signals
* **Price Anchoring:** Where price is a decision driver for the local audience, price hooks operate as primary visual hooks rather than secondary details. Where it is not, they follow their tier.
* **Trust & Quality Signals:** Trust and quality claims supplied by the brief need a distinct container or treatment so they read instantly as claims of authenticity. Their weight follows their tier.
* **Direct Mobile Action:** WhatsApp handles and Instagram usernames serve as primary conversion channels and must be grouped with recognizable icons. They are used after the hook has landed, so they are sized to the legibility floor and kept subordinate in weight unless contact itself is the brief's message anchor.

### 3. Cultural Authenticity vs. Modern Polish
* **Preserving Heritage:** Traditional food, craft, or service businesses must communicate mastery and authenticity without appearing outdated or unhygienic.
* **Modern Refinement:** Combine heritage cues drawn from the brand's own heritage with contemporary structure and a sharp typographic hierarchy to project professional reliability.
