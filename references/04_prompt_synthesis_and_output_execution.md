# Prompt Synthesis & Output Execution

*Used in Phases 4 and 5 of `SKILL.md`. Phase 4 carries every decision into the prompt, and Phase 5 audits them.*

Image-generation models respond to precise structural, artistic, and spatial specification, not to explanations or subjective adjectives. Phase 4 translates each decision into what is physically visible.

---

## 1. Semantic Density & Precision

```
INTENT  →  name the tradition, technique, stance, or structure that embodies it
        →  state observable properties (form, line, light, color, surface, scale)
        →  state spatial relationships (position, proportion, hierarchy, grouping)
```

* **Decisions, not judgments:** Every statement names what something is, where it sits, and how it relates to its neighbors. A statement that only assesses quality gives the model nothing to execute.
* **Carry the concept visibly:** The concept and its range reach the model as visible directives in the slots where they act: the form and behavior of the mark, type, color relationships, composition structure, imagery stance, and ornament. The concept is never named as an abstraction and left for the model to interpret.
* **Carry stance, not only category:** For each pictorial layer, direct kind of making and execution style as observable properties (`02`, Section 2.3). Saying only "photograph" or "illustration" leaves the decision to the model.
* **Discipline terminology:** Draw on professional design, typography, art-historical, and print-production terminology, and choose the term whose scope matches the decision exactly. Compose wording fresh for each brief. A modifier stays only if it separates this choice from its alternatives.
* **Space is directed:** Image models fill unspecified space, so negative space is stated as part of the composition: wide outer margins, separations between groups, regions left deliberately empty, and the modest fraction of the canvas the content occupies, matched to the medium's scale and viewing distances.
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
• Mark architecture, scale & position           • Stroke rendering nuance
• Color roles & proportions
• Movement, stance & style traits
```

---

## 4. Output Construction

Assemble the decisions into the template in `SKILL.md`, Section 4, leaving no slot filled by habit.
1. **Header:** aspect ratio, medium, full brand name, concept as direct visual direction, movement resolved to traits, palette roles, hues, and proportions, form language and tone.
2. **Mark:** geometry, role and scale, embodiment of the concept, typography, descriptor, isolation.
3. **Composition:** the density target and negative-space allocation; zones by axis, visibility, and content groups; placement by tier and balance, with relative sizes calibrated to physical scale and viewing distance; every hard-content string verbatim, in quotation marks, at its placed position.
4. **Visual elements:** each pictorial subject (or its deliberate absence); for each layer, kind of making, execution style, intensity, leading layer, and binding properties.
5. **Background, borders, finish:** substrate, borders or deliberate absence, accents, and pattern density at the visibility their purpose needs.
6. **Technical constraints:** layout and rendering rules suited to the medium and style, legibility intent per level, and strict hard-content fidelity.

---

## 5. Verification Checklist

Run internally and revise until every item passes. None of it appears in the output. Trace each failure to the decision that caused it, revise there, and re-derive what it governs.

**Content & Language**
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

**Approach**
* [ ] Is each visual layer's kind of making matched to the truth it must deliver, with hybrids justified by function, led by one layer, and bound by shared properties?
* [ ] Was each layer briefed from its job and the subject's truth, and is each execution style a stance resolved to observable properties for this brief, rather than a category name or a default treatment?

**Hierarchy & Layout**
* [ ] Is the primary focus determined from the objective, reader task, engagement mode, content structure, recognition supplied, and movement, with the mark's prominence set by its tier?
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