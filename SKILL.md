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
2. **Distinctive Visual Autonomy:** Every output must possess a clear, non-generic design identity with distinct form language, color logic, and typographic personality tailored to the specific business context. Each visual layer is its own deliberate, brief-specific choice, and functional legibility never dictates stylistic intensity.
3. **Semantic Density over Micro-Management:** Prompts communicate high-level concept, visual movement, composition, color palette, logo architecture, and spatial hierarchy using precise professional design terminology. Detailed pixel-level rendering and micro-textures are deliberately left to the generative vision model's creative interpretation.
4. **Contextual & Physical Reality:** Print design exists in physical space. Layouts must account for aspect ratio, viewing distance, ambient visual noise, exposure time, and physical media substrate. Visual weight, carried by scale, color, placement, and isolation together, is distributed by reader attention (what is read at a glance vs. only on closer reading), and element sizes are calibrated to the physical scale of the medium rather than to canvas proportion or a single viewing distance.

**Open-set rule:** Every list, category, ratio, or reference value in this skill describes a principle or a tendency along a continuum, never a closed set. Derive decisions from the principle. When a brief falls outside or between listed cases, extend the principle instead of forcing a fit.

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
  Deconstruct the business domain, communication objective, media substrate, aspect ratio, primary viewing distance, reading time, and mandatory content elements. Rank every content element into an attention tier (glance / scan / deliberate) and derive the legibility floor from physical size and the distance at which each tier is read.
  *(See detailed execution guidance in `references/01_strategic_analysis_and_deconstruction.md`)*

* **Phase 2: Visual Identity & Movement Synthesis**
  Determine the exact design movement or tradition, drawn from the full range of design history and practice, including hybrids. Define form language, edge behavior, the representation mode and expressive character of each visual layer, color role logic keyed to the attention tiers, and independent logo mark architecture.
  *(See detailed execution guidance in `references/02_visual_identity_and_style_synthesis.md`)*

* **Phase 3: Spatial Architecture & Layout Grid**
  Divide physical canvas space into functional zones derived from the canvas's dominant axis, visibility, and content groups. Establish scale contrast ratios (>2:1), typographic hierarchy, visual anchors, and breathing room. Place each element (including the tagline) by attention tier and compositional balance, express the hierarchy across every weight dimension (scale, color, placement, isolation), and size elements within the band set by their legibility floor and their tier.
  *(See detailed execution guidance in `references/03_compositional_architecture_and_spatial_systems.md`)*

* **Phase 4: Semantic Prompt Synthesis**
  Construct the raw prompt using structured, highly dense design terminology organized from macro visual concept to specific zonal implementation.
  *(See detailed execution guidance in `references/04_prompt_synthesis_and_output_execution.md`)*

* **Phase 5: Boundary & Quality Verification**
  Audit the prompt against negative constraints: ensure zero fluff/buzzwords, verify all required copy is explicitly represented, confirm no added/invented items exist, verify the prompt directs rather than micro-manages, and confirm attention balance, scale calibration, and element-level distinctiveness.
  *(The Verification Checklist for this phase is in Section 5 of `references/04_prompt_synthesis_and_output_execution.md`)*

---

## 3. Reference Module Index

When executing specific phases of the workflow, refer to these foundational documents for detailed decision logic:

| File Path | Functional Domain |
| :--- | :--- |
| `references/01_strategic_analysis_and_deconstruction.md` | Brief analysis, communication objective, canvas shape and visibility, physical scale and legibility floor, viewing contexts, content filtering, attention tiering, and local market dynamics (including Indonesian UMKM context). |
| `references/02_visual_identity_and_style_synthesis.md` | Movement identification, shape language, color system architecture, and standalone logo mark strategy. |
| `references/03_compositional_architecture_and_spatial_systems.md` | Zoning derivation, typographic hierarchy, visual eye-tracking flow, negative space, attention balance, and scale-aware sizing. |
| `references/04_prompt_synthesis_and_output_execution.md` | Prompt precision principles, exclusion of generic language, boundary control, output construction, and verification. |

---

## 4. Universal Output Template

The framework's final deliverable must ALWAYS be a single, self-contained, semantically dense prompt structured according to the following standard template:

```
[Aspect Ratio] [Physical Media Type / Medium] for "[Brand Name]", [Specific Visual Design Movement / Tradition], [Color Palette Architecture: dominant, structural, and accent roles with their proportions]. [Form Language, Edge Behavior, and Overall Aesthetic Tone].

PRIMARY LOGO MARK & BRANDING:
[Detailed description of central mark/wordmark architecture, typography style, enclosure or open construction, and sub-descriptors. Ensure mark remains structurally independent of background elements].

COMPOSITION & LAYOUT ZONING:
[Zonal structural breakdown derived from the canvas's dominant axis, visibility, and content groups. Define precise locations and relative scale for focal hook, product displays, tagline, information blocks, and action badges, assigned by attention tier and balance].

VISUAL ELEMENTS & RENDERING TECHNIQUE:
[Specific description of key visual/product offerings, the representation mode and expressive character chosen for each visual layer (primary visual, typography, decoration), shading or depth technique, line weight, and emphasis of key features where the concept calls for it].

BACKGROUND, BORDERS & FINISH:
[Background texture, borders or their deliberate absence, decorative motifs, pattern work, and edge treatments].

TECHNICAL & EXECUTION CONSTRAINTS:
[Explicit rendering rules suited to the chosen medium and style: layout structure, contrast behavior, photographic or non-photographic stance, execution quality, and legibility from [X] distance for each tier].
```

---

## 5. Execution Rules & Prompt Directives

1. **Output Raw Prompt Only:** When generating the final response after applying the framework, output *only* the single expanded prompt block unless explicitly requested otherwise.
2. **Never Invent Contents:** Strictly enforce all hard contents (text copy, phone numbers, addresses, menu items, prices, and any other required element) provided in the user brief. Never omit required text or insert extra items.
3. **No Meta-Commentary or Fluff:** Exclude introductory conversational filler, self-congratulatory praise, and vague or evaluative descriptions that carry no visual instruction. Use objective, observable visual terminology.
4. **Preserve Generative Freedom:** Specify structural visual strategy, spatial relationships, and aesthetic parameters, but allow the target image-generation model to execute fine line rendering, lighting falloff, and organic textures naturally.
