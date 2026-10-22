---
name: print-design-prompt-framework
description: Universal framework for converting a business brief into a single, semantically dense image-generation prompt for print design (banners, posters, flyers, backdrops, feather flags, menus, signage, packaging inserts, and similar physical media). Use this skill whenever the user provides a business brief, brand identity, print media size or constraints, or asks for a print design prompt, banner prompt, poster prompt, flyer prompt, or any image-generation prompt for a physical print piece, especially for local UMKM or street-level commercial businesses, even if they do not mention "framework" or "prompt engineering" explicitly.
---

# Print Design Prompt Engineering Framework

A universal, principle-based system for translating business briefs, brand identities, print media constraints, and visual strategies into precise, semantically dense image-generation prompts.

**How to use this skill:** Work through the 5 phases in Section 2 in order. At the start of each phase, read the matching reference file listed in Section 3 before making decisions for that phase. Then output the final prompt using the template in Section 4 and the rules in Section 5. The Decision Context and Decision Protocol at the end of Section 2 govern every phase. Foundational decisions are deliberated and locked before the decisions they govern; the pipeline order exists to enforce this.

---

## 1. Philosophical Stance & Operating Limits

This framework operates on **strategic authority without execution micro-management**. It bridges high-level brand strategy and generative AI vision models through seven core axioms:

1. **Principle-Driven Strategy:** Design decisions must emerge from structural analysis—media specs, viewing distance, business positioning, target psychology—never from static lookup tables, stock aesthetics, or predefined industry-to-style mappings.
2. **Distinctive Visual Autonomy:** Every output must possess a clear, non-generic design identity, anchored in one brand theme and personality that unifies every layer, with distinct form language, color logic, and typographic personality tailored to the specific business context. It must stand out from its neighbors through a distinct idea, not through volume, while belonging natively to its placement context. Each visual layer is its own deliberate, brief-specific choice: its representation mode is chosen by the job it must do (hybrids across layers are as valid as a single mode), personality is carried by the layers best placed to carry it, and functional legibility never dictates stylistic intensity. Restraint calibrates intensity and never removes character: tier governs a layer's volume, not its voice, and a plain layer is a choice the theme must earn.
3. **Semantic Density over Micro-Management:** Prompts communicate high-level concept, visual movement, composition, color palette, logo architecture, and spatial hierarchy using precise professional design terminology. Detailed pixel-level rendering and micro-textures are deliberately left to the generative vision model's creative interpretation. Density includes specificity: every stylistic term is resolved to the level at which it discriminates, because a category name alone leaves the decision to the model.
4. **Contextual & Physical Reality:** Print design exists in physical space. Layouts must account for aspect ratio, viewing distance, ambient visual noise, exposure time, physical media substrate, and placement context (the setting, host surface, and surroundings the piece lives in). Visual weight, carried by scale, color, placement, and isolation together, is distributed by reader attention (what is read at a glance vs. only on closer reading), and element sizes are calibrated to the physical scale of the medium rather than to canvas proportion or a single viewing distance. Canvas area is the scarcest weight dimension because it is taken directly from content and breathing room, so it is spent last: hierarchy is built first with the cheaper dimensions (contrast, isolation, placement, color), and no element is owed area by its category or role.
5. **Hierarchically Derived Decisions:** No decision about any element, layer, or attribute comes from its category or from habit, and none is made in isolation. Foundational decisions (theme, mood, movement, representation modes, palette, typographic voice, composition) are tailored to the whole Decision Context read jointly (business, objective, audience, medium, and placement together); a foundational decision that would survive a change in that context unchanged is generic. Derived decisions (every attribute of every element) serve the foundational decisions through the element's tier and purpose. Upstream governs downstream, and each decision is made explicit.
6. **Deliberation Proportional to Leverage:** The more a decision governs, the more deliberately it is made. Foundational decisions are explored across meaningfully different candidates, tested, and locked before anything they govern is decided; derived decisions follow by derivation, not fresh invention. Rushing is the skipping of this order.
7. **Divided Communicative Labor:** A piece carries several messages (what the brand is, what it offers, how it should feel, what the reader should do). Each is carried by the layer best placed to carry it, once, and not echoed through every layer; layers that already carry a message free the others to carry what they alone can. Each foundational decision draws on every context dimension that bears on it, never anchoring on the most salient or literal input. A fact merely adjacent to the brand (its place, category, or origin) constrains fit until the brand's own identity connects it to the personality.

**Open-set rule:** Every list, category, ratio, or reference value in this skill that describes a design choice is a principle or a tendency along a continuum, never a closed set. Derive decisions from the principle. When a brief falls outside or between listed cases, extend the principle instead of forcing a fit. Hard-content fidelity, the output template, and the execution rules are fixed.

---

## 2. Master Decision Flow

When processing a brief, follow this sequential 5-phase cognitive pipeline:

```
[Phase 1: Strategic Brief Deconstruction]
   │  Analyze business, objective, audience, medium, placement, copy density, and local market context; weigh them, name their tensions, and compile the Decision Context.
   ▼
[Phase 2: Brand Theme & Visual Identity Synthesis]
   │  Lock the foundational identity decisions as one system: theme and personality, mood, design movement, representation modes, color architecture, typographic voice, and logo strategy.
   ▼
[Phase 3: Spatial Architecture & Layout Grid]
   │  Lock the composition strategy, then derive zoning, placement, size, presence, and visibility of every element from it, by tier and purpose.
   ▼
[Phase 4: Semantic Prompt Synthesis]
   │  Translate design decisions into a dense, structured, professional prompt text.
   ▼
[Phase 5: Boundary & Quality Verification]
   │  Strip generic buzzwords, verify strict brief content adherence, confirm generative freedom, and audit decision traceability, re-opening the upstream cause of any failure.
```

### Phase Details & Reference Modules

* **Phase 1: Strategic Brief Deconstruction**
  * Deconstruct the business (domain, background, positioning), communication objective and intended reader response, media substrate, placement context and its contextual register, aspect ratio, primary viewing distance, reading time, and mandatory content elements.
  * Rank every content element into an attention tier (glance / scan / deliberate). Determine the primary focus from the objective, the reader's task, usage, content structure, and recognition already supplied, never assuming it.
  * Derive the legibility floor from physical size and the distance at which each tier is read.
  * Capture what is distinctive about the business, product, name, and audience as raw material for the theme, reading the name's full meaning and the whole brief rather than only what the brief emphasizes.
  * Inventory the messages the piece must carry and note which the content and any pictorial subject will already carry; the rest is the work of the identity layers.
  * Determine how much the piece is looked at versus read and, from that, the pictorial commitment it can support (absent, ambient, supporting, or dominant), given the objective, medium, content load, and reading time.
  * Weigh the parameters by how much each governs in this brief and name the tensions between them (where serving one strains another). The foundational decisions exist to resolve these tensions, which is what makes them tailor-made.
  * Compile everything into the Decision Context (see Decision Context & Decision Protocol below).
  *(See detailed execution guidance in `references/01_strategic_analysis_and_deconstruction.md`)*

* **Phase 2: Brand Theme & Visual Identity Synthesis**
  * First establish the brand's theme and personality, derived from what the brand is (its name, character, heritage, and audience) and from what the other layers will not already carry, admitting facts about its situation such as place, category, or origin only where its own identity connects them to the personality, expressing the idea behind the first association in a fresh form rather than replacing it, and make the logo mark its canonical statement.
  * Determine the exact design movement or tradition that serves the theme and belongs natively in its placement context, drawn from the full range of design history and practice, including hybrids, with its leading and supporting voices resolved to distinguishing traits.
  * Define form language, edge behavior, the representation mode of each visual layer matched to the job it does (a single mode or a hybrid, with the leading layer and what unifies the layers) and the expressive character of each, the subject, complexity, and specific style of any pictorial subject admitted, the palette's roles, size, and combination keyed to the attention tiers with color logic set from the personality before any hue is chosen, any ornament calibrated in weight but drawn from the theme's world, and independent logo mark architecture. Resolve every stylistic choice to a discriminating level of specificity.
  * Add the theme, personality, mood, and style direction to the Decision Context, check the foundational decisions against each other as one system, and lock them.
  *(See detailed execution guidance in `references/02_visual_identity_and_style_synthesis.md`)*

* **Phase 3: Spatial Architecture & Layout Grid**
  * Confirm the tiering against the chosen style and pictorial decisions.
  * Decide the composition strategy (axis commitment, focal anchor, reading path, density and negative-space stance) as a foundational decision, then lock it.
  * Divide physical canvas space into functional zones derived from the canvas's dominant axis, visibility, and content groups.
  * Establish scale contrast ratios (>2:1), typographic hierarchy, visual anchors, and breathing room.
  * Place each element (including the tagline) by attention tier and compositional balance, deriving every placement and group form from function, relationship, and counterweight instead of a template. Set the role, placement, and scale of any pictorial subject by sufficiency (the smallest scale and weight at which it still does its job) within the area left after required content at its floor and breathing room.
  * Set each element's purpose, presence, and visibility, deriving its attributes from the foundational decisions it serves, its tier, and its purpose.
  * Express the hierarchy across every weight dimension (scale, color, placement, isolation), and size elements within the band set by their legibility floor and their tier.
  * Audit the weight each element actually produces, including grounds, borders, and bands, against its tier, and reduce or remove any element that outweighs its tier. Audit expression as well: where a layer (ground, type, containers, edges) is bare or default without the theme calling for stillness, give it the theme's character at a volume its tier allows. Remove only what adds weight without adding meaning.
  *(See detailed execution guidance in `references/03_compositional_architecture_and_spatial_systems.md`)*

* **Phase 4: Semantic Prompt Synthesis**
  * Construct the raw prompt using structured, highly dense design terminology organized from macro visual concept to specific zonal implementation.
  * Carry every Decision Protocol decision into the prompt as an explicit directive, leaving no attribute to default.
  *(See detailed execution guidance in `references/04_prompt_synthesis_and_output_execution.md`)*

* **Phase 5: Boundary & Quality Verification**
  * Audit the prompt internally against the Verification Checklist and revise until every item passes: content fidelity and language, identity and context, hierarchy and layout, and decision traceability and distinctiveness, tracing each failure to its upstream cause and re-deriving what that cause governs.
  *(The Verification Checklist for this phase is in Section 5 of `references/04_prompt_synthesis_and_output_execution.md`)*

### Decision Context & Decision Protocol
**Decision Context:** Compiled at the end of Phase 1, extended in Phase 2, and consulted by every later decision: the business (background, positioning, distinctive substance); objective, the reader's task, and the intended reader response; audience (who, state, familiarity, local codes); medium (physical scale, mode of use, viewing distances, visibility); placement context and contextual register; content load, attention tiers, and primary focus; the weight each parameter carries in this brief and the tensions between them; brand theme, personality, and mood; style direction (movement, representation modes, expressive character, palette logic).

**Decision Protocol:** Decisions fall into two classes that differ in their source of authority and in the depth of deliberation they receive.

**Foundational decisions** govern all others: primary focus, the allocation of messages across layers, theme and personality, mood, design movement with its leading and supporting voices, the representation mode of each visual layer, pictorial commitment, palette architecture, typographic voice, mark architecture, and composition strategy. Their authority is the whole Decision Context read jointly, with its tensions resolved. Each is deliberated in full:
1. **Frame:** The job the decision does and every Decision Context parameter that bears on it, weighted as this brief weights them.
2. **Diverge:** Candidates that differ in underlying idea, not only in label, drawn at three depths: the apparent (what proximity, category, or literal association suggests, which includes the prototype), the underlying (what that is actually about), and the personal (what this brand's character would choose). The apparent is the baseline to beat and is chosen only when it is the strongest fit for the personality, never by reflex.
3. **Test:** Tailoring (would the choice change if the business, audience, medium, or placement changed? if not, it is generic), range (it draws on every context dimension that bears on it, not on the most salient or literal input), complementarity (it carries what the other layers do not already carry), relevance (each context fact it draws on is connected to the brand's own identity, claim, or audience; proximity or category membership is not a connection), expression (it lets the personality be perceived, not merely avoids clashing), resolution of the brief's tensions, belonging and distinction within the placement context, generative power (does it settle downstream choices), legibility at the medium's distances, and coherence with the foundational decisions already made.
4. **Specify:** Resolve it to a discriminating level of specificity (`02`, Section 2.2).
5. **Lock:** Foundational decisions co-constrain one another, so they are checked against each other as one system and locked before the first derived decision is made.

**Derived decisions** are every attribute of every element and layer (presence, visibility, size, position, extent, grouping, boundary, color, typography, rendering, finish, complexity). Their authority is the foundational decisions plus the element's own role. They are derived, not reinvented:
1. **Role:** The element's tier (when it is read), its purpose (what it does for the reader), and its presence and visibility, including whether it exists at all (`03`, Section 5.5).
2. **Governing decisions:** The foundational decisions this attribute must express or stay subordinate to.
3. **Derive:** The value that role and governing decisions imply. Alternatives are weighed only where more than one derivation survives, and the prototype is chosen only when it is what the derivation yields.
4. **Test:** Necessity (what is lost without it, including loss of character), weight proportionate to role as the attributes actually produce it (across dimensions, including area), voice (its form carries the theme's character at its tier's volume, never a default), legibility at the floor, and consistency with sibling decisions.
5. **Commit:** State the choice explicitly as a specific directive. No attribute is left to the model's default.

**Conflict rule:** When a derived decision cannot satisfy its governing decisions without breaking hierarchy or legibility, trace the conflict to its cause. If a foundational decision is the cause, revise it and re-derive what it governs. Never patch downstream.

**Working discipline:** The protocol is how decisions are made, not extra output, but internal never means abbreviated: each foundational decision is deliberated separately and in full before any prompt text is drafted, while derived attributes that share role and governing decisions may be decided together. Only the committed directives appear in the prompt.

**Whole-piece consistency:** Decisions are made per element but judged together. The weight budget balances across tiers, and color, form, spacing, and voice share one underlying logic, the theme. The piece is also edited for excess and for bareness. Any element or device that adds weight without adding meaning is removed or reduced, but restraint calibrates weight, complexity, and contrast before it removes expression, and a layer left plain must be so because the theme calls for stillness there, not by omission.

---

## 3. Reference Module Index

When executing specific phases of the workflow, refer to these foundational documents for detailed decision logic:

| File Path | Functional Domain |
| :--- | :--- |
| `references/01_strategic_analysis_and_deconstruction.md` | Brief analysis, business background, communication objective and intended response, placement context, context weights and tensions, canvas shape and visibility, physical scale and legibility floor, viewing contexts, content filtering, attention tiering, reception balance and pictorial commitment, and local market dynamics (including Indonesian UMKM context). |
| `references/02_visual_identity_and_style_synthesis.md` | Brand theme sourcing, relevance gating, message allocation, personality, and mood, movement identification and style specificity, representation modes and hybrid integration, shape language, color logic, hue sourcing, and palette size, pictorial subject design, ornament derivation, and standalone logo mark strategy. |
| `references/03_compositional_architecture_and_spatial_systems.md` | Zoning derivation, element purpose, presence, and visibility, typographic hierarchy, visual eye-tracking flow, negative space, attention balance, scale-aware sizing, placement logic, and pictorial subject role, sufficiency sizing, and placement. |
| `references/04_prompt_synthesis_and_output_execution.md` | Prompt precision and specificity principles, exclusion of generic language, boundary control, output construction, and verification. |

---

## 4. Universal Output Template

The framework's final deliverable must ALWAYS be a single, self-contained, semantically dense prompt structured according to the following standard template:

```
[Aspect Ratio] [Physical Media Type / Medium] for "[Brand Name]", [Brand Theme & Personality: the single creative idea as direct visual direction only (what it is, and the visible character and atmosphere it dictates), with no rationale], [Governing Design Movement / Tradition resolved to its distinguishing traits, with the supporting voice when hybrid], [Color Palette Architecture: the color roles, the hues chosen for them, and their relative proportions]. [Form Language, Edge Behavior, and Overall Aesthetic Tone].

PRIMARY LOGO MARK & BRANDING:
[Detailed description of mark/wordmark architecture, its role and relative scale in the hierarchy, how it embodies the theme and personality, typography style, enclosure or open construction, and sub-descriptors. Ensure mark remains structurally independent of background elements].

COMPOSITION & LAYOUT ZONING:
[Zonal structural breakdown derived from the canvas's dominant axis, visibility, and content groups. Define specific placement and relative scale, expressed as relationships, for focal anchor, any pictorial subject, tagline, information blocks, and action badges, assigned by attention tier and balance. Every hard-content string appears verbatim, in quotation marks, at its placed position].

VISUAL ELEMENTS & RENDERING TECHNIQUE:
[Each pictorial subject admitted (subject, complexity, role, relative scale, specific style), or a statement that none is used and the piece is carried by type, mark, and layout; the representation mode, specific technique or lineage, and expressive character chosen for each visual layer (primary visual, typography, decoration), which layer leads and what binds the layers when they differ in mode, shading or depth technique, line weight, and emphasis of key features where the concept calls for it].

BACKGROUND, BORDERS & FINISH:
[Ground character and surface treatment, borders, decorative motifs, and edge treatments, each carrying the theme's character at the visibility its purpose needs, or a statement that a layer is deliberately plain].

TECHNICAL & EXECUTION CONSTRAINTS:
[Explicit rendering rules suited to the chosen medium and style: layout structure, contrast behavior, photographic or non-photographic stance, execution quality, and legibility at the viewing distances involved].
```

---

## 5. Execution Rules & Prompt Directives

1. **Output Raw Prompt Only:** When generating the final response after applying the framework, output *only* the single expanded prompt block unless explicitly requested otherwise. The Decision Context, protocol work, and audits stay internal, but are performed in full before the prompt is written.
2. **Never Invent Contents:** Strictly enforce all hard contents (text copy, phone numbers, addresses, menu items, prices, and any other required element) provided in the user brief. Never omit required text or insert extra items.
3. **No Meta-Commentary or Fluff:** Exclude introductory conversational filler, self-congratulatory praise, and vague or evaluative descriptions that carry no visual instruction. Use objective, observable visual terminology. Every phrase in the prompt is a visual directive; reasoning, justification, and intent statements stay out. Framework terminology (tiers, protocol, context) never appears in the prompt.
4. **Preserve Generative Freedom:** Specify structural visual strategy, spatial relationships, and aesthetic parameters, but allow the target image-generation model to execute fine line rendering, lighting falloff, and organic textures naturally.
5. **English Output:** Write the entire prompt in English, whatever language the brief uses. Only literal hard content (brand name, copy, prices, contact details, addresses, and any other supplied string) is reproduced verbatim in its original language, placed in quotation marks; all descriptions, directions, and labels are English.
6. **Relational Direction:** Direct position, scale, and proportion through relationships (order, alignment, relative size, weight) and describe color by hue and role. Measurements, coordinates, angles, counts, and color codes appear only when the brief supplies them.
7. **Economy:** State each decision once, in the slot where it belongs.
8. **Specificity:** Every stylistic term is resolved to a level that discriminates within its category. A category name never stands alone as a decision.
