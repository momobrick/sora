# Create Vertical Panel Reference Sheet

## Purpose
Generate a copy/paste-ready image generation prompt for creating a multi-angle reference sheet of the approved Sora vertical panel roof profile.

## Required reference image
Ask the user to provide the approved Sora vertical panel image before writing the final prompt.

1. **Approved Sora vertical panel image** — the final approved result created from `vertical_123` + `sora-roof-pattern_123`

## Optional reference images
The user may also provide these if they want extra consistency, but they are not required:

1. **`vertical_123`** — original smooth vertical panel geometry reference
2. **`sora-roof-pattern_123`** — original Sora material pattern reference

## Skill behavior
When this skill is used:

1. Confirm that the approved Sora vertical panel image is available.
2. If the approved image is missing, ask the user to provide it.
3. Once the approved image is available, output a single prompt the user can paste into an image generation tool along with the approved reference image.
4. Do not generate the image directly.
5. Do not include long explanation unless the user asks for rationale.

## Prompt to generate
Use this structure when generating the paste-ready prompt:

```text
Use the approved Sora vertical panel image as the primary source reference. Create a clean multi-angle product reference sheet showing the same Sora vertical panel roof profile from several useful angles and rotations.

Preserve the approved roof profile exactly. Keep the Sora material character consistent across every view: soft sculptural wave bands, shallow molded relief, subtle dimensional flow, and fine striations that follow the wave direction. Preserve the vertical panel structure: long panel pans, raised ribs, vertical seams, rib spacing, crisp edges, side returns, metal-panel geometry, and panel thickness.

The Sora material should live primarily within the flat or recessed panel pans between the raised ribs. The raised ribs must remain clearly visible and structurally accurate. The roof profile should still read as a vertical panel system in every view, not as shingles, barrel tile, a flat slab, or a generic sculptural surface.

Create a clean reference-sheet layout with multiple distinct views of the same object: front three-quarter view, opposite three-quarter view, low side angle showing rib height and panel depth, top-down or high-angle view showing vertical rib spacing, close-up crop showing Sora relief and striations inside the panel pan, and edge or profile view showing rib geometry and panel thickness.

Use a light gray or almost-white background for clear contrast. Keep the lighting soft, even, and product-reference oriented. Keep the views organized clearly on the sheet with enough space between them.

Do not erase or soften the raised ribs, let the wave pattern overpower the vertical panel structure, run the pattern across seams in a way that hides the panel logic, convert it into shingles, barrel tile, or a flat sculptural slab, change the Sora material language, exaggerate the relief depth, alter the approved material character, or add labels, logos, text, people, tools, fasteners, vents, skylights, house context, or background objects.
```

## Refinement notes
If the result loses the vertical panel logic, emphasize preserving the raised ribs and panel pans from the approved image. If the material spreads across ribs too much, ask for the Sora relief to remain primarily inside each panel pan.
