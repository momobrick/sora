# Apply Sora Material to Vertical Panel

## Purpose
Generate a copy/paste-ready image generation prompt that applies the Sora material signature to a vertical panel roof profile while preserving the original vertical panel geometry.

## Required reference images
Ask the user to provide both reference images before writing the final prompt:

1. **`sora-roof-pattern_123`** — Sora material pattern, relief, striation, and surface-character reference
2. **`vertical_123`** — smooth vertical panel roof-profile geometry reference

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
Use the reference image named sora-roof-pattern_123 as the material reference only. Use the reference image named vertical_123 as the roof-profile geometry reference only.

Apply the Sora roof material from sora-roof-pattern_123 to the vertical panel roof profile shown in vertical_123. Preserve the original vertical panel geometry, including the long vertical panel organization, raised ribs, recessed or flatter panel pans, rib spacing, panel edges, side returns, metal thickness, and overall roof-panel structure.

The final result should still clearly read as a vertical panel roof profile. Do not erase the ribs, soften the panel seams too much, flatten the profile, merge the panels into one continuous slab, or convert the roof into shingles, barrel tile, or a generic sculptural surface.

Translate the Sora material signature onto the vertical panel system: soft sculptural wave bands, shallow molded relief, subtle dimensional flow, and fine striations that follow the direction of the wave bands. The Sora wave texture should live primarily within the flat or recessed panel pans between the raised ribs. The raised ribs should remain crisp, visible, and structurally dominant. The wave pattern may repeat within each panel pan rather than flowing continuously across the ribs.

Keep the relief visible but controlled. The waves should be subtle to moderate in depth, realistic, architectural, durable, and manufacturable. Preserve the overall lighting, perspective, shadows, grayscale material quality, and product-reference clarity of vertical_123 unless a cleaner neutral product render improves readability.

Do not add text, labels, logos, people, tools, fasteners, vents, skylights, house context, decorative objects, or background distractions. Create a clean product-reference rendering of the same vertical panel profile with the Sora material integrated into it.
```

## Refinement notes
If the first result loses the panel ribs, emphasize that `vertical_123` controls geometry and the raised ribs must remain crisp. If the wave pattern spreads across seams too much, ask for the Sora texture to repeat within each panel pan.
