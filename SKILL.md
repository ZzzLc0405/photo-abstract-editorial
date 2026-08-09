---
name: photo-abstract-editorial
description: Create a clean, vertical editorial artwork that preserves an uploaded photograph as the original image and pairs it with a restrained, photo-derived abstract memory panel and poetic English title. Use when asked to transform a photo into an abstract editorial diptych, photo-plus-abstraction composition, visual memory panel, or minimalist archival poster without redrawing or stylizing the source photo.
---

# Photo Abstract Editorial

Create one finished image from one uploaded photograph. Keep the photograph faithful; derive the lower abstract panel only from the photograph's observed spatial, tonal, and color relationships.

## Input Formats

- Accept rendered raster inputs directly as JPEG/JPG, PNG, WebP, or a still GIF. If a GIF is animated, ask the user to choose or provide the intended frame.
- Do not claim direct support for camera RAW, DNG, CR2/CR3, NEF, ARW, RAF, HEIC, TIFF, SVG, or PDF inputs. Preserve the supplied original unchanged and work from a neutrally rendered sRGB JPEG or PNG copy.
- During conversion, do not apply creative color grading, retouching, generative expansion, or cropping. If the environment cannot make a reliable neutral conversion, ask the user for a rendered JPEG or PNG.

## Workflow

1. Inspect the photograph internally. Identify three to six decisive spatial facts: subject relationships, scale, axes, direction, intervals, overlap, depth, rhythm, light, color roles, and negative space.
2. Keep the photo as the upper or principal section. Permit only proportional scaling or a slight crop needed for the composition. Never redraw, extend, replace, retouch, apply a filter to, or otherwise alter its content.
3. Reconstruct the retained relationships below as a sparse abstract motif—not a thumbnail, trace, illustration, vector icon, or style transfer. Prefer relationships over silhouettes and preserve only the minimum recognition cues needed for distinctive subjects.
4. Compose a vertical work with an untextured, uniform ivory lower panel. Adapt the photo/panel proportions to the photograph rather than splitting the image mechanically in half. Join both sections directly with no frame, shadow, collage, tape, or mockup effect.
5. Use one primary mark family and no more than two supporting families. Extract a muted palette solely from the photo; use generous whitespace and avoid invented decorative elements, colors, symbols, and symmetry.
6. Create one original English title of two to five words, grounded in visible facts. Place it only on the abstract panel in a restrained editorial serif face. Add a short subtitle only when it adds meaning.
7. Return only the completed composition. Do not add commentary, analysis, title options, labels, dates, logos, or watermarks.

## Guardrails

- Treat the uploaded photo as the sole content source.
- Keep the panel background flat, continuous, and neutral ivory; exclude gradients, paper texture, grain, glow, shadows, vignettes, stains, collage artifacts, and scan effects.
- Make every abstract mark traceable to a visual fact in the source photo.
- Preserve people as irregular continuous short vertical marks or gently tapered blocks, never illustrated heads, limbs, faces, or clothing.
- Preserve landmark architecture with at most one to three identity cues; omit architectural surface detail.

## Reference Prompt

Read the appropriate full prompt before producing the image:

- Chinese: [references/photo-abstract-editorial-prompt.zh-CN.md](references/photo-abstract-editorial-prompt.zh-CN.md)
- English: [references/photo-abstract-editorial-prompt.en.md](references/photo-abstract-editorial-prompt.en.md)

Use [assets/examples](assets/examples) as finished-output references only; they are not input photographs or reusable templates. Read the [example guide](assets/examples/README.md) for the behavior each case demonstrates. Do not reuse their subject matter, colors, or composition unless the user supplies that exact image.
