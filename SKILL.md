---
name: print-design-prompt-framework
description: Universal framework for converting a business brief into a single, semantically dense image-generation prompt for print design (banners, posters, flyers, backdrops, feather flags, menus, signage, packaging inserts, and similar physical media). Use this skill whenever the user provides a business brief, brand identity, print media size or constraints, or asks for a print design prompt, banner prompt, poster prompt, flyer prompt, or any image-generation prompt for a physical print piece, especially for local UMKM or street-level commercial businesses, even if they do not mention "framework" or "prompt engineering" explicitly.
---

# Print Design Prompt Engineering Framework

A universal, principle-based system for translating business briefs, brand identities, print media constraints, and visual strategies into precise, semantically dense image-generation prompts.

**How to use this skill:** Work through the 5 phases in Section 2 in order. At the start of each phase, read the matching reference file listed in Section 3 before making decisions for that phase. Then output the final prompt using the template in Section 4 and the rules in Section 5. The Decision Context and Decision Protocol at the end of Section 2 govern every phase.

---

## 1. Philosophical Stance & Operating Limits

This framework operates on **strategic authority without execution micro-management**. It bridges high-level brand strategy and generative AI vision models through five core axioms:

1. **Principle-Driven Strategy:** Design decisions must emerge from structural analysis—media specs, viewing distance, business positioning, target psychology—never from static lookup tables, stock aesthetics, or predefined industry-to-style mappings.
2. **Distinctive Visual Autonomy:** Every output must possess a clear, non-generic design identity, anchored in one brand theme and personality that unifies every layer, with distinct form language, color logic, and typographic personality tailored to the specific business context. It must stand out from its neighbors through a distinct idea, not through volume, while belonging natively to its placement context. Each visual layer is its own deliberate, brief-specific choice, and functional legibility never dictates stylistic intensity.
3. **Semantic Density over Micro-Management:** Prompts communicate high-level concept, visual movement, composition, color palette, logo architecture, and spatial hierarchy using precise professional design terminology. Detailed pixel-level rendering and micro-textures are deliberately left to the generative vision model's creative interpretation.
4. **Contextual & Physical Reality:** Print design exists in physical space. Layouts must account for aspect ratio, viewing distance, ambient visual noise, exposure time, physical media substrate, and placement context (the setting, host surface, and surroundings the piece lives in). Visual weight, carried by scale, color, placement, and isolation together, is distributed by reader attention (what is read at a glance vs. only on closer reading), and element sizes are calibrated to the physical scale of the medium rather than to canvas proportion or a single viewing distance.
5. **Context-Justified Decisions:** No decision about any element, layer, or attribute comes from its category or from habit. Each is derived from the element's role in the hierarchy and the Decision Context (Section 2), and each is made explicit.

**Open-set rule:** Every list, category, ratio, or reference value in this skill that describes a design choice is a principle or a tendency along a continuum, never a closed set. Derive decisions from the principle. When a brief falls outside or between listed cases, extend the principle instead of forcing a fit. Hard-content fidelity, the output template, and the execution rules are fixed.

---

## 2. Master Decision Flow

When processing a brief, follow this sequential 5-phase cognitive pipeline:

```
[Phase 1: Strategic Brief Deconstruction]
   │  Analyze medium, viewing distance, copy density, USP, and local market context; compile the Decision Context.
   ▼
[Phase 2: Brand Theme & Visual Identity Synthesis]
   │  Establish the brand theme and personality, then select a specific design movement, form language, color architecture, and logo strategy.
   ▼
[Phase 3: Spatial Architecture & Layout Grid]
   │  Derive zoning from the canvas, place and size every element by tier, and set the focal anchor, reading path, and negative space.
   ▼
[Phase 4: Semantic Prompt Synthesis]
   │  Translate design decisions into a dense, structured, professional prompt text.
   ▼
[Phase 5: Boundary & Quality Verification]
   │  Strip generic buzzwords, verify strict brief content adherence, confirm generative freedom, and audit decision traceability.
```

### Phase Details & Reference Modules

* **Phase 1: Strategic Brief Deconstruction**
  * Deconstruct the business domain, communication objective, media substrate, placement context and its contextual register, aspect ratio, primary viewing distance, reading time, and mandatory content elements.
  * Rank every content element into an attention tier (glance / scan / deliberate). Determine the primary focus from the objective, the reader's task, usage, content structure, and recognition already supplied, never assuming it.
  * Derive the legibility floor from physical size and the distance at which each tier is read.
  * Capture what is distinctive about the business, product, name, and audience as raw material for the theme.
  * Assess whether the piece needs a pictorial subject at all, given the objective, content load, and reading time.
  * Compile everything into the Decision Context (see Decision Context & Decision Protocol below).
  *(See detailed execution guidance in `references/01_strategic_analysis_and_deconstruction.md`)*

* **Phase 2: Brand Theme & Visual Identity Synthesis**
  * First establish the brand's theme and personality, derived from the business, product, USP, audience, name, and placement context, pushing past the first literal association, and make the logo mark its canonical statement.
  * Determine the exact design movement or tradition that serves the theme and belongs natively in its placement context, drawn from the full range of design history and practice, including hybrids.
  * Define form language, edge behavior, the representation mode and expressive character of each visual layer, the subject, complexity, and style of any pictorial subject admitted, the palette's roles, size, and combination keyed to the attention tiers, and independent logo mark architecture.
  * Add the theme, personality, and style direction to the Decision Context.
  *(See detailed execution guidance in `references/02_visual_identity_and_style_synthesis.md`)*

* **Phase 3: Spatial Architecture & Layout Grid**
  * Confirm the tiering against the chosen style and pictorial decisions.
  * Divide physical canvas space into functional zones derived from the canvas's dominant axis, visibility, and content groups.
  * Establish scale contrast ratios (>2:1), typographic hierarchy, visual anchors, and breathing room.
  * Place each element (including the tagline) and set the role, scale, and placement of any pictorial subject by attention tier and compositional balance, deriving every placement and group form from function, relationship, and counterweight instead of a template.
  * Express the hierarchy across every weight dimension (scale, color, placement, isolation), and size elements within the band set by their legibility floor and their tier.
  * Audit the weight each element actually produces, including grounds, borders, and bands, against its tier. Reduce or remove any element that outweighs its tier, and remove anything the objective, hierarchy, or theme does not need.
  *(See detailed execution guidance in `references/03_compositional_architecture_and_spatial_systems.md`)*

* **Phase 4: Semantic Prompt Synthesis**
  * Construct the raw prompt using structured, highly dense design terminology organized from macro visual concept to specific zonal implementation.
  * Carry every Decision Protocol decision into the prompt as an explicit directive, leaving no attribute to default.
  *(See detailed execution guidance in `references/04_prompt_synthesis_and_output_execution.md`)*

* **Phase 5: Boundary & Quality Verification**
  * Audit the prompt internally against the Verification Checklist and revise until every item passes: content fidelity and language, identity and context, hierarchy and layout, and decision traceability and distinctiveness.
  *(The Verification Checklist for this phase is in Section 5 of `references/04_prompt_synthesis_and_output_execution.md`)*

### Decision Context & Decision Protocol
**Decision Context:** Compiled at the end of Phase 1, extended in Phase 2, and consulted by every later decision: objective and the reader's task; audience (who, state, familiarity, local codes); medium (physical scale, mode of use, viewing distances, visibility); placement context and contextual register; content load, attention tiers, and primary focus; brand theme and personality; style direction (movement, representation modes, expressive character, palette logic).

**Decision Protocol:** Every attribute of every element and layer (size, position, extent, grouping, boundary, color, typography, rendering, finish, and any other) is decided in this order:
1. **Role:** The element's tier and function in the hierarchy, including whether it is present at all.
2. **Relevant context:** The Decision Context parameters that bear on this attribute.
3. **Candidates:** Several viable options that differ meaningfully, including the prototype (the choice most briefs of this kind would default to). The prototype is chosen only when it is the strongest fit for this brief, never by reflex.
4. **Test:** Necessity (what is lost without it), weight proportionate to role as the attributes actually produce it (across dimensions, including area), coherence with the theme, fit with the placement context, legibility at the floor, and consistency with decisions already made.
5. **Commit:** State the choice explicitly as a specific directive. No attribute is left to the model's default.

**Working discipline:** The protocol is how decisions are made, not extra output. Attributes of one element that share context may be decided together, and only the committed directives appear in the prompt.

**Whole-piece consistency:** Decisions are made per element but judged together. The weight budget balances across tiers, and color, form, spacing, and voice share one underlying logic, the theme. The piece is also subtracted from: any element or device whose removal would not weaken the objective, the hierarchy, or the theme is removed.

---

## 3. Reference Module Index

When executing specific phases of the workflow, refer to these foundational documents for detailed decision logic:

| File Path | Functional Domain |
| :--- | :--- |
| `references/01_strategic_analysis_and_deconstruction.md` | Brief analysis, communication objective, placement context, canvas shape and visibility, physical scale and legibility floor, viewing contexts, content filtering, attention tiering, pictorial need, and local market dynamics (including Indonesian UMKM context). |
| `references/02_visual_identity_and_style_synthesis.md` | Brand theme and personality, movement identification, shape language, color system architecture and palette size, pictorial subject design, and standalone logo mark strategy. |
| `references/03_compositional_architecture_and_spatial_systems.md` | Zoning derivation, typographic hierarchy, visual eye-tracking flow, negative space, attention balance, scale-aware sizing, placement logic, and pictorial subject role, scale, and placement. |
| `references/04_prompt_synthesis_and_output_execution.md` | Prompt precision principles, exclusion of generic language, boundary control, output construction, and verification. |

---

## 4. Universal Output Template

The framework's final deliverable must ALWAYS be a single, self-contained, semantically dense prompt structured according to the following standard template:

```
[Aspect Ratio] [Physical Media Type / Medium] for "[Brand Name]", [Brand Theme & Personality: the single creative idea as direct visual direction only (what it is, and the visible character and atmosphere it dictates), with no rationale], [Specific Visual Design Movement / Tradition], [Color Palette Architecture: the color roles, the hues chosen for them, and their relative proportions]. [Form Language, Edge Behavior, and Overall Aesthetic Tone].

PRIMARY LOGO MARK & BRANDING:
[Detailed description of mark/wordmark architecture, its role and relative scale in the hierarchy, how it embodies the theme and personality, typography style, enclosure or open construction, and sub-descriptors. Ensure mark remains structurally independent of background elements].

COMPOSITION & LAYOUT ZONING:
[Zonal structural breakdown derived from the canvas's dominant axis, visibility, and content groups. Define specific placement and relative scale, expressed as relationships, for focal anchor, any pictorial subject, tagline, information blocks, and action badges, assigned by attention tier and balance. Every hard-content string appears verbatim, in quotation marks, at its placed position].

VISUAL ELEMENTS & RENDERING TECHNIQUE:
[Each pictorial subject admitted (subject, complexity, role), or a statement that none is used and the piece is carried by type, mark, and layout; the representation mode and expressive character chosen for each visual layer (primary visual, typography, decoration), shading or depth technique, line weight, and emphasis of key features where the concept calls for it].

BACKGROUND, BORDERS & FINISH:
[Background treatment, borders, decorative motifs, and edge treatments, each only where it earns its place, or a statement that none is used].

TECHNICAL & EXECUTION CONSTRAINTS:
[Explicit rendering rules suited to the chosen medium and style: layout structure, contrast behavior, photographic or non-photographic stance, execution quality, and legibility at the viewing distances involved].
```

---

## 5. Execution Rules & Prompt Directives

1. **Output Raw Prompt Only:** When generating the final response after applying the framework, output *only* the single expanded prompt block unless explicitly requested otherwise. The Decision Context, protocol work, and audits stay internal.
2. **Never Invent Contents:** Strictly enforce all hard contents (text copy, phone numbers, addresses, menu items, prices, and any other required element) provided in the user brief. Never omit required text or insert extra items.
3. **No Meta-Commentary or Fluff:** Exclude introductory conversational filler, self-congratulatory praise, and vague or evaluative descriptions that carry no visual instruction. Use objective, observable visual terminology. Every phrase in the prompt is a visual directive; reasoning, justification, and intent statements stay out. Framework terminology (tiers, protocol, context) never appears in the prompt.
4. **Preserve Generative Freedom:** Specify structural visual strategy, spatial relationships, and aesthetic parameters, but allow the target image-generation model to execute fine line rendering, lighting falloff, and organic textures naturally.
5. **English Output:** Write the entire prompt in English, whatever language the brief uses. Only literal hard content (brand name, copy, prices, contact details, addresses, and any other supplied string) is reproduced verbatim in its original language, placed in quotation marks; all descriptions, directions, and labels are English.
6. **Relational Direction:** Direct position, scale, and proportion through relationships (order, alignment, relative size, weight) and describe color by hue and role. Measurements, coordinates, angles, counts, and color codes appear only when the brief supplies them.
7. **Economy:** State each decision once, in the slot where it belongs.
