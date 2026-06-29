# Create Shingle Reference Sheet

## Purpose
Generate a copy/paste-ready image generation prompt for creating a multi-angle reference sheet of the approved Sora shingle roof profile.

## Required reference image
Ask the user to provide the approved Sora shingle image before writing the final prompt.

1. **Approved Sora shingle image** — the final approved result created from `shingle_123` + `sora-roof-pattern_123`

## Optional reference images
The user may also provide these if they want extra consistency, but they are not required:

1. **`shingle_123`** — original smooth shingle geometry reference
2. **`sora-roof-pattern_123`** — original Sora material pattern reference

## Skill behavior
When this skill is used:

1. Confirm that the approved Sora shingle image is available.
2. If the approved image is missing, ask the user to provide it.
3. Once the approved image is available, output a single prompt the user can paste into an image generation tool along with the approved reference image.
4. Do not generate the image directly.
5. Do not include long explanation unless the user asks for rationale.

## Prompt to generate
Use this structure when generating the paste-ready prompt:

```text
Use the approved Sora shingle image as the primary source reference. Create a clean multi-angle product reference sheet showing the same Sora shingle roof profile from several useful angles and rotations.

Preserve the approved roof profile exactly. Keep the Sora material character consistent across every view: soft sculptural wave bands, shallow molded relief, subtle dimensional flow, and fine striations that follow the wave direction. Preserve the shingle structure: staggered rectangular layout, individual shingle boundaries, horizontal courses, vertical offsets, seams, raised edges, edge thickness, and visible tile structure.

The Sora material should remain integrated into each shingle face. The roof profile must still read clearly as a shingle system in every angle, not as one continuous sculpted slab, barrel tile, vertical panel, or generic roof surface.

Create a clean reference-sheet layout with multiple distinct views of the same object: front three-quarter view, opposite three-quarter view, low side angle showing shingle thickness and overlap, top-down or high-angle view showing staggered layout, close-up crop showing Sora relief and striations, and edge or profile view showing individual shingle depth.

Use a light gray or almost-white background for clear contrast. Keep the lighting soft, even, and product-reference oriented. Keep the views organized clearly on the sheet with enough space between them.

Do not merge shingles into one continuous slab, erase seams, offsets, raised edges, or tile boundaries, convert it into barrel tile or vertical panel geometry, change the Sora material language, exaggerate the relief depth, alter the approved material character, or add labels, logos, text, people, tools, fasteners, vents, skylights, house context, or background objects.
```

## Refinement notes
If the result erases the shingle structure, emphasize preserving individual shingle boundaries and staggered courses. If the sheet feels too flat, ask for a low side view that clearly shows edge thickness and overlap.
