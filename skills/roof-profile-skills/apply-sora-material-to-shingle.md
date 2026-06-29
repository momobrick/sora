# Apply Sora Material to Shingle

## Purpose
Generate a copy/paste-ready image generation prompt that applies the Sora material signature to a shingle roof profile while preserving the original staggered shingle layout and individual shingle geometry.

## Required reference images
Ask the user to provide both reference images before writing the final prompt:

1. **`sora-roof-pattern_123`** — Sora material pattern, relief, striation, and surface-character reference
2. **`shingle_123`** — smooth shingle roof-profile geometry reference

## Skill behavior
When this skill is used:

1. Confirm that both required references are available.
2. If either image is missing, ask the user to provide the missing image by name.
3. Once both references are available, output a single prompt the user can paste into an image generation tool along with the reference images.
4. Do not generate the image directly.
5. Do not include long explanation unless the user asks for rationale.

## Prompt to generate
Use this structure when generating the paste-ready prompt:

```text
Use the reference image named sora-roof-pattern_123 as the material reference only. Use the reference image named shingle_123 as the roof-profile geometry reference only.

Apply the Sora roof material from sora-roof-pattern_123 to the shingle roof profile shown in shingle_123. Preserve the original shingle geometry and layout, including the staggered rectangular arrangement, individual shingle boundaries, horizontal courses, vertical offsets, seams, raised edges, edge thickness, and visible tile structure.

The final result should still clearly read as a shingle roof profile. Do not merge the shingles into one continuous slab, erase the seams, remove the staggered layout, flatten the shingle edges, or convert the roof into barrel tile, vertical panels, or a single sculptural surface.

Translate the Sora material signature onto the visible faces of the shingles: soft sculptural wave bands, shallow molded relief, subtle dimensional variation, and fine striations that follow the direction of the wave bands. The Sora material should feel embedded into each shingle surface while still respecting the individual shingle units. The pattern may flow across the overall surface, but it must not overpower or hide the shingle boundaries.

Keep the relief visible but controlled. The waves should be subtle to moderate in depth, realistic, architectural, durable, and manufacturable. Preserve the overall lighting, perspective, shadows, grayscale material quality, and product-reference clarity of shingle_123 unless a cleaner neutral product render improves readability.

Do not add text, labels, logos, people, tools, fasteners, vents, skylights, house context, decorative objects, or background distractions. Create a clean product-reference rendering of the same shingle profile with the Sora material integrated into it.
```

## Refinement notes
If the first result erases the shingle grid, emphasize preserving all seams and individual tile boundaries. If the texture looks too uniform, ask for the wave relief to be integrated into each shingle face while keeping the staggered structure legible.
