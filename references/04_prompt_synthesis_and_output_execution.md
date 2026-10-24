# Prompt Synthesis & Output Execution

*Used in Phases 4 and 5 of `SKILL.md`. Phase 4 carries every decision into the prompt, and Phase 5 audits them. `07` (style bank, part 3) is read in full in Phase 4 and supplies the anatomy of a direction with its template slots, the phrasing rules, the reliability handling for each element, and the specificity audit. Where `07` and this file differ, this file and `SKILL.md`, Sections 4 and 5, govern.*

Image-generation models respond to precise structural, artistic, and spatial specification, not to explanations or subjective adjectives, and they draw or obey whatever the prompt contains. Phase 4 translates each decision into what is visible inside the canvas and stops there.

---

## 1. Semantic Density & Precision

```
INTENT  →  name the tradition, technique, stance, or structure that embodies it
        →  state observable properties (form, line, light, color, surface, scale)
        →  state spatial relationships (position, proportion, hierarchy, grouping)
```

* **Frame boundary:** The prompt holds only what can be seen in the image and how the image is rendered (`SKILL.md`, Principle 12). Placement, mounting, surroundings, audience, viewing distance and duration, purpose, production method, and substrate drive the decisions and are then converted into visible consequences (a ratio, a contrast, a margin, a ground character) with the cause left out. The medium appears only as the format name in the opening sentence. A sentence that narrates the piece as an object, an event, or something viewed is situation language even when its words are visual, and is rewritten as depiction or deleted. Before finalizing, read every sentence and ask what in the image it changes; a sentence that changes nothing is removed.
* **Decisions, not judgments:** Every statement names what something is, where it sits, and how it relates to its neighbors. A statement that only assesses quality gives the model nothing to execute.
* **Carry the concept visibly:** The concept and its range reach the model as visible directives in the slots where they act: the form and behavior of the mark, type, color relationships, composition structure, imagery stance, and ornament. The concept is never named as an abstraction and left for the model to interpret.
* **Carry stance, not only category:** For each pictorial layer, direct kind of making and execution style as observable properties (`02`, Section 2.3). Saying only "photograph" or "illustration" leaves the decision to the model.
* **Carry the register for each image:** Every image takes its own entry, its role expressed as visible dial settings in the signature's vocabulary (`07`, Section 7; `08`, Section 6), bound to the other images by the properties they share. Role words, purposes, and situations stay out of the entry.
* **Bank vocabulary, fully resolved:** A named lineage, technique, or material enters the prompt with its distinguishing traits (`07`, Section 2, rules 1 to 3), never as a bare name or a bare adjective. Entries are used for their traits and never copied wholesale, and no living artist, brand, or character is named as a style (`05`, Section 3).
* **Discipline terminology:** Draw on professional design, typography, art-historical, and craft terminology (print-production terms only for the visible character they produce, never as manufacturing facts), and choose the term whose scope matches the decision exactly. Compose wording fresh for each brief. A modifier stays only if it separates this choice from its alternatives.
* **Space is directed:** Image models fill unspecified space, so negative space is stated as part of the composition: wide outer margins, separations between groups, regions left deliberately empty, and the modest fraction of the canvas the content occupies. The medium's scale and viewing distances determine these values and are not themselves stated.
* **Counter default gravity:** Where an unspecified property would let the model fall back to glossy rendering, filled canvas, centered symmetry, generic type, or stock lighting, specify the considered property in its place (`07`, Section 3).
* **Hybrid direction:** State which layer leads, the technique of each, and the shared properties that bind them.
* **Cover every layer:** Layout, typography, color roles, imagery, ornament, and ground each carry a concrete decision.
* **Directive form:** The rules in `SKILL.md`, Section 5 apply to every phrase: directives only, English with literal hard content in quotation marks, relationships over numbers, each decision stated once, no framework vocabulary.

---

## 2. Genericness Control

Where the prompt is silent, the model supplies its most common default, so silence is a decision. For every element, decide what determines its distinctiveness: how it expresses the concept, how it is anchored in the structure, how related information is grouped or left ungrouped, the kind of making and stance of each visual layer, the typographic and decorative voice, what the ground is and does, and which surface effects exist.
* **Test:** If a sentence could move unchanged into a prompt for a different business, it is generic; rewrite it with this brief's specifics.
* **Prototype test:** Name the choice a typical prompt for this business and medium would reach, the choice the category's conventions suggest, and the choice proximity or literal association suggests. If the prompt's choice is the same, it must be the strongest fit for this brief.
* **Evaluative language:** Replace words that assess quality, promise an effect, or invoke popularity with the visual mechanic they stood for. A rendering stance is stated as a chosen technique, never as a quality boost.
* **Exclusions:** State an exclusion only where a likely default would damage the brief.

---

## 3. Boundary Control

Strictly direct structure, hierarchy, composition, brand architecture, color logic, movement, and imagery stance. Leave fine line execution, micro-texture, lighting falloff, and organic variation to the model.

```
MUST BE EXPLICITLY DIRECTED                     LEFT TO GENERATIVE EXECUTION
• Aspect ratio & media format                   • Micro-texture and grain
• Zoning, hierarchy & reading flow              • Fine lighting falloff and shading
• Density, margins & negative space
• Exact hard content strings                    • Subtle organic linework variation
• Mark construction, role, scale & position          • Stroke rendering nuance
• Color roles & proportions
• Movement, stance & style traits
```

---

## 4. Output Construction

Assemble the decisions into the template in `SKILL.md`, Section 4, leaving no slot filled by habit.
1. **Header:** an opening sentence of aspect ratio, format name, and full brand name only, then the concept as direct visual direction, movement resolved to traits, palette roles, hues, and proportions, form language and tone.
2. **Mark:** one entry (`07`, Section 8): type and construction, silhouette, lettering moves, symbol, boundary or open contour, color logic, internal levels and descriptor, variant, relative scale and clear space, separation from the ground, with the brand name in quotation marks, once.
3. **Composition:** the density target and negative-space allocation; the display and supporting typographic voices per hierarchy level, resolved to structural traits; zones by axis and content group; position by tier and balance, with sizes expressed as ratios between levels (the physical scale and viewing distance that set them are not stated); every hard-content string verbatim, in quotation marks, at its placed position.
4. **Visual elements:** each image by entry (or the deliberate absence of images), with subject, complexity, kind of making, signature traits, register, edge and crop behavior, the leading image or layer, and the properties that bind the images into one style identity. Imagery that forms or sits within the ground is directed in item 5 at its register.
5. **Background, borders, finish:** ground character and visible surface treatment (including any image or texture field that forms the ground, with its calm regions by position and value band), borders or deliberate absence, accents, and pattern density at their stated visibility.
6. **Technical constraints:** layout and rendering rules for the image, contrast behavior, rendering stance, execution quality, legibility expressed as relative scale and contrast between levels, and strict hard-content fidelity.

---

## 5. Verification Checklist

Run internally and revise until every item passes. None of it appears in the output. Trace each failure to the decision that caused it, revise there, and re-derive what it governs.

**Outcome & Information**
* [ ] Walking the encounter at each viewing distance and exposure, does the reader register Tier 1, grasp the offer, and take the intended action?
* [ ] Was information that could not be inferred obtained, or handled by a choice that holds under every plausible reading, with no invented facts or hard content, and assumptions kept out of the prompt's hard content?

**Content & Language**
* [ ] Does every phrase name something visible inside the canvas or a property of how it is rendered, with no placement, mounting, surroundings, audience, viewing distance, purpose, production method, or substrate stated, and does the opening sentence hold only the aspect ratio, the format name, and the brand name?
* [ ] Is every hard-content string verbatim, in quotation marks, with nothing added, dropped, or reworded?
* [ ] Does the prompt obey every rule in `SKILL.md`, Section 5 (English except hard content, directives only, no framework terms, relational direction, each decision stated once)?

**Understanding & Concept**
* [ ] Does the design draw on design-relevant truths beyond the brief (the subject's reality, the USP as lived difference, the real customer decision), and does the brand core show in how forms, type, and color behave?
* [ ] Is the style direction composed of precisely named traits, each grounded in the subject or brand core, rather than a broad style label?
* [ ] Is each category convention deliberately kept as a signal of belonging, questioned, or replaced, so the piece reads as native to its category and distinct from its field by idea?
* [ ] Does the design answer a stated design problem and insight, and is the concept one specific idea that is visible in the directives rather than named as an abstraction?
* [ ] Does every context fact the identity draws on connect to the brand's own identity, claim, or audience, and was the apparent choice weighed against the underlying and personal alternatives?
* [ ] Would each foundational decision change if the business, audience, medium, or placement changed, and does it resolve a tension of this brief?
* [ ] Does each message have one best-placed carrier, with the mark, type, color, composition, and ornament carrying what the content and imagery do not already carry?
* [ ] Does the piece have range: a personality with productive tension, a payoff at each distance from which it is read, and layers that carry different things rather than one note repeated?
* [ ] Does the aesthetic register belong natively in the placement and its surroundings, with distinction coming from an idea within its range?
* [ ] Does each positioning quality take the form this audience, price level, place, and field call for, and do the signals match what the business actually is and delivers (model, premises, means, customer expectations), so the real encounter confirms the promise?

**Brand Mark**
* [ ] Is the mark a distinct unit with its own construction (silhouette, structure, built lettering, symbol, boundary or implied block), passing the blur, headline, and swap tests, rather than the name set in the display voice?
* [ ] Were open, bounded, and symbol- or structure-led constructions evaluated as candidates that differ in idea, with the choice and rejections traced to drivers, and does the chosen construction qualify (a specific boundary and built lettering if enclosed; sufficient silhouette, structure, lettering, or symbol if open)?
* [ ] Does the mark's lettering differ from the display voice in at least one structural property, and does the mark carry the concept as visible form?
* [ ] Does the mark's role (dominant identity, supporting element, or discreet signature) follow the objective and tiers, with scale in a band between its floor and its tier, the variant fitting the role and ground, and weight that matches its tier in the weight audit?
* [ ] Is identity constant across variants and pieces (structure, silhouette family, lettering character, symbol, color logic), with only prominence, scale, variant, and placement adapting?
* [ ] Does the mark keep separation on its ground, avoid overlap, and appear as one entry with the brand name stated once and no role, purpose, or situation language?

**Imagery & Roles**
* [ ] Does each image in the ledger trace to a driver and a job another layer would do worse, with a grade at the lowest level that does the job, and does the image economy fit the reception balance with no image outweighing a higher tier?
* [ ] Does each image have its own role profile (function, grade, reading regime, relations, truth demand), and do the differences between image treatments trace exactly to differences in those profiles?
* [ ] Is there one style identity, with every image's register keeping the primary anchors (anchor test) and carrying identity by transfer where a dial is held low, never by a generic fade, blur, or opacity reduction?
* [ ] Where an image hosts type, is the host region designed in the image (position, value band, detail, edge) with focal content outside it?
* [ ] Do series images share every framing property and differ only by subject, and do images differing in kind of making share binding properties?
* [ ] Does every image depict only supplied content, and does the prompt express each role through visible settings, with no role word, purpose, or situation?

**Approach**
* [ ] Is each visual layer's kind of making matched to the truth it must deliver, with hybrids justified by function, led by one layer, and bound by shared properties?
* [ ] Was each layer briefed from its job and the subject's truth, and is each execution style a stance resolved to observable properties for this brief, rather than a category name or a default treatment?

**Hierarchy & Layout**
* [ ] Is the primary focus determined from the objective, reader task, engagement mode, content structure, recognition supplied, and movement, with the mark's role set by its tier (`09`, Section 5.1)?
* [ ] Does the weight each element actually produces (area, contrast, chroma, detail, position, including grounds, bands, and borders) match its tier, with weight distributed across the canvas?
* [ ] Do density, margins, group separations, and empty regions match the medium's capacity and viewing distances, are they directed explicitly, and is any group cramped despite legible content?
* [ ] Is every placement and group form derived from function, relationship, and counterweight, and is each element sized within its band, with Tier 3 legible but unboosted?
* [ ] Is the pictorial subject at the lowest grade that does its job (or deliberately absent), sized by sufficiency?

**Decisions & Distinctiveness**
* [ ] Does every weighted driver appear as a visible consequence in the prompt, and does every major directive trace through a decision to a driver?
* [ ] Were the foundational decisions explored across different ideas, locked in their two stages, and checked against each other before any derived decision was made, and does every derived decision trace to them?
* [ ] Does every stylistic term, including typography, rendering, imagery, and hues, discriminate within its category and use professional terminology?
* [ ] Is the personality perceptible across layers (ground, type, containers, edges, secondary elements), with every plain layer a deliberate choice and ornament calibrated down in steps rather than dropped?
* [ ] Does every element and device earn its place, with attributes that differ where roles differ, and nothing overlapping text?
* [ ] Would any sentence survive unchanged in a prompt for a different business, and does any major choice match the prototype without being the strongest fit? If so, rewrite it.
* [ ] Does the output follow the template in `SKILL.md`, Section 4?

**Style Bank**
* [ ] Is the governing lineage one dominant tradition resolved to its distinguishing traits, with at most two secondary influences each limited to one property, sharing a compatible logic, and carrying a brand-specific inflection (`05`, Section 2)?
* [ ] Was each chosen term kept because a driver called for it and it changes something visible, and was the choice widened across at least three families rather than taken from the nearest?
* [ ] Are heritage, regional, sacred, state, and regulated elements handled by `05`, Section 3 (structure and idea rather than pasted motif, no scripture as decoration, no flag or emblem, trust marks reserved or reproduced as supplied)?
* [ ] Is every element directed according to its generator reliability (`07`, Section 5), with required content still stated verbatim and nothing the generator cannot render (QR code, regulated mark, supplied logo, non-Latin script) recreated?
* [ ] Does the piece survive its viewing distance and print process (Facet M), and does each stylistic term pass the specificity audit (`07`, Section 6)?
* [ ] Is the prompt free of bank apparatus (facet letters, entry codes, column names) and of living artists, brands, and characters named as styles (`SKILL.md`, Section 5, rule 9)?