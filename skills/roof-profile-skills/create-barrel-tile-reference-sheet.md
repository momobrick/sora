# Create Barrel Tile Reference Sheet

## Purpose
Generate a copy/paste-ready image generation prompt for creating a multi-angle reference sheet of the approved Sora barrel tile roof profile.

## Required reference image
Ask the user to provide the approved Sora barrel tile image before writing the final prompt.

1. **Approved Sora barrel tile image** — the final approved result created from `barrel_123` + `sora-roof-pattern_123`

## Optional reference images
The user may also provide these if they want extra consistency, but they are not required:

1. **`barrel_123`** — original smooth barrel tile geometry reference
2. **`sora-roof-pattern_123`** — original Sora material pattern reference

## Skill behavior
When this skill is used:

1. Confirm that the approved Sora barrel tile image is available.
2. If the approved image is missing, ask the user to provide it.
3. Once the approved image is available, output a single prompt the user can paste into an image generation tool along with the approved reference image.
4. Do not generate the image directly.
5. Do not include long explanation unless the user asks for rationale.

## Prompt to generate
Use this structure when generating the paste-ready prompt:

```text
Use the approved Sora barrel tile image as the primary source reference. Create a clean multi-angle product reference sheet showing the same Sora barrel tile roof profile from several useful angles and rotations.

Preserve the approved roof profile exactly. Keep the Sora material character consistent across every view: soft sculptural wave bands, shallow molded relief, subtle dimensional flow, and fine striations that follow the wave direction. Preserve the barrel tile structure: rounded overlapping tile forms, curved tile surfaces, dark shadow gaps, row rhythm, edge thickness, and repeated barrel profile.

Show the Sora material wrapping naturally over the curved barrel tile geometry in every angle. The roof profile should remain clearly readable as barrel tile, not a flat slab, shingle system, vertical panel, or generic sculptural surface.

Create a clean reference-sheet layout with multiple distinct views of the same object: front three-quarter view, opposite three-quarter view, low side angle showing curved barrel depth, top-down or high-angle view showing row rhythm, close-up crop showing Sora relief and striations, and edge or cross-section-like view showing tile thickness and curved profile.

Use a light gray or almost-white background for clear contrast. Keep the lighting soft, even, and product-reference oriented. Keep the views organized clearly on the sheet with enough space between them.

Do not redesign the barrel tile geometry, flatten the tile into a slab, convert it into shingles or vertical panels, change the Sora material language, exaggerate the relief depth, alter the approved material character, or add labels, logos, text, people, tools, fasteners, vents, skylights, house context, or background objects.
```

## Refinement notes
If the result changes the approved profile too much, emphasize preserving the approved Sora barrel tile image exactly. If the sheet is too repetitive, ask for more distinct camera angles and include a close-up texture crop.
