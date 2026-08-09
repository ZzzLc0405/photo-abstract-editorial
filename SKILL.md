---
name: photo-abstract-editorial
description: Create a clean standalone abstract artwork derived from an uploaded photograph's spatial, tonal, and color relationships. Use when asked to turn a photo into a restrained abstract memory panel, minimalist photo-derived abstraction, or editorial abstract composition without displaying, redrawing, or stylizing the source photo and without titles, captions, or other text.
---

# Photo Abstract Editorial

Create one finished abstract image from one uploaded photograph. Treat the photograph only as a private visual source; do not include it in the output. Derive every visible element from its observed spatial, tonal, and color relationships.

## Workflow

1. Inspect the photograph internally. Identify three to six decisive spatial facts: subject relationships, scale, axes, direction, intervals, overlap, depth, rhythm, light, color roles, and negative space.
2. Reconstruct those relationships as a sparse abstract motif, not a thumbnail, trace, illustration, vector icon, filtered photo, or style transfer. Prefer relationships over silhouettes and preserve only the minimum recognition cues needed for distinctive subjects.
3. Compose a single standalone abstract artwork on a flat, uniform neutral-ivory canvas. Do not place the source photograph anywhere in the composition and do not create a photo/abstract split, diptych, panel join, frame, collage, or mockup.
4. Use one primary mark family and no more than two supporting families. Extract a muted palette solely from the photo; use generous whitespace and avoid invented decorative elements, colors, symbols, and symmetry.
5. Render no typography or written content. Do not create a title, subtitle, caption, label, date, number, logo, signature, or watermark.
6. Generate exactly one variation in a single image-generation call. Return and display exactly one completed abstract artwork without commentary or analysis.

## Guardrails

- Treat the uploaded photo as the sole content source but never display or reproduce it in the output.
- Keep the entire canvas background flat, continuous, and neutral ivory; exclude gradients, paper texture, grain, glow, shadows, vignettes, stains, collage artifacts, and scan effects.
- Make every abstract mark traceable to a visual fact in the source photo.
- Preserve people as irregular continuous short vertical marks or gently tapered blocks, never illustrated heads, limbs, faces, or clothing.
- Preserve landmark architecture with at most one to three identity cues; omit architectural surface detail.
- Keep the result image-only and text-free.
- Never request, generate, attach, or display multiple candidates, variants, duplicates, or before/after images. Do not place two copies inside one canvas. If a tool unexpectedly provides duplicate outputs, keep and return only the first unique image.

## Reference Prompt

Read the appropriate full prompt before producing the image:

- Chinese: [references/photo-abstract-editorial-prompt.zh-CN.md](references/photo-abstract-editorial-prompt.zh-CN.md)
- English: [references/photo-abstract-editorial-prompt.en.md](references/photo-abstract-editorial-prompt.en.md)

Use [assets/examples](assets/examples) only as references for abstraction language and restraint. Ignore any source-photo region or typography shown in those legacy examples. Do not reproduce their diptych layout, text, subject matter, colors, or composition unless independently required by the user's supplied photo.
