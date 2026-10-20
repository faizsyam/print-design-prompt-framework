# Prompt Synthesis & Output Execution

*Used in Phases 4 and 5 of `SKILL.md`.*

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
SPATIAL RELATIONSHIPS  (position, proportion, hierarchy, containment)
```

### 1. Precision Principles
* **Specify decisions, not judgments:** Every statement names what something is, where it sits, and how it relates to its neighbors. A statement that only assesses quality gives the model nothing to execute.
* **Terminology from the discipline:** Draw on the full breadth of professional design, typography, art-historical, and print-production knowledge, and choose the term that most exactly names the intended decision. Compose the wording fresh for each brief; never reuse stock phrasing across briefs.
* **Cover every layer:** Layout structure, typography, color roles, and rendering technique each carry a concrete decision in the prompt.
* **Directive only:** Every phrase is a visual directive. The prompt carries decisions, never the rationale, justification, or intent behind them.
* **English with literal contents:** The prompt is written in English. Only literal hard content (brand name, copy, prices, contact details, addresses, other supplied strings) stays verbatim in its original language, in quotation marks.

---

## 2. Elimination of Generic AI Aesthetics & Fluff

To prevent the vision model from reverting to generic "AI stock design" tropes, strictly purge conversational filler, vague language, and redundant descriptors.

### 1. Evaluative & Vague Language
Exclude words that assess quality, promise an effect, or invoke popularity without describing form. Replace each with the visual mechanic it was standing in for. A rendering stance (photographic or otherwise) is stated as a chosen technique, never as a quality boost.

### 2. Genericness Test & Default Overrides
Genericness enters wherever a decision is left unspecified, because the model fills gaps with its most common defaults. Where the prompt is silent, the model supplies its most common default for that element, so silence is itself a decision. For each element, make the decision that determines its distinctiveness: how it expresses the theme and personality, how it is anchored in the structure, how related information is grouped and separated (an enclosure is a decision, and so is its absence), the representation mode and expressive character of each visual layer, the typographic and decorative voice, what the background is and what it does for legibility, and which surface effects exist and why.
* **Test:** If a sentence could be placed unchanged into a prompt for a different business, it is generic. Rewrite it with this brief's specifics.
* **Exclusions:** State an exclusion only where a likely default would damage the brief.

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
│ • Zoning & reading flow              │   │ • Fine lighting falloff & shade│
│ • Exact hard content & copy strings  │   │ • Subtle organic linework      │
│ • Logo architecture & position       │   │   variations                   │
│ • Color role hierarchy & proportions │   │ • Artistic stroke rendering    │
│ • Visual style & design movement     │   │   nuances                      │
└──────────────────────────────────────┘   └────────────────────────────────┘
```

---

## 4. Final Output Construction Pipeline

When generating the final prompt output, assemble the deconstructed design decisions according to the strict universal template:

### Execution Protocol Steps

1. **Header Block Assembly:** State aspect ratio, physical media type, full brand name, the brand theme and personality as a direct visual directive, selected design movement, and the palette's roles, hues, and proportions.
2. **Primary Logo Mark & Branding:** Detail the emblem/wordmark geometry, how it embodies the theme and personality, typography style, descriptor, and structural isolation mechanics.
3. **Composition & Layout Zoning:** Map the physical canvas into distinct spatial zones derived from its dominant axis, visibility, and content groups, aligned to the target reading distance. Place every element, including the tagline, by attention tier and balance, with relative sizes calibrated to the physical scale.
4. **Visual Elements & Rendering Technique:** Detail product displays, hero visuals, the representation mode and expressive character of each visual layer, and line-weight parameters.
5. **Background, Borders & Finish:** Define substrate textures, borders or their deliberate absence, decorative accents, or background pattern density.
6. **Technical & Execution Constraints:** Enforce the layout and rendering rules suited to the medium and style, the legibility distance of each tier, and strict hard-content fidelity.

---

## 5. Verification Checklist

Before emitting the final expanded prompt, execute a final cognitive audit:

* [ ] **Hard Copy Fidelity:** Is every brand name, menu item, price, phone number, address, and trust badge from the brief explicitly included in the prompt text without alterations?
* [ ] **Zero Added Hallucinations:** Did you avoid inserting extra menu items, fake prices, or unrequested social handles?
* [ ] **Open Choice:** Were the design movement, mark architecture, and layout derived from the brief's principles, rather than from the first conventional fit or a listed category?
* [ ] **Contextual Fit:** Does the aesthetic register (finish, formality, realism, production character) belong natively in the placement context, with positioning expressed through signals that setting can carry and distinction coming from a differentiator within its range?
* [ ] **Language & Directness:** Is the entire prompt in English except literal hard content, and is every phrase, including the theme line, a direct visual directive with no rationale?
* [ ] **Theme Coherence:** Is one specific theme and personality stated, embodied first and most fully in the logo mark, and traceable through every other layer at an intensity set by its tier, without altering hard content?
* [ ] **Semantic Density:** Are all visual instructions expressed in professional design, art history, and print production terminology?
* [ ] **Attention Balance:** Does visual weight follow the attention tiers across every dimension (scale, color relationship, placement, isolation), with ornament and lower-tier elements recessive in color and position rather than sharing the hero's, weight distributed across the canvas rather than clustered, and the tagline and contact information placed by role rather than by habit?
* [ ] **Deliberate Devices:** Is each grouping or separation device, representation mode, expressive character, and typographic and decorative voice a specific choice for this brief, including the choice of no boundary where none is needed?
* [ ] **Placement Logic:** Is every placement and group form (including contact information) derived from function, relationship, and counterweight, rather than repeated from a template?
* [ ] **Scale Calibration:** Is each element sized within the band set by its legibility floor and its tier, with surplus canvas given to hero scale and negative space rather than to enlarged secondary content, and with Tier 3 information kept legible but unboosted?
* [ ] **Distinctiveness:** Would any sentence in the prompt survive unchanged in a prompt for a different business? If so, rewrite it.
* [ ] **Template Integrity:** Does the output strictly adhere to the universal template structure defined in `SKILL.md`?
