---
name: film-burn-abstract-editorial
description: Transform a partially exposed film scan into an editorial artwork, preserving the source's original dimensions and aspect ratio by default, its exposed photograph, and its original accidental exposure boundary while placing a sparse, source-derived abstraction only in the genuine blank film. Use when a source scan already contains meaningful unexposed film; do not use to create, repair, redesign, or imitate film burns.
---

# Film Burn Abstract Editorial

Preserve the accident. Preserve the frame. Abstract the photograph into its existing absence.

## Region model

- **Exposed photograph:** read-only source.
- **Original film-burn/exposure boundary:** read-only source.
- **Genuine blank/unexposed film:** writable creative canvas.

Proceed only when the input contains a meaningful genuine blank/unexposed region. The film accident is source evidence, not an effect to design.

## Immutable rules

- Preserve the source's original oriented pixel dimensions, full frame, and aspect ratio unless the user explicitly requests a different output format. Do not crop, stretch, or resize merely to create additional writable space.
- Preserve every retained exposed photographic pixel and the retained original exposure boundary unchanged.
- Never create, regenerate, redesign, repair, strengthen, clean, straighten, extend, or imitate the film burn.
- Place generated artwork only inside genuinely unexposed film already present in the source frame.
- Do not extend or reconstruct the photographed scene in the blank region.
- Preserve substantial blank negative space. Use only elements that materially express the source-derived relationships.
- Derive a new abstract grammar independently from each photograph; never impose or reuse a house vocabulary of shapes or devices.
- Include one short poetic or emotional fragment, normally 1–5 words, derived from visible atmosphere, relationships, composition, light, space, rhythm, or tension. Interpret relationships freely; invent facts never.

This version is instruction-only. Do not claim pixel-identical preservation unless the available workflow can guarantee it. A visually similar reconstruction is not preservation; disclose any inability to verify protected pixels as a validation limitation.

## Workflow

1. Inspect the scan and distinguish exposed photography, the original exposure boundary, and genuinely unexposed film. Stop if no meaningful writable region can be identified reliably.
2. Honor the source's display orientation while preserving its original oriented pixel dimensions, full frame, and aspect ratio unless the user explicitly requests a different output format. Do not crop, stretch, or resize merely to create additional writable space, and do not independently alter the boundary.
3. Lock the full exposed photograph and boundary as protected source. Establish only the existing genuine unexposed film as the writable region.
4. Read [references/source-derivation.md](references/source-derivation.md). Select approximately 3–5 relationships that genuinely distinguish this photograph and derive an abstract grammar from them.
5. Read [references/visual-language.md](references/visual-language.md). Reduce the design to a restrained composition that preserves blankness and does not mimic or compete with the film accident.
6. Generate the abstraction separately when possible, then composite it only through the writable region. Do not ask a generative model to recreate protected source pixels.
7. Inspect the complete result against both validation gates. Correct only the failed stage: recomposite from the source for integrity failures; return to derivation for generic artwork.

## Validation gates

### Source integrity

- The output preserves the source's original oriented pixel dimensions, full frame, and aspect ratio unless the user explicitly requested a different output format.
- No unrequested cropping, stretching, resizing, warping, or reframing occurred, and dimensions were not changed merely to create additional writable space.
- The full exposed photograph and original boundary are unchanged, or any inability to guarantee and verify this is stated explicitly.
- Generated content appears only inside genuine retained unexposed film.
- No scene extension, new exposure damage, or imitation film burn appears.

### Creative specificity

- Every abstract element traces to a selected relationship in this photograph.
- Substantial blank film remains and no removable decoration survives.
- Ask: **Could essentially this same abstract composition have been generated from a substantially different photograph?** If yes, reject it and return to source derivation.
- Any text remains secondary, stays inside genuine writable blank film, and passes: **Interpret relationships freely; invent facts never.** If no convincing grounded phrase emerges, omit it.

## Delivery

Show the finished image and saved path when available. Briefly name the selected source relationships, how they informed the abstraction, and any text used. State whether protected-region preservation was actually verified; if not, identify that limitation plainly.
