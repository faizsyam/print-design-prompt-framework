# Prompt Synthesis & Output Execution

*Used in Phases 4 and 5 of `SKILL.md`. Phase 4 carries every Decision Protocol decision (`SKILL.md`, Section 2) into the prompt; Phase 5 audits them.*

This reference guide establishes the principles, semantic translation mechanics, negative constraints, and output execution directives for converting synthesized strategic design decisions into a single, highly dense, professional image-generation prompt.

---

## 1. Semantic Density & Precision Principles

Image-generation vision models respond to precise structural, artistic, and spatial specification rather than conversational explanations or subjective buzzwords. Translate each strategic design decision into what is physically visible on the page:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SEMANTIC TRANSLATION PIPELINE                        │
└─────────────────────────────────────────────────────────────────────────┘

INTENT  (what the design must feel or do)
   │  name the specific tradition, technique, or structure that embodies it
   ▼
OBSERVABLE PROPERTIES  (form, line, color, surface, scale)
   │  state them as what is physically visible
   ▼
SPATIAL RELATIONSHIPS  (position, proportion, hierarchy, grouping)
```

### 1. Precision Principles
* **Specify decisions, not judgments:** Every statement names what something is, where it sits, and how it relates to its neighbors. A statement that only assesses quality gives the model nothing to execute.
* **Terminology from the discipline:** Draw on the full breadth of professional design, typography, art-historical, and print-production knowledge, and choose the term that most exactly names the intended decision. Compose the wording fresh for each brief; never reuse stock phrasing across briefs.
* **Specificity resolved:** Every stylistic term is taken to the level at which it discriminates (`02`, Section 2.2). A category name alone is a non-decision; a term fits when other styles in its category could not answer to it.
* **Term fit and discriminating modifiers:** Choose the term whose scope matches the decision exactly, neither broader nor narrower, and never a near-synonym that shifts the meaning. A modifier stays only if it separates this choice from its alternatives; modifiers that would fit any style are cut.
* **Hybrid direction:** When layers differ in mode, direct which layer leads, the specific technique of each, and the shared properties that bind them, so the model composes one piece instead of assembling parts.
* **Cover every layer:** Layout structure, typography, color roles, and rendering technique each carry a concrete decision in the prompt.
* **Directive only:** Every phrase is a visual directive. The prompt carries decisions, never the rationale, justification, or intent behind them.
* **English with literal contents:** The prompt is written in English. Only literal hard content (brand name, copy, prices, contact details, addresses, other supplied strings) stays verbatim in its original language, in quotation marks.
* **Relationships over numbers:** Position, scale, and proportion are directed as relationships (order, alignment, relative size, relative dominance), and color by hue and role. Measurements, coordinates, angles, counts, and color codes appear only when the brief supplies them.
* **Economy:** State each decision once, in the slot where it belongs, and never restate hierarchy, rationale, or the same constraint across slots.
* **No internal vocabulary:** Framework terms (tier names, decision context, protocol) never appear in the prompt.

---

## 2. Elimination of Generic AI Aesthetics & Fluff

To prevent the vision model from reverting to generic "AI stock design" tropes, strictly purge conversational filler, vague language, and redundant descriptors.

### 1. Evaluative & Vague Language
Exclude words that assess quality, promise an effect, or invoke popularity without describing form. Replace each with the visual mechanic it was standing in for. A rendering stance (photographic or otherwise) is stated as a chosen technique, never as a quality boost.

### 2. Genericness Test & Default Overrides
Genericness enters wherever a decision is left unspecified: where the prompt is silent, the model supplies its most common default for that element, so silence is itself a decision. For each element, make the decision that determines its distinctiveness: how it expresses the theme and personality, how it is anchored in the structure, how related information is grouped and separated (an enclosure is a decision, and so is its absence), the representation mode and expressive character of each visual layer, the typographic and decorative voice, what the background is and what it does for legibility, and which surface effects exist and why.
* **Test:** If a sentence could be placed unchanged into a prompt for a different business, it is generic. Rewrite it with this brief's specifics. Apply the same test to decisions before they are worded: a decision that would not change if the business, audience, medium, or placement changed is generic.
* **Prototype test:** Name the choice a typical prompt for this kind of business and medium would arrive at. If the prompt's choice is the same, it must be the strongest fit for this brief; otherwise depart from it.
* **Exclusions:** State an exclusion only where a likely default would damage the brief.

---

## 3. Boundary Control & Generative Freedom Balance

The prompt framework must exercise **strategic boundary control**: it strictly governs visual structure, hierarchy, composition, brand architecture, and color logic, while leaving fine line execution, micro-rendering, and organic textures to the model's creative strength. Exact measurements, coordinates, angles, counts, and color codes belong to the generative side unless the brief supplies them: models cannot honor them reliably, and they crowd out the decisions that matter.

```
┌───────────────────────────────────────────────────────────────────────────┐
│                    THE BOUNDARY CONTROL BALANCE                           │
└───────────────────────────────────────────────────────────────────────────┘

MUST BE EXPLICITLY DIRECTED                 LEFT TO GENERATIVE EXECUTION
┌──────────────────────────────────────┐   ┌────────────────────────────────┐
│ • Aspect ratio & media format        │   │ • Exact micro-texture grain    │
│ • Zoning, hierarchy & reading flow   │   │ • Fine lighting falloff & shade│
│ • Exact hard content & copy strings  │   │ • Subtle organic linework      │
│ • Logo architecture, scale & position│   │   variations                   │
│ • Color role hierarchy & proportions │   │ • Artistic stroke rendering    │
│ • Visual style & design movement     │   │   nuances                      │
└──────────────────────────────────────┘   └────────────────────────────────┘
```

---

## 4. Final Output Construction Pipeline

When generating the final prompt output, assemble the design decisions made through the Decision Protocol (`SKILL.md`, Section 2) according to the strict universal template, leaving no slot filled by habit:

### Execution Protocol Steps

1. **Header Block Assembly:** State aspect ratio, physical media type, full brand name, the brand theme and personality as a direct visual directive, design movement resolved to its distinguishing traits, and the palette's roles, hues, and proportions.
2. **Primary Logo Mark & Branding:** Detail the emblem/wordmark geometry, its role and scale in the hierarchy, how it embodies the theme and personality, typography style, descriptor, and structural isolation mechanics.
3. **Composition & Layout Zoning:** Map the physical canvas into distinct spatial zones derived from its dominant axis, visibility, and content groups, aligned to the target reading distance. Place every element, including the tagline, by attention tier and balance, with relative sizes calibrated to the physical scale, and include every hard-content string verbatim, in quotation marks, at its placed position.
4. **Visual Elements & Rendering Technique:** Detail each pictorial subject admitted (subject, complexity, style, role, scale), or state that none is used, plus the representation mode, specific technique, and expressive character of each visual layer (with the leading layer and the properties that bind them when they differ in mode) and line-weight parameters.
5. **Background, Borders & Finish:** Define substrate textures, borders or their deliberate absence, decorative accents, or background pattern density, each at the visibility its purpose needs.
6. **Technical & Execution Constraints:** Enforce the layout and rendering rules suited to the medium and style, the legibility intent per hierarchy level, and strict hard-content fidelity.

---

## 5. Verification Checklist

Before emitting the final prompt, run this audit internally and revise until every item passes. None of it appears in the output. A failed item is traced to the decision that caused it, revised there, and everything that decision governs is re-derived; patching downstream is not a fix.

**Content & Language**
* [ ] **Hard Copy Fidelity:** Is every hard-content string from the brief included verbatim, in quotation marks, with nothing added, invented, or reworded?
* [ ] **Language & Directness:** Is the entire prompt in English except literal hard content, and is every phrase, including the theme line, a direct visual directive with no rationale, free of framework terminology, measurements, coordinates, angles, counts, and color codes, and stating each decision once?

**Identity & Context**
* [ ] **Theme Coherence:** Is one specific theme and personality stated, embodied in the logo mark as its canonical statement, and traceable through the few layers that carry it and consistent in the rest, without altering hard content?
* [ ] **Division of Labor:** Does each message (what the brand is, what it offers, how it feels, what to do) have one best-placed carrier, with theme, mark, ornament, and palette carrying the identity the content and imagery do not already carry, and no layer echoing another's message?
* [ ] **Tailoring:** Would each foundational decision (theme, mood, movement, representation modes, palette, typographic voice, composition) change if the business, audience, medium, or placement changed, does it resolve a tension of this brief, and does it draw on every context dimension that bears on it rather than the most salient or literal input?
* [ ] **Contextual Fit:** Does the aesthetic register (finish, formality, realism, production character) belong natively in the placement context, with positioning expressed through signals that setting can carry and distinction coming from a differentiator within its range?

**Hierarchy & Layout**
* [ ] **Hierarchy Derivation:** Is the primary focus determined from the objective, reader's task, engagement mode, content structure, recognition already supplied, and style direction, with the logo mark's prominence (like every element's) set by its tier rather than assumed?
* [ ] **Attention Balance:** Does visual weight follow the attention tiers across every dimension (scale, color relationship, placement, isolation), with ornament and lower-tier elements recessive in color and position rather than sharing the focal anchor's, and weight distributed across the canvas rather than clustered? Does the weight each element's attributes actually produce (area, contrast, chroma, detail, position), including grounds, bands, and borders, match its tier?
* [ ] **Placement Logic:** Is every placement and group form (including the tagline and contact information) derived from function, relationship, and counterweight, rather than repeated from a template?
* [ ] **Scale Calibration:** Is each element sized within the band set by its legibility floor and its tier, with surplus canvas given to Tier 1 scale and negative space rather than to enlarged secondary content, and with Tier 3 information kept legible but unboosted?
* [ ] **Pictorial Decision:** Is the pictorial subject justified by need at the lowest grade of presence that does its job (or deliberately absent), with its scale set by sufficiency within the area left after content at its floor, and its subject, complexity, style, role, and placement derived from the reception balance, content load, theme, tier, and placement context rather than assumed?

**Decisions & Distinctiveness**
* [ ] **Decision Traceability:** Can every element's size, position, grouping, color, and treatment be traced to its role and to the Decision Context parameters that bear on it? Is each grouping or separation device, representation mode, expressive character, and typographic and decorative voice a specific choice for this brief (including no boundary where none is needed), with none left to default or taken from its category, and do the decisions together read as one coherent, balanced piece?
* [ ] **Derivation Direction:** Were the foundational decisions locked and checked against each other before any derived decision was made, and does every derived decision trace to the foundational decisions it serves and to its element's tier and purpose, with presence and visibility set at the lowest degree at which the element still does its job?
* [ ] **Specificity:** Does every stylistic term, including typography, rendering, capture or drawing treatment, and palette hues, discriminate within its category, with no category name standing alone as a decision?
* [ ] **Modality Fit:** Is each visual layer's representation mode matched to the job it does, with any hybrid justified by function, led by one layer, and bound by shared properties?
* [ ] **Restraint:** Does every element and device earn its place (what is lost without it), with ornament limited to what the hierarchy, objective, and theme need, and with nothing overlapping text?
* [ ] **Open Choice:** Were the design movement, mark architecture, and layout derived from the brief's principles, rather than from the first conventional fit or a listed category?
* [ ] **Distinctiveness:** Would any sentence in the prompt survive unchanged in a prompt for a different business, and does any major choice (theme, style, palette, mark architecture, layout) match the prototype without being the strongest fit? If so, rewrite it.
* [ ] **Semantic Density:** Are all visual instructions expressed in professional design, art history, and print production terminology?
* [ ] **Template Integrity:** Does the output strictly adhere to the universal template structure defined in `SKILL.md`?
