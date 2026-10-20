# Prompt Synthesis & Output Execution

*Used in Phases 4 and 5 of `SKILL.md`.*

This reference guide establishes the principles, semantic translation mechanics, negative constraints, and output execution directives for converting synthesized strategic design decisions into a single, highly dense, professional image-generation prompt.

---

## 1. Semantic Density & Technical Terminology Translation

Image-generation vision models respond to precise structural, artistic, and spatial terminology rather than conversational explanations or subjective buzzwords. Translate strategic design decisions into exact domain terms:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SEMANTIC TRANSLATION PIPELINE                        │
└─────────────────────────────────────────────────────────────────────────┘

INFORMAL / VAGUE INTENT                 PRECISION DOMAIN TERMINOLOGY
┌──────────────────────────┐           ┌──────────────────────────────────┐
│ "Looks vintage and old"  │ ────────► │ "19th-century linocut woodcut    │
│                          │           │  etching, cross-hatched shading, │
│                          │           │  vintage aged paper substrate"   │
└──────────────────────────┘           └──────────────────────────────────┘
┌──────────────────────────┐           ┌──────────────────────────────────┐
│ "Very bright and stands  │ ────────► │ "High-chroma dual-tone palette,  │
│  out on the street"      │           │  flat vector planes, thick dark  │
│                          │           │  bounding strokes, high contrast"│
└──────────────────────────┘           └──────────────────────────────────┘
┌──────────────────────────┐           ┌──────────────────────────────────┐
│ "Clean and modern cafe   │ ────────► │ "Japandi warm editorial style,   │
│  vibe"                   │           │  asymmetrical grid, generous     │
│                          │           │  negative space, light serif"    │
└──────────────────────────┘           └──────────────────────────────────┘
```

### 1. Architectural & Spatial Vocabulary
* **Layout Mechanics:** `asymmetrical grid`, `three-column linear layout`, `central radial composition`, `top-weighted vertical hierarchy`, `horizontal zonal partitioning`, `geometric modular containers`, `framed pill badges`.
* **Typographic Descriptors:** `high-contrast display serif`, `ultra-bold condensed sans-serif`, `hand-lettered brush script`, `tracked uppercase subheadline`, `drop-shadowed block typography`, `woodcut slab-serif`.
* **Color Distribution:** `60-30-10 structural color ratio`, `terracotta primary base (60%)`, `navy structural containers (30%)`, `amber accent callout badges (10%)`, `monochromatic tone-on-tone background`.

### 2. Style & Technique Vocabulary
* **Artistic Traditions:** `Swiss International Style`, `Risograph multi-pass print`, `Constructivist poster art`, `Japanese woodblock print (Ukiyo-e)`, `Mid-century flat vector illustration`, `Retro-pop commercial graphics`.
* **Rendering Mechanics:** `cel-shaded vector rendering`, `copperplate line etching`, `stippled halftone grain`, `flat 2D graphic planes`, `isometric dimensional projection`, `textured matte linework`.

---

## 2. Elimination of Generic AI Aesthetics & Fluff

To prevent the vision model from reverting to generic "AI stock design" tropes, strictly purge conversational filler, vague buzzwords, and redundant descriptors.

### 1. Prohibited Buzzwords & Vague Terminology
Never use subjective or non-actionable adjectives that offer zero visual structure:
* ❌ *Prohibited:* "stunning," "eye-catching," "beautiful," "award-winning," "trending on ArtStation," "hyper-realistic," "photorealistic," "amazing," "high quality," "unbelievable detail."
* ✔ *Replacement:* Direct, descriptive mechanics (e.g., `"crisp vector edges, high contrast line weight, rich matte paper texture, balanced 3-zone composition"`).

### 2. Purging "Default AI Stock" Visual Elements
Vision models often default to generic digital visual tropes if unguided. Explicitly construct prompts to override these defaults:
* **Avoid generic glowing effects:** Replace digital glows/neon flares with crisp high-chroma contrast or sharp vector outlines unless specifically designing a neon sign.
* **Avoid floating/random 3D objects:** Ensure all visual elements are anchored within explicit grid structures, containers, ribbons, or organic flat-lay surface arrangements.
* **Avoid hyper-busy background clutter:** Mandate solid, textured, or subtly patterned backgrounds that preserve readability for overlaid text and menu modules.

---

## 3. Boundary Control & Generative Freedom Balance

The prompt framework must exercise **strategic boundary control**: it strictly governs visual structure, hierarchy, composition, brand architecture, and color logic, while leaving fine line execution, micro-rendering, and organic textures to the model's creative strength.

```
┌───────────────────────────────────────────────────────────────────────────┐
│                    THE BOUNDARY CONTROL BALANCE                           │
└───────────────────────────────────────────────────────────────────────────┘

MUST BE EXPLICITLY DIRECTED                 LEFT TO GENERATIVE EXECUTION
┌──────────────────────────────────────┐   ┌────────────────────────────────┐
│ • Aspect ratio & media format        │   │ • Exact micro-texture grain    │
│ • Aspect ratio zoning & grid flow    │   │ • Fine lighting falloff & shade│
│ • Exact hard content & copy strings  │   │ • Subtle organic linework      │
│ • Logo architecture & position       │   │   variations                   │
│ • Color hierarchy (60-30-10)         │   │ • Artistic stroke rendering    │
│ • Visual style & design movement     │   │   nuances                      │
└──────────────────────────────────────┘   └────────────────────────────────┘
```

---

## 4. Final Output Construction Pipeline

When generating the final prompt output, assemble the deconstructed design decisions according to the strict universal template:

### Execution Protocol Steps

1. **Header Block Assembly:** State aspect ratio, physical media type, full brand name, selected design movement, and explicit 60-30-10 color allocation.
2. **Primary Logo Mark & Branding:** Detail the emblem/wordmark geometry, typography style, descriptor, and structural isolation mechanics.
3. **Composition & Layout Zoning:** Map the physical canvas into distinct spatial zones (Top/Middle/Bottom or Left/Center/Right) aligned to the media aspect ratio and target reading distance. Place every element, including the tagline, by attention tier and balance, with relative sizes calibrated to the physical scale.
4. **Visual Elements & Rendering Technique:** Detail product displays, hero visuals, graphic rendering style (vector, etching, risograph, cel-shaded), and line-weight parameters.
5. **Background, Borders & Finish:** Define substrate textures, framing borders, decorative corner guards, or background pattern density.
6. **Technical & Execution Constraints:** Enforce flat print layout execution, zero unwanted photographic noise, high legibility distances, and strict hard-content fidelity.

---

## 5. Verification Checklist

Before emitting the final expanded prompt, execute a final cognitive audit:

* [ ] **Hard Copy Fidelity:** Is every brand name, menu item, price, phone number, address, and trust badge from the brief explicitly included in the prompt text without alterations?
* [ ] **Zero Added Hallucinations:** Did you avoid inserting extra menu items, fake prices, or unrequested social handles?
* [ ] **No Lookup Table Tropes:** Is the style choice derived from structural business analysis rather than a generic industry lookup list?
* [ ] **Semantic Density:** Are all visual instructions expressed in professional design, art history, and print production terminology?
* [ ] **Attention Balance:** Does visual weight follow the attention tiers (no lower-tier element out-weighs a higher one), with weight distributed across the canvas rather than clustered, and with the tagline and contact information placed by role rather than by habit?
* [ ] **Scale Calibration:** Are element sizes derived from the legibility floor of the physical size and viewing distance, with surplus canvas given to hero scale and negative space rather than to enlarged secondary content?
* [ ] **Template Integrity:** Does the output strictly adhere to the universal template structure defined in `SKILL.md`?
