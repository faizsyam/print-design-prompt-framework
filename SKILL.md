---
name: print-design-prompt-framework
description: Universal framework for converting a business brief into a single, semantically dense image-generation prompt for print design (banners, posters, flyers, backdrops, feather flags, menus, signage, packaging inserts, and similar physical media). Use this skill whenever the user provides a business brief, brand identity, print media size or constraints, or asks for a print design prompt, banner prompt, poster prompt, flyer prompt, or any image-generation prompt for a physical print piece, especially for local UMKM or street-level commercial businesses, even if they do not mention "framework" or "prompt engineering" explicitly.
---

# Print Design Prompt Engineering Framework

A universal, principle-based system for translating business briefs, brand identities, print media constraints, and visual strategies into precise, semantically dense image-generation prompts.

**How to use this skill:** Work through the 5 phases in Section 2 in order. At the start of each phase, read the matching reference file listed in Section 3 before making decisions for that phase. Then output the final prompt using the template in Section 4 and the rules in Section 5.

---

## 1. Philosophical Stance & Operating Limits

This framework operates on **strategic authority without execution micro-management**. It bridges high-level brand strategy and generative AI vision models through four core axioms:

1. **Principle-Driven Strategy:** Design decisions must emerge from structural analysis—media specs, viewing distance, business positioning, target psychology—never from static lookup tables, stock aesthetics, or predefined industry-to-style mappings.
2. **Distinctive Visual Autonomy:** Every output must possess a clear, non-generic design identity with distinct form language, color logic, and typographic personality tailored to the specific business context.
3. **Semantic Density over Micro-Management:** Prompts communicate high-level concept, visual movement, composition, color palette, logo architecture, and spatial hierarchy using precise professional design terminology. Detailed pixel-level rendering and micro-textures are deliberately left to the generative vision model's creative interpretation.
4. **Contextual & Physical Reality:** Print design exists in physical space. Layouts must account for aspect ratio, viewing distance, ambient visual noise, exposure time, and physical media substrate (e.g., outdoor vinyl, kraft paper, window vinyl, fabric flags). Visual weight is distributed by reader attention (what is read at a glance vs. only on closer reading), and element sizes are calibrated to the physical scale of the medium rather than to canvas proportion.

---

## 2. Master Decision Flow

When processing a brief, follow this sequential 5-phase cognitive pipeline:

```
[Phase 1: Strategic Brief Deconstruction]
   │  Analyze medium, viewing distance, copy density, USP, and local market context.
   ▼
[Phase 2: Visual Identity & Movement Synthesis]
   │  Select a specific design movement, form language, color architecture, and logo strategy.
   ▼
[Phase 3: Spatial Architecture & Layout Grid]
   │  Establish aspect ratio zoning, reading hierarchy, focal points, and negative space ratios.
   ▼
[Phase 4: Semantic Prompt Synthesis]
   │  Translate design decisions into a dense, structured, professional prompt text.
   ▼
[Phase 5: Boundary & Quality Verification]
   │  Strip generic buzzwords, verify strict brief content adherence, and confirm generative freedom.
```

### Phase Details & Reference Modules

* **Phase 1: Strategic Brief Deconstruction**
  Deconstruct the business domain, media substrate, aspect ratio, primary viewing distance, reading time (e.g., 2-second roadside vs. 15-second counter read), and mandatory content elements. Rank every content element into an attention tier (glance / scan / deliberate) and derive the legibility floor from physical size and viewing distance.
  *(See detailed execution guidance in `references/01_strategic_analysis_and_deconstruction.md`)*

* **Phase 2: Visual Identity & Movement Synthesis**
  Determine the exact design movement or tradition (e.g., Swiss Style, Risograph Pop, Japanese-Nordic Minimalist, Vintage Linocut, Technical Utilitarian). Define form language, edge behavior, rendering style, 60-30-10 color logic, and independent logo mark architecture.
  *(See detailed execution guidance in `references/02_visual_identity_and_style_synthesis.md`)*

* **Phase 3: Spatial Architecture & Layout Grid**
  Divide physical canvas space into distinct functional zones based on aspect ratio and reading flow. Establish scale contrast ratios (>2:1), typographic hierarchy, visual anchors, and breathing room. Place each element (including the tagline) by attention tier and compositional balance, and size elements from the legibility floor of the physical canvas.
  *(See detailed execution guidance in `references/03_compositional_architecture_and_spatial_systems.md`)*

* **Phase 4: Semantic Prompt Synthesis**
  Construct the raw prompt using structured, highly dense design terminology organized from macro visual concept to specific zonal implementation.
  *(See detailed execution guidance in `references/04_prompt_synthesis_and_output_execution.md`)*

* **Phase 5: Boundary & Quality Verification**
  Audit the prompt against negative constraints: ensure zero fluff/buzzwords, verify all required copy is explicitly represented, confirm no added/invented items exist, verify the prompt directs rather than micro-manages, and confirm attention balance and scale calibration.
  *(The Verification Checklist for this phase is in Section 5 of `references/04_prompt_synthesis_and_output_execution.md`)*

---

## 3. Reference Module Index

When executing specific phases of the workflow, refer to these foundational documents for detailed decision logic:

| File Path | Functional Domain |
| :--- | :--- |
| `references/01_strategic_analysis_and_deconstruction.md` | Brief analysis, media mechanics, physical scale and legibility floor, viewing contexts, content filtering, attention tiering, and local market dynamics (including Indonesian UMKM context). |
| `references/02_visual_identity_and_style_synthesis.md` | Movement identification, shape language, color system architecture, and standalone logo mark strategy. |
| `references/03_compositional_architecture_and_spatial_systems.md` | Grid systems, aspect ratio mapping, typographic hierarchy, spatial zoning, visual eye-tracking flow, attention balance, and scale-aware sizing. |
| `references/04_prompt_synthesis_and_output_execution.md` | Prompt syntax, semantic density rules, exclusion parameters, and boundary control guidelines. |

---

## 4. Universal Output Template

The framework's final deliverable must ALWAYS be a single, self-contained, semantically dense prompt structured according to the following standard template:

```
[Aspect Ratio] [Physical Media Type / Medium] for "[Brand Name]", [Specific Visual Design Movement / Tradition], [Color Palette Architecture: Dominant 60%, Structural 30%, Accent 10%]. [Form Language, Edge Behavior, and Overall Aesthetic Tone].

PRIMARY LOGO MARK & BRANDING:
[Detailed description of central mark/wordmark architecture, typography style, shape containers/frames, and sub-descriptors. Ensure mark remains structurally independent of background elements].

COMPOSITION & LAYOUT ZONING:
[Zonal structural breakdown aligned to aspect ratio and reading flow (e.g., Left/Center/Right or Top/Middle/Bottom). Define precise locations and relative scale for focal hook, product displays, tagline, information blocks, and action badges, assigned by attention tier and balance].

VISUAL ELEMENTS & RENDERING TECHNIQUE:
[Specific description of key visual/product offerings, visual style (vector, illustration, photography, etching, etc.), shading technique, line weight, and exaggeration of key features].

BACKGROUND, BORDERS & FINISH:
[Background texture, framing borders, decorative motifs, pattern work, and edge treatments].

TECHNICAL & EXECUTION CONSTRAINTS:
[Explicit rendering rules: flat layout, high contrast, clean vector/print execution, zero photographic elements (or explicit photographic style), high legibility from [X] distance].
```

---

## 5. Execution Rules & Prompt Directives

1. **Output Raw Prompt Only:** When generating the final response after applying the framework, output *only* the single expanded prompt block unless explicitly requested otherwise.
2. **Never Invent Contents:** Strictly enforce all hard contents (text copy, phone numbers, addresses, menu items, prices) provided in the user brief. Never omit required text or insert extra items.
3. **No Meta-Commentary or Fluff:** Exclude introductory conversational filler, self-congratulatory praise, or vague visual descriptions (*"stunning," "eye-catching," "beautiful"*). Use objective visual terminology (*"high-chroma," "slab-serif," "asymmetrical grid," "stippled shading"*).
4. **Preserve Generative Freedom:** Specify structural visual strategy, spatial relationships, and aesthetic parameters, but allow the target image-generation model to execute fine line rendering, lighting falloff, and organic textures naturally.
