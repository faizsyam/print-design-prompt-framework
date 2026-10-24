# Style Bank: Articulating a Direction for Generators

*Used in Phases 4 and 5 of `SKILL.md`, and in Phase 2 when a chosen term is resolved (`02`, Section 5). Facet letters and entry codes refer to `06`. Consultation rules and guardrails are in `05`.*

Practitioners who get reliable results from image generators converge on the same habits. This file turns them into a reference for the prompt.

**Precedence.** `04` and `SKILL.md`, Sections 4 and 5, govern the prompt's structure, content fidelity, and form. This file supplies the vocabulary habits, the reliability handling, and the specificity audit that serve them. Where this file seems to conflict with them, they win.

---

## 1. Anatomy of a Direction

A direction is complete when it resolves each of the following into visible properties. Fill the slots the brief needs; do not invent slots.

| Slot | Meaning | Where it lands in the template (`SKILL.md`, Section 4) |
| :--- | :--- | :--- |
| Lineage | The governing tradition, era, or region, with its distinguishing traits | Header: governing design movement or tradition |
| Technique and material | How the work visibly appears made (drawn, painted, cut, printed, constructed) and the visible character of its materials | Header (movement traits); Visual Elements & Rendering Technique; Background, Borders & Finish |
| Form language | Shape vocabulary, edge behavior, line quality, depth | Header: form language, edge behavior, aesthetic tone |
| Palette logic | Harmony, value structure, saturation behavior, ink or pigment sources, and proportions | Header: color palette architecture |
| Typographic voice | Structure of the display and supporting voices and how lettering is made | Composition & Layout Zoning (voices per hierarchy level); Primary Logo Mark (mark lettering) |
| Imagery roles and registers | For each image: kind of making, the style signature's traits, and the register its role calls for (`08`; Section 7 here) | Visual Elements & Rendering Technique; imagery that forms or sits within the ground goes to Background, Borders & Finish; position and relative scale go to Composition & Layout Zoning |
| Composition structure | Grid or axis, balance, negative-space idiom, density | Composition & Layout Zoning |
| Surface and finish | Ground texture, sheen, and wear as they appear in the image | Background, Borders & Finish; Technical & Execution Constraints |
| Inflection | The brand-specific turn that makes the direction this brand's own | Header: concept and movement traits |
| Mark construction (Facet I) | Mark type and construction, silhouette, lettering moves, symbol, boundary or open silhouette, color logic, internal levels, variant, relative scale and clear space (`09`; Section 8 here) | Primary Logo Mark & Branding |

Imagery is directed per image, and the register of each differs from the others only by what its role requires (`08`). Production process, substrate, mounting, and placement are never slots. They inform choices (Facets G, L, M) and enter the prompt only as a visible property of the image (`SKILL.md`, Principle 12).

---

## 2. Phrasing Rules

1. **Place the governing style early, in observable terms.** A named lineage pulls toward real design only when its traits follow it; a name alone or an adjective alone is thin. In the template it sits in the header with the concept.
2. **One dominant lineage, bounded influences.** State the dominant lineage for structure and, separately, any secondary influence limited to one property (texture, palette, mood, or lettering). Reinforce one logic with consistent terms; do not stack contradictory styles.
3. **Concrete over abstract.** Replace qualities with materials, shapes, textures, light, and process. Specify the visible making (how ink, paint, paper, or cut layers look on the surface, such as flat screenprinted ink layers or brush-painted enamel) and the rendering stance. Name how the image looks made, never how it is manufactured or where it is shown.
4. **Positive properties before negations.** Say what the image is (a flat matte ink surface, limited ink colors, asymmetric positioning with open ground) and add negations only for defaults that would damage the piece.
5. **Describe color by hue, role, and a limited count.** Exact color codes and brand fonts are not reliably honored by generators, so describe hue, value, and saturation character, and describe type by its structure.
6. **Quote text, set it as typography, and keep it short.** Put required copy in quotation marks, give its position and typographic structure, render each string once, and avoid asking generators to set long passages beyond what the brief requires. Spell out uncommon names when accuracy matters.
7. **Direct space explicitly.** Generators tend to fill the canvas to match their training frames, and aspect ratio changes framing. State margins, empty regions, and the density target as relationships (wide outer margins, a modest fraction of the canvas occupied), never as measurements unless the brief supplies them.
8. **Describe photographic looks in photographic terms,** and avoid words that imply studio polish when the stance is candid or documentary. Camera specifications give general look, not exact simulation.
9. **Separate decisions.** Keep each decision in one sentence in its own slot so any one can be adjusted without disturbing the others.
10. **Prefer lineage and technique to named people.** Do not cite living artists, brands, or characters as the style.
11. **State imagery per image, in registers.** Each image takes one entry holding its subject, its kind of making with the signature's traits, its register in visible settings (Section 7), and what binds it to the other images. Never copy one image's entry onto another, and never describe a secondary image as "the same style" without its own settings.
12. **Stay inside the frame.** Do not state where the piece hangs, what surrounds it, who sees it, from how far, what it is for, or how it is produced. Convert each into its visible consequence and write that (`SKILL.md`, Principle 12).

---

## 3. Default Gravity

Left unspecified, generators regress to a recognizable average: glossy plastic rendering, glow and sheen, saturated gradient palettes, centered symmetrical layouts, a filled canvas, generic neutral type, uniform soft lighting, and stock-photo blandness. Counter each by specifying a considered property in its place (visible ink and surface behavior, a limited named palette, asymmetric placement with open ground, a typographic structure, directional light), not only by prohibition.

The mark has its own gravity. Unspecified, the brand name is set as a line of display-style text, perhaps with an underline or a small icon, and a generic ring, shield, or pill appears around it; the symbol arrives as a stock motif beside plain lettering; the mark is scaled by the generator's sense of importance. Counter with a stated silhouette, structure, lettering moves, boundary relation, and scale ratio (Section 8).

Images add their own gravity. Unspecified, every image receives the same polish and detail as the leading one; a field behind type becomes a stock scene with a flat translucent wash over it; a focal subject lands in the middle of any frame, including the region where type sits; decorative imagery arrives as hero-quality rendering at a small size; repeated items drift in angle, light, and scale; icons arrive in mixed styles; a requested subtle or faded look becomes a gray veil that removes the style. Counter each with the specific property: a stated register per image (Section 7), a designed calm region with its position and value band, a shared framing rule for siblings, and a single icon logic.

---

## 4. Reference Decomposition

Designers steer generators with reference images and style codes. A text-only prompt has none, so decompose the intended look into the same attributes a reference would carry: palette and value structure, line and edge behavior, texture and finish, composition and spacing, lighting and grade, and era or craft cues. State these as properties and keep them consistent across every layer. The same decomposition reads a style's signature (`08`, Section 3.1): sorting the properties into making, edge, color, light and space, simplification, and surface logic shows which are primary anchors and which flex by role.

---

## 5. Generator Reliability by Element

Reliability decides how an element is directed. It never decides whether required content appears: hard content is always stated verbatim (`SKILL.md`, Section 5, rule 2).

| Element | Reliability | Handling |
| :--- | :--- | :--- |
| Short headline text (one to four words) | Moderate to good | Quote exactly; one string per area |
| Long copy, small print, prices, phone numbers | Poor | Still state every required string verbatim in quotation marks. Keep them in few clean blocks, one string per area, with tabular alignment for prices, at the size the viewing distance needs. Reserve a clean empty area instead only for content the brief says will be added afterward |
| QR codes | Cannot be generated meaningfully | Reserve a blank white square with a clear quiet zone at its placed position |
| Logos and brand marks | Unreliable | When the brief supplies a mark, direct its placement, relative scale, and clear space and do not ask for its recreation. When none is supplied, design it per `09` and direct a construction the generator can hold: one definite silhouette, few parts, flat fills, lettering resolved to structure (single-enclosure emblem, built wordmark with a stated silhouette, or symbol-plus-name lockup, whichever won the evaluation) |
| Regulated marks (halal, QRIS) | Must not be generated | Reserve a clear area at its placed position |
| Non-Latin scripts (Arabic, Jawi, Hanzi, Hangeul, Brahmic) | Poor | Use only exact supplied text, or avoid |
| Hands, faces, and crowds | Unreliable | Use silhouette, illustration, or crop |
| Food and beverage | Good with specific cues | Use Facet C8 cues |
| Consistent repeated icons | Drifts | Specify a single icon style and keep few |
| Hand-lettered look | Moderate | Describe construction (brush-built, outlined, offset shadow) |
| Gradients on large format | Banding risk in print | Use grain gradients or flat fields |
| Exact color matches | Not honored | Describe by hue and role |
| Patterns and textile motifs | Moderate | Specify motif structure and repeat |
| Series of repeated item images | Drifts in vantage, light, scale, and ground | State one shared framing rule (vantage, light direction, subject scale in frame, ground) once, then list only the subjects |
| Full-bleed field that must leave a calm region for type | Generators center a focal subject | Direct the calm region by position and value band, and place any focal content outside it; direct the field's edges to dissolve in the style's own manner |
| Large texture or tonal fields | Banding and smoothing at large format | Use grain or visible surface marks at a stated scale, or flat tonal fields, not smooth gradients |
| Scenes with people in the background | Faces and hands unreliable | Reduce people to silhouette, crop, motion blur, or back view; keep them out of the calm region |
| Diagrams and explanatory drawings | Labels and fine geometry drift | Draw geometry as simple consistent shapes; every label is hard-content text set once in its own string |
| Icon sets beside list items | Style drift across icons | One grid, one stroke or fill logic, few distinct forms, each icon depicting a supplied item only |
| Faded, low-contrast, or ambient imagery | Becomes a generic gray veil | Lower dials by transfer (`08`, Section 4.4): keep the style's palette logic, edge or mark behavior, and surface, and state them |

---

## 6. Specificity Audit: From Vague Words to Visible Properties

These conversions show alternative ways to resolve common vague words. They are not equivalents and should be chosen from the drivers.

| Vague word | Possible visible resolutions |
| :--- | :--- |
| Modern | Asymmetric layout with open ground and neutral grotesque; or flat vector with geometric sans and limited palette; or neo-brutalist hard borders; depends on field position |
| Premium | Tonal palette, fine letterspacing, ample margins, foil or spot gloss accent, uncoated stock; or dense engraved ornament with deep jewel colors |
| Friendly | Rounded terminals, warm temperature, hand-lettered accent, rounded shape family, visible people or hands |
| Traditional or heritage | Named tradition with its structure (for example, emblem-centered kemasan jadul layout in few flat inks); craft process visible |
| Fresh | Clear light, high-key tonal range, green or citrus accents, water droplets, open space |
| Rustic | Kraft or wood grain texture, hand-lettering, matte ink, imperfect edges |
| Energetic | Diagonals, burst shapes, high chroma, scale jumps, condensed heavy type |
| Clean | Few elements, consistent gutters, restricted palette, no ornament |
| Luxurious | Restraint plus material: black and gold foil, deep ground, wide tracking, small mark |
| Authentic | Documentary photography, unretouched, local lettering, honest imperfections |
| Playful | Rounded shapes, mascot, tilted elements, bright palette |
| Logo, logo-like, or distinctive mark | One unit with a stated silhouette; lettering built with named moves (ligature, shared stroke, custom terminals, a substituted letter); a boundary or implied block with a stated form and relation to the lettering, or an open silhouette with a defined contour; its own color logic; a symbol described as simplified form; never "the name in a nice font" |
| Badge or emblem | A contained form (named) holding lettering built for it, with stated margins, alignment, and whether lettering touches or breaks the boundary; not a stock ring around set type |
| Wordmark | Name as lettering built for the mark: its moves, its silhouette, and what separates it from the headline in structure; never a bare typeface name |
| Ramai tapi rapi (busy but tidy) | Dense field with relief: grid-based product wall, one dominant hero, single color band for headline |
| Subtle | Compressed value band with the style's primary anchors still visible at low amplitude; or a few large simplified forms; never an opacity reduction alone |
| Background | A ground whose resolution is low, edges dissolve in the style's own manner, values are held in one band, and a calm region sits where type sits; or a texture field with no subject; or a pattern field on a reserve |
| Decorative | A motif in the movement's own vocabulary at low resolution, recessive color relationships, confined to edges or intervals; no subject detail |
| Faded or washed | Narrow value band plus the style's mark or surface behavior kept visible; not a gray veil |
| Textured | A named surface logic (grain, ink squash, brush ridge, weave, paper tooth) at a stated scale relative to the image |
| Detailed | A named list of what is resolved (crumb, fiber, droplets, stitching) at the focal area, with relaxation outward |
| Simple | Few large forms, closed silhouette, restricted palette, and the style's anchors at coarse scale |
| Hero | One dominant image with the highest settings of tonal range, chroma, and edge in the piece and every primary anchor fully visible |
| Same style across images | The same palette logic, edge logic, light logic, and surface behavior at different settings, with each difference traceable to a role |

**Audit questions.** For each decision in the prompt: Can the reader of the prompt imagine a specific surface? Is the visible making named? Is the palette limited and sourced? Is type described by structure? Is negative space directed? Does the piece survive its viewing distance and production process (checked internally against Facet M, and not stated in the prompt)? Does every phrase pass the frame boundary (`SKILL.md`, Principle 12)? Does it avoid regulated and sacred elements (`05`, Section 3; Facet N5)?

---

## 7. Registers in the Prompt: Dial Settings as Visible Properties

*Used with `08`, Sections 4 and 6. A register is a style signature at the settings a role calls for. Write it as observable properties, in the style's own vocabulary, one entry per image.*

Each setting converts into what can be seen. The patterns below are generic; resolve them through the signature (a flat-ink style states layers, shapes, and ink behavior; a captured style states focus, light, grade, and crop; a line-led style states line weight, hatching, and ground; a rendered style states form, material, and shadow). Choose the wording that fits the family (`06`, Facet P2), never the generic pattern verbatim.

| Dial | Low-end patterns | High-end patterns |
| :--- | :--- | :--- |
| Resolution | resolved as a few large simplified forms with no interior detail; closed silhouette | fine surface detail resolved across the subject and named (crumb, fiber, droplets, stitch, vein), relaxing toward the edges of the frame |
| Tonal range | values held in one narrow band with no deep darks or pure lights | full value spread with deep darks and bright lights; strong directional light |
| Chroma and palette breadth | limited to two hues and tints of the ground color | wide, saturated palette with distinct hue relationships |
| Edge and separation | forms fade into the ground in the style's own manner (bleed, grain dissolve, focus melt) with no contour | clean, continuous contour or cut edge; subject isolated against open ground |
| Depth and focus | single plane, no cast shadow, even focus | layered planes with a sharp focal plane and melted foreground or background |
| Completeness and crop | fragment cropped tight or bleeding off the canvas edge | whole subject centered or placed with open room on every side |
| Mark and surface visibility | smooth, invisible making | visible stroke, grain, ink squash, brush ridge, weave, or relief at a stated scale relative to the subject |
| Specificity | typified shape, generic form | particular, identifiable subject with its distinguishing features |

**Writing the entry.** One sentence or two per image: the subject and its complexity; the kind of making and the signature's traits in the style's vocabulary; the settings that differ from the piece's leading image, resolved as above; the edge and crop behavior; and the shared properties that bind it to the other images (palette logic, edge character, light direction, surface behavior). Position and relative scale are stated once in the composition slot.

**Converting role to visible consequence.** The role is never named; what it requires is drawn.

| Analysis | Written as depiction |
| :--- | :--- |
| the image must host type | a region of the image, at a stated position and extent, held to one value band with low detail and dissolved edges, with focal content placed outside it |
| the image is subordinate to a leader | lower tonal range, lower chroma, softer edge, and reduced detail than the leading image, on the same palette and mark logic |
| the images are a series | one shared vantage, light direction, subject scale in frame, ground, and crop, then the list of subjects |
| the image is a felt field | a field of surface texture or pattern at a stated scale with no focal subject and compressed values |
| the image is explanatory | simple consistent shapes with uniform line, few hues used as code, and no atmosphere |

**Audit questions for imagery.** Does each image have its own register, with every difference traceable to its role? Do the registers share palette, edge, light, and surface behavior? Is any image described by a role word, a purpose, or a situation? Is any register a bare opacity or blur reduction? Does every image depict only supplied content?

---

## 8. Writing the Mark

*Used with `09`, Section 6. The mark is one entry in the mark slot, stated once. It describes a constructed unit, not a category.*

**Anatomy of the entry.** Fill the slots the mark has; do not invent slots.

| Slot | Written as |
| :--- | :--- |
| Type and construction | what the mark is (built wordmark, emblem, symbol-plus-name lockup, monogram, character) and how its parts are held together |
| Silhouette | the overall contour (block, arch, round, tapered, stepped, asymmetric) and its proportions relative to its height |
| Lettering | structural traits (proportion, stroke modulation, terminals, joins) and the moves built in (ligature, shared stroke, substituted letter, constructed counter), with the brand name verbatim, in quotation marks, once |
| Symbol | what it depicts as simplified form, how it relates to the lettering in scale and position |
| Boundary | a named enclosure with its form, line weight, and the lettering's relation to it (margin, alignment, touching or breaking it); or an implied boundary (field, bars, brackets, cut); or an open silhouette with the contour stated |
| Color logic | fills and strokes, number of colors, relation to the ground, its own color field if any |
| Internal levels | the order of parts; descriptor as a separate clean line or block in a stated ratio to the name |
| Variant | the arrangement (stacked, horizontal, compact, symbol-only) and its detail level, resolved as coarse or fine strokes, few or many parts |
| Scale and clear space | the mark's size as a ratio to the other hierarchy levels and the open space around it relative to its own height |
| Separation | how it stands from its ground (boundary, isolating space, own field) |

**Rules.**
1. Describe construction and silhouette, not the word "logo". State what the unit looks like.
2. Resolve lettering to structure and moves, and never to a typeface name or a bare adjective.
3. A boundary is named with its geometry and its relation to the lettering. An open mark states its contour instead.
4. No role language, no purpose, no situation. The mark's prominence enters as a scale ratio, clear space, and contrast with the ground.
5. A supplied mark is placed and sized by relationship and reserved as a clean area; it is not described or recreated.
6. Keep the mark simple enough to render: one silhouette, few parts, flat fills, strokes sized for coarse reproduction when it is small. A construction the generator cannot hold (curved text on long names, fine inner detail) is simplified in the entry, never dropped.
7. The mark's own entry holds the construction. The composition slot holds only its position and its ratio to neighbors, and the brand name is not re-stated elsewhere.

**Audit questions.** Can the reader of the prompt draw this mark's silhouette? Is the lettering built, with its moves named? Is the boundary or its absence a stated, specific form? Would the entry still describe this brand's mark if the name were swapped? Is any phrase a role, a purpose, or a situation? Does the name appear once?