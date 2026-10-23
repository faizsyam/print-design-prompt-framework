---
name: print-design-prompt-framework
description: Universal framework for converting a business brief into a single, semantically dense image-generation prompt for print design (banners, posters, flyers, backdrops, feather flags, menus, signage, packaging inserts, and similar physical media). Use this skill whenever the user provides a business brief, brand identity, print media size or constraints, or asks for a print design prompt, banner prompt, poster prompt, flyer prompt, or any image-generation prompt for a physical print piece, especially for local UMKM or street-level commercial businesses, even if they do not mention "framework" or "prompt engineering" explicitly.
---

# Print Design Prompt Engineering Framework

A principle-based system for turning a business brief into one precise image-generation prompt for a physical print piece. Its output answers a specific design problem; it is never a styled version of the business category.

**How to use:** Work through the five phases in Section 2 in order. At the start of each phase, read the matching reference file (Section 3). Foundational decisions are explored and locked before the decisions they govern. Output the prompt with the template in Section 4 and the rules in Section 5.

---

## 1. Principles

1. **Problem before style.** Design starts from a design problem: the strain that appears where the brand's truth, the audience's state, the objective, the medium, and the placement meet. Style, imagery, color, and type are answers to that problem, never starting points. Context dimensions are read through their interactions, because the same attribute means different things to different audiences, placements, and distances. No dimension is interpreted alone.
2. **Insight before concept.** A distinctive idea comes from an insight: a non-obvious truth about this brand, for this reader, at this moment of encounter, that the piece can make felt. The concept is that insight made visible as a specific world, device, structure, or behavior, concrete enough to settle later choices. A mood adjective or style label is not a concept.
3. **Associations are hypotheses.** The first association a name, product, category, or place offers is the baseline every competitor shares. Trace it to what it is actually about, keep it only if the brand itself earns it, and express it as this brand's own form of that idea. A fact merely adjacent to the brand constrains fit until the brand's identity connects it to the personality.
4. **Range, not a single note.** A piece is one-dimensional when every layer states the same thing the same way. A distinctive piece has one governing concept carried with range: a personality made of qualities held in productive tension, a payoff at each distance from which the piece is actually read, and layers that each contribute what no other layer does.
5. **Approach follows the job.** Each visual layer receives a kind of making (captured, drawn, constructed, typographic, or a hybrid) according to the kind of truth it must deliver, and an execution style according to the stance the piece takes toward its subject and viewer. Neither is a default and neither is set by category.
6. **Divided labor.** A piece carries several messages (what the brand is, what it offers, how it should feel, what to do). Each goes to the layer best placed to carry it, once. Layers that already carry a message free the others to carry what they alone can.
7. **Physical reality.** Aspect ratio, physical size, viewing distance, exposure time, substrate, and placement set what can be read and what looks native. Weight comes from scale, color, placement, isolation, and detail together, distributed by reader attention. Canvas area is the last dimension spent. Size is bounded below by the legibility floor and above by tier.
8. **Deliberation proportional to leverage.** What governs more is explored more widely, tested, and locked first. What is governed is derived, not reinvented.
9. **Voice at every volume.** Tier sets an element's volume, never its voice. Restraint lowers intensity and complexity before it removes character, and a plain layer is a choice the concept must call for.
10. **Open set.** Every list, ratio, or reference in this skill is a tendency along a continuum. Where a brief falls outside it, extend the principle. Hard-content fidelity, the output template, and the execution rules are fixed.

---

## 2. Master Decision Flow

```
[Phase 1: Design Problem]      Read the brief, weigh the context, find its interactions and tensions, state the insight.
   ▼
[Phase 2: Concept & Identity]  Concept, message allocation, visual approach per layer, movement, color, type, mark. Lock as one system.
   ▼
[Phase 3: Composition]         Composition strategy, then zoning, placement, size, and presence of every element.
   ▼
[Phase 4: Prompt Synthesis]    Carry every decision into the template as an explicit visual directive.
   ▼
[Phase 5: Verification]        Audit, trace each failure to its upstream cause, re-derive.
```

* **Phase 1: Design Problem** (`references/01_strategic_analysis_and_deconstruction.md`)
  * Deconstruct the business, objective and intended reader response, audience and moment of encounter, medium, placement and its contextual register, content, and reading time.
  * Tier content by when the reader needs it, determine the primary focus, derive legibility floors, and set the reception balance and a provisional pictorial ceiling.
  * Weigh the parameters, read how they interact, name the tensions, and state the design problem and the insight it opens.
* **Phase 2: Concept & Identity** (`references/02_visual_identity_and_style_synthesis.md`)
  * Derive the concept, personality, and mood from the insight, drawing on identity first and then on what other layers will not carry, and allocate each message to its carrier.
  * Assign each visual layer its kind of making by the job it does and resolve its execution style from the stance the piece takes. Confirm or revise the pictorial commitment with these decisions.
  * Choose movement, form language, color logic, typographic voice, any ornament, and the mark. Check all of it as one system and lock it.
* **Phase 3: Composition** (`references/03_compositional_architecture_and_spatial_systems.md`)
  * Confirm the tiering and primary focus against the locked identity decisions, then lock a composition strategy that carries the concept through structure.
  * Derive every element's zone, position, size, presence, and treatment from tier, purpose, and the foundational decisions.
  * Audit the weight each element actually produces and the expression and range each layer actually carries.
* **Phase 4: Prompt Synthesis** (`references/04_prompt_synthesis_and_output_execution.md`)
  * Write the prompt from macro concept to zonal implementation. Every decision becomes an observable directive and no attribute is left to default.
* **Phase 5: Verification**
  * Run the checklist in `references/04`, Section 5.

### Decision Context & Decision Protocol

**Decision Context:** Compiled in Phase 1, extended in Phase 2, consulted by every later decision. It holds: business and positioning; objective, reader task, and intended response; audience and moment of encounter; medium and physical scale; placement and register; content load, tiers, and primary focus; parameter weights, interactions, and tensions; the design problem and insight; then concept, personality, mood, approach per layer, and style direction.

**Foundational decisions** govern all others: primary focus, message allocation, concept and personality, mood, kind of making and execution style per layer, pictorial commitment, movement, palette architecture, typographic voice, mark architecture, and composition strategy. Each is made in full:
1. **Frame:** State the job of the decision and which context parameters, and which interactions among them, bear on it.
2. **Diverge:** Generate candidates that differ in underlying idea, building them from different dominant context dimensions or interactions so they are genuinely distinct, at three depths: the apparent (what proximity, category, or the prototype suggests), the underlying (what that is about), and the personal (what this brand's character would choose). The apparent is the baseline to beat and is chosen only when it is the strongest fit.
3. **Test:**
   * *Tailoring:* would it change if the business, audience, medium, or placement changed? If not, it is generic.
   * *Earned connection:* every context fact it draws on is connected to the brand's own identity, claim, or audience, not merely nearby.
   * *Resolution:* it resolves a tension of this brief.
   * *Range:* it carries something other layers do not, and it holds a tension rather than one note.
   * *Belonging and distinction:* it looks native in the placement and differs from neighbors by idea, not by volume.
   * *Function:* it is legible at the medium's distances and settles downstream choices.
   * *Coherence:* it agrees with the foundational decisions already made.
4. **Specify:** Resolve it to a level that discriminates (`02`, Section 5).
5. **Lock:** Check the foundational decisions against each other as one system. Lock them in two stages: identity decisions at the end of Phase 2, composition strategy at the start of Phase 3, checked against the identity. No derived decision precedes the lock that governs it.

**Derived decisions** are every attribute of every element and layer. Each is derived from the element's tier (when it is read), its purpose (what it does for the reader), its presence (whether and how visibly it exists), the physical conditions under which it is seen, and the foundational decisions it serves. Test each for necessity, proportionate weight as its attributes actually produce it, voice, legibility at the floor, and consistency with siblings. Commit each as an explicit directive.

**Conflict rule:** When a derived decision cannot satisfy its governing decisions without breaking hierarchy or legibility, trace the conflict to its cause, revise the foundational decision, and re-derive what it governs. Never patch downstream.

**Working discipline:** Deliberation is internal but never abbreviated. Each foundational decision is explored separately and in full before any prompt text is drafted. Only committed directives appear in the prompt.

---

## 3. Reference Module Index

| File Path | Functional Domain |
| :--- | :--- |
| `references/01_strategic_analysis_and_deconstruction.md` | Context deconstruction, interactions, tensions, design problem and insight, physical scale and legibility, placement register, content filtering, attention tiering, pictorial commitment, local market context. |
| `references/02_visual_identity_and_style_synthesis.md` | Concept derivation, personality, mood, range, message allocation, visual approach and execution style per layer, movement, color, typographic voice, specificity, ornament, mark. |
| `references/03_compositional_architecture_and_spatial_systems.md` | Composition strategy, zoning, typographic hierarchy, grouping, negative space, weight balance, sizing, placement, pictorial role, presence. |
| `references/04_prompt_synthesis_and_output_execution.md` | Prompt precision, genericness control, boundary control, output construction, verification checklist. |

---

## 4. Universal Output Template

The final deliverable is ALWAYS a single, self-contained, semantically dense prompt in this structure:

```
[Aspect Ratio] [Physical Media Type / Medium] for "[Brand Name]", [Creative Concept & Personality: the single idea as direct visual direction only (what is visibly present, how forms, type, and color behave, and the atmosphere that results), with no rationale], [Governing Design Movement / Tradition resolved to its distinguishing traits, with the supporting voice when hybrid], [Color Palette Architecture: the color roles, the hues chosen for them, and their relative proportions]. [Form Language, Edge Behavior, and Overall Aesthetic Tone].

PRIMARY LOGO MARK & BRANDING:
[Mark/wordmark architecture, its role and relative scale in the hierarchy, how it embodies the concept, typography style, enclosure or open construction, and sub-descriptors. The mark remains structurally independent of background elements].

COMPOSITION & LAYOUT ZONING:
[Zonal structure derived from the canvas's dominant axis, visibility, and content groups. Specific placement and relative scale, expressed as relationships, for the focal anchor, any pictorial subject, tagline, information blocks, and action badges. Every hard-content string appears verbatim, in quotation marks, at its placed position].

VISUAL ELEMENTS & RENDERING TECHNIQUE:
[Each pictorial subject admitted (subject, complexity, role, relative scale) or a statement that none is used; for each visual layer, its kind of making, its execution style resolved to observable properties (vantage, light, depth, subject state, and grade for captured work; lineage, medium, line, and simplification for drawn work; geometric logic and rhythm for constructed work), and its expressive character; which layer leads and what binds the layers when they differ].

BACKGROUND, BORDERS & FINISH:
[Ground character and surface treatment, borders, decorative motifs, and edge treatments, each carrying the concept's character at the visibility its purpose needs, or a statement that a layer is deliberately plain].

TECHNICAL & EXECUTION CONSTRAINTS:
[Rendering rules suited to the medium and style: layout structure, contrast behavior, photographic or non-photographic stance, execution quality, and legibility at the viewing distances involved].
```

---

## 5. Execution Rules & Prompt Directives

1. **Output Raw Prompt Only:** Output only the single prompt block unless asked otherwise. The Decision Context, protocol work, and audits stay internal and are completed before the prompt is written.
2. **Never Invent Contents:** Enforce all hard content (copy, numbers, addresses, menu items, prices, and any other required element) exactly as supplied. Never omit required text or add items.
3. **No Meta-Commentary:** Every phrase is an objective, observable visual directive. Reasoning, justification, intent, evaluative language, and framework terminology never appear in the prompt.
4. **Preserve Generative Freedom:** Specify structure, relationships, and aesthetic parameters. Leave fine line rendering, lighting falloff, and organic texture to the model.
5. **English Output:** Write the entire prompt in English whatever language the brief uses. Only literal hard content is reproduced verbatim in its original language, in quotation marks.
6. **Relational Direction:** Direct position, scale, and proportion through relationships (order, alignment, relative size, weight) and describe color by hue and role. Measurements, coordinates, angles, counts, and color codes appear only when the brief supplies them.
7. **Economy:** State each decision once, in the slot where it belongs.
8. **Specificity:** Every stylistic term is resolved to a level that discriminates within its category. A category name never stands alone as a decision.