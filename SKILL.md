---
name: print-design-prompt-framework
description: Universal framework for converting a business brief into a single, semantically dense image-generation prompt for print design (banners, posters, flyers, backdrops, feather flags, menus, signage, packaging inserts, and similar physical media). Use this skill whenever the user provides a business brief, brand identity, print media size or constraints, or asks for a print design prompt, banner prompt, poster prompt, flyer prompt, or any image-generation prompt for a physical print piece, especially for local UMKM or street-level commercial businesses, even if they do not mention "framework" or "prompt engineering" explicitly.
---

# Print Design Prompt Engineering Framework

A principle-based system for turning a business brief into one precise image-generation prompt for a physical print piece. Its output answers a specific design problem; it is never a styled version of the business category.

**How to use:** Work through the five phases in Section 2 in order. At the start of each phase, read the matching reference file (Section 3). Foundational decisions are explored and locked before the decisions they govern. Output the prompt with the template in Section 4 and the rules in Section 5. A brief for several pieces shares Phases 1 and 2, so the pieces read as one family, and repeats Phases 3 to 5 for each medium.

---

## 1. Principles

1. **Understand before deciding.** The brief states a fraction of what determines good design. Build a working model of the business as its owner and a domain expert would hold it: how the business operates and earns; how the subject is made, delivered, met, and judged; what its advantage means in lived terms; how the customer actually decides and buys; how the category presents itself; what surrounds the piece where it hangs. Understanding is pursued until it yields design-relevant truths: findings that are true, distinctive within the field, perceptible, and relevant to the customer's decision. Every later decision draws on these, not on the brief's words.
2. **Problem before style.** Design starts from a design problem: the strain that appears where the brand's truth, the audience's state, the objective, the medium, and the placement meet. Style, imagery, color, and type are answers to that problem, never starting points. Context dimensions are read through their interactions, because the same attribute means different things to different audiences, placements, and distances. No dimension is interpreted alone.
3. **Insight before concept.** A distinctive idea comes from an insight: a non-obvious truth about this brand, for this reader, at this moment of encounter, that the piece can make felt. The concept is that insight, grounded in the brand's core (what it is to its customer, how it behaves, what territory it can credibly own), made visible as a specific world, device, structure, or behavior, concrete enough to settle later choices. A mood adjective or style label is not a concept.
4. **Associations are hypotheses.** The first association a name, product, category, or place offers is the baseline every competitor shares. Trace it to what it is actually about, keep it only if the brand itself earns it, and express it as this brand's own form of that idea. A fact merely adjacent to the brand constrains fit until the brand's identity connects it to the personality.
5. **Position within the field.** Every category has a grammar of presentation. Conventions that signal belonging (legitimacy, category, price level, trust) are kept and executed in the brand's own way; habits are questioned; clichés that make competitors indistinguishable are replaced. The design is placed in the possibility space on purpose: authentic to its category, its place, and the business as it truly operates, and distinct from its field by idea rather than by volume. Positioning qualities have no fixed visual form: each is read through this audience's codes, price level, and field baseline, so the same quality takes different treatments in different contexts. A design promises something, and the real encounter must be able to keep it.
6. **Range, and difference by role.** A piece is one-dimensional when every layer states the same thing the same way or receives the same treatment. A distinctive piece has one governing concept carried with range: a personality made of qualities held in productive tension, a payoff at each distance from which the piece is actually read, and layers whose attributes derive from their own roles. Coherence comes from a shared logic, not shared values. Tier sets an element's volume, never its voice, and restraint lowers intensity before it removes character.
7. **Approach follows the job.** Each visual layer receives a kind of making (captured, drawn, constructed, typographic, or a hybrid) according to the kind of truth it must deliver about the subject's reality, and an execution style according to the stance the piece takes toward its subject and viewer. Neither is a default and neither is set by category.
8. **Divided labor.** A piece carries several messages (what the brand is, what it offers, how it should feel, what to do). Each goes to the layer best placed to carry it, once. Layers that already carry a message free the others to carry what they alone can.
9. **Physical reality.** Aspect ratio, physical size, viewing distance, exposure time, substrate, and placement set what can be read and what looks native. Weight comes from scale, color, placement, isolation, and detail together, distributed by reader attention. Canvas area is the last dimension spent. Size is bounded below by the legibility floor and above by tier. Space is a designed layer: content is fitted to the density the medium's scale and viewing conditions support, never the reverse.
10. **Every finding becomes a consequence.** Analysis exists to change decisions. Each finding is converted into an implication (what it requires, permits, or rules out), each implication into the decisions it informs, and each decision into observable properties and directives. A directive with no chain back to a driver is a default, and a driver that changes no decision was not worth the analysis.

Every list, ratio, or reference in this skill is a tendency along a continuum; where a brief falls outside it, extend the principle. Hard-content fidelity, the output template, and the execution rules are fixed.

---

## 2. Master Decision Flow

Each phase takes the accumulated Decision Context, does ordered work, and produces entries that later phases depend on.

```
Phase 1 Understanding  →  Phase 2 Concept & Identity  →  Phase 3 Composition  →  Phase 4 Prompt Synthesis  →  Phase 5 Verification
```

* **Phase 1: Understanding & Design Problem** (`references/01_strategic_analysis_and_deconstruction.md`)
  * *Takes:* the brief.
  * *Does:* (1) Run each assessment in the register as question, finding, implication, decision informed, covering the stated brief and then the subject beyond it. (2) Tier content, set the primary focus, derive viewing conditions, legibility floors, and capacity, and set the reception balance and a provisional pictorial ceiling. (3) Weigh the drivers, read their interactions, name the tensions, and state the design problem, insight, and brand core. (4) Compile the implication map.
  * *Produces:* the subject model, tiers and focus, floors and capacity, problem, insight, brand core, and implication map, each finding tagged stated, inferred, or unknown.
* **Phase 2: Concept & Identity** (`references/02_visual_identity_and_style_synthesis.md`)
  * *Takes:* the implication map, brand core, insight, tiers, and viewing conditions.
  * *Does:* (1) Position the piece within the category field, derive the concept, personality, and mood, and allocate each message to its carrier. (2) Brief each visual layer from its job and the subject's truth, assign its kind of making and execution style, and confirm or revise the pictorial commitment. (3) Choose movement, form language, color logic, typographic voice, ornament, and the mark. (4) Check all of it as one system and lock it.
  * *Produces:* locked identity decisions: field position, concept, personality, and mood as visible behavior; message allocation; per-layer kind of making and stance; pictorial grade; movement and form language; palette roles, logic, hues, and proportions; display and supporting typographic voices; ornament; and mark architecture.
* **Phase 3: Composition** (`references/03_compositional_architecture_and_spatial_systems.md`)
  * *Takes:* the locked identity, tiers, focus, and capacity.
  * *Does:* (1) Confirm tiering and focus against the identity (a change returns through the conflict rule). (2) Set the density target and lock a composition strategy that carries the concept through structure. (3) Brief every element (job, tier, distance, relationships) and derive its zone, position, size, presence, and treatment. (4) Audit the weight, expression, and range the attributes actually produce.
  * *Produces:* a locked composition and, for every element, its zone, position, relative size, weight and color relationship, typographic treatment, rendering, and presence, each traceable.
* **Phase 4: Prompt Synthesis** (`references/04_prompt_synthesis_and_output_execution.md`)
  * *Takes:* every locked decision and attribute.
  * *Does:* Fill the template slot by slot from macro concept to zonal implementation, converting each decision into observable properties and relationships.
  * *Produces:* the prompt, with no attribute left to default.
* **Phase 5: Verification** (`references/04`, Section 5)
  * *Takes:* the prompt and the Decision Context.
  * *Does:* Run the checklist, trace each failure to the decision that caused it, revise there, and re-derive what it governs.
  * *Produces:* the final prompt.

### Decision Context & Decision Protocol

**Decision Context:** Compiled in Phase 1, extended in every later phase, consulted by every decision. It is also a ledger: each committed decision is entered with the drivers behind it and the information status of those drivers, each new decision is checked against all entries, and revising an entry reopens everything derived from it. It holds: business and positioning; objective, reader task, and intended response; audience and moment of encounter; medium and physical scale; placement and register; the subject model (design-relevant truths: operations, reality, lived USP, customer decision and buying behavior, category field, surroundings); content load, tiers, and primary focus; parameter weights, interactions, and tensions; the design problem, insight, and brand core; the implication map linking each weighted driver to the decisions it informs; then, as decisions are committed, field position, concept, personality, mood, approach per layer, and style direction.

**Foundational decisions** govern all others: primary focus, message allocation, concept and personality, mood, kind of making and execution style per layer, pictorial commitment, movement, palette architecture, typographic voice, mark architecture, and composition strategy (including its density target). Each follows these steps, with divergence widest for the decisions that govern the most:
1. **Frame:** State the job of the decision and which drivers (weighted findings, interactions, and tensions in the implication map) bear on it, and what each implies for it.
2. **Diverge:** Map the possibility space for the decision (the axes along which answers can genuinely vary, including the variables on which this business differs from its field), then generate candidates that sit apart on those axes and differ in underlying idea, each built from a different dominant context dimension or interaction and stated as concrete visible behavior so it can be judged. Include three depths: the apparent (what proximity, category grammar, or the prototype suggests), the underlying (what that is about), and the personal (what this brand's character would choose). The first coherent candidate is usually the nearest one, so the search continues past it. The apparent is the baseline to beat and is chosen only when it is the strongest fit.
3. **Test:**
   * *Traceability:* it follows from named drivers and their implications.
   * *Tailoring:* would it change if the business, audience, medium, or placement changed? If not, it is generic.
   * *Earned connection:* every context fact it draws on is connected to the brand's own identity, claim, or audience, not merely nearby.
   * *Resolution:* it resolves a tension of this brief.
   * *Range:* it carries something other layers do not, and it holds a tension rather than one note.
   * *Belonging and distinction:* it keeps the field's signals of belonging so it looks native in its category and placement, and differs from its neighbors by idea, not by volume.
   * *Function:* it is legible at the medium's distances and settles downstream choices.
   * *Credibility:* the signals it sends match what the business is and delivers, at the scale and means it operates with, so the customer's real encounter confirms them.
   * *Coherence:* it agrees with the foundational decisions already made.
4. **Specify:** Resolve it to a level that discriminates (`02`, Section 5).
5. **Lock:** Check the foundational decisions against each other as one system. Lock them in two stages: identity decisions at the end of Phase 2, composition strategy at the start of Phase 3, checked against the identity. No derived decision precedes the lock that governs it.

**Derived decisions** are every attribute of every element and layer. Each is derived from the element's tier (when it is read), its purpose (what it does for the reader), its presence (whether and how visibly it exists), the physical conditions under which it is seen, and the foundational decisions it serves. Test each for necessity, proportionate weight as its attributes actually produce it, voice, legibility at the floor, and consistency with siblings. Commit each as an explicit directive.

**Traceability chain:** Every directive traces from driver to implication to foundational decision to derived attribute to directive. What governs more is explored more widely and locked first; what is governed is derived, not reinvented. A directive with no chain is a default, and a weighted driver that reaches no decision signals analysis left unfinished.

**Conflict rule:** When a derived decision cannot satisfy its governing decisions without breaking hierarchy or legibility, trace the conflict to its cause in the ledger, revise the foundational decision, and re-derive everything entered after it that depends on it. Never patch downstream.

**Working discipline:** Deliberation is internal. Each foundational decision is explored separately before any prompt text is drafted, and only committed directives appear in the prompt.

---

## 3. Reference Module Index

| File Path | Functional Domain |
| :--- | :--- |
| `references/01_strategic_analysis_and_deconstruction.md` | Assessment register and method, brief deconstruction, subject model (operations, reality, lived USP, customer decision, category field), interactions, tensions, design problem, insight, brand core, implication map, viewing conditions and capacity, content filtering, attention tiering, pictorial commitment, local market context. |
| `references/02_visual_identity_and_style_synthesis.md` | Concept derivation, field position, personality, mood, range, message allocation, layer briefs, kind of making and execution style, movement, color, typographic voice, specificity, ornament, mark. |
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
[Zonal structure derived from the canvas's dominant axis, visibility, and content groups. The density target and negative-space allocation (outer margins, separations between groups, regions left deliberately empty). The display and supporting typographic voices per hierarchy level, resolved to structural traits. Specific placement and relative scale, expressed as relationships, for the focal anchor, any pictorial subject, tagline, information blocks, and action badges. Every hard-content string appears verbatim, in quotation marks, at its placed position].

VISUAL ELEMENTS & RENDERING TECHNIQUE:
[Each pictorial subject admitted (subject, complexity, role, relative scale) or a statement that none is used; for each visual layer, its kind of making, its execution style resolved to observable properties (vantage, light, depth, subject state, and grade for captured work; lineage, medium, line, and simplification for drawn work; geometric logic and rhythm for constructed work), and its intensity; which layer leads and what binds the layers when they differ].

BACKGROUND, BORDERS & FINISH:
[Ground character and surface treatment, borders, decorative motifs, and edge treatments, each carrying the concept's character at the visibility its purpose needs, or a statement that a layer is deliberately plain].

TECHNICAL & EXECUTION CONSTRAINTS:
[Rendering rules suited to the medium and style: layout structure, contrast behavior, photographic or non-photographic stance, execution quality, and legibility at the viewing distances involved].
```

---

## 5. Execution Rules & Prompt Directives

1. **Output Raw Prompt Only:** Output only the single prompt block unless asked otherwise, except when information that cannot be inferred and would change a foundational decision or the hard content is missing; ask for it concisely first. The Decision Context, protocol work, and audits stay internal and are completed before the prompt is written.
2. **Never Invent Contents:** Enforce all hard content (copy, numbers, addresses, menu items, prices, and any other required element) exactly as supplied. Never omit required text or add items.
3. **No Meta-Commentary:** Every phrase is an objective, observable visual directive. Reasoning, justification, intent, evaluative language, and framework terminology never appear in the prompt.
4. **Preserve Generative Freedom:** Specify structure, relationships, and aesthetic parameters. Leave fine line rendering, lighting falloff, and organic texture to the model.
5. **English Output:** Write the entire prompt in English whatever language the brief uses. Only literal hard content is reproduced verbatim in its original language, in quotation marks.
6. **Relational Direction:** Direct position, scale, and proportion through relationships (order, alignment, relative size, weight) and describe color by hue and role. Measurements, coordinates, angles, counts, and color codes appear only when the brief supplies them (the aspect ratio is derived from supplied dimensions).
7. **Economy:** State each decision once, in the slot where it belongs.
8. **Specificity:** Every stylistic term is resolved to a level that discriminates within its category. A category name never stands alone as a decision.