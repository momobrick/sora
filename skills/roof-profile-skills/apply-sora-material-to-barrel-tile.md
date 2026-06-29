# Apply Sora Material to Barrel Tile

## Purpose
Generate a copy/paste-ready image generation prompt that applies the Sora material signature to a barrel-tile roof profile while preserving the original barrel-tile geometry.

## Required reference images
Ask the user to provide both reference images before writing the final prompt:

1. **`sora-roof-pattern_123`** — Sora material pattern, relief, striation, and surface-character reference
2. **`barrel_123`** — smooth barrel tile roof-profile geometry reference

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
Use the reference image named sora-roof-pattern_123 as the material reference only. Use the reference image named barrel_123 as the roof-profile geometry reference only.

Apply the Sora roof material from sora-roof-pattern_123 to the barrel tile roof profile shown in barrel_123. Preserve the original barrel tile geometry, including the rounded overlapping barrel forms, curved tile surfaces, row spacing, visible dark shadow gaps, edge conditions, tile thickness, and repeated roof rhythm.

The final result should still clearly read as a barrel tile roof profile. Do not flatten the barrel tiles, remove the overlaps, erase the gaps, simplify the profile, or convert it into shingles, vertical panels, or a flat sculptural slab.

Translate the Sora material signature onto the barrel tile surfaces: soft sculptural wave bands, shallow molded relief, subtle dimensional flow, and fine striations that follow the direction of the wave bands. The Sora texture should wrap naturally over the rounded tile forms and conform to the curved geometry, as if the material is manufactured into the tile itself. It should not look like a separate slab or surface pattern pasted on top.

Keep the relief visible but controlled. The waves should be subtle to moderate in depth, realistic, architectural, durable, and manufacturable. Preserve the overall lighting, perspective, shadows, grayscale material quality, and product-reference clarity of barrel_123 unless a cleaner neutral product render improves readability.

Do not add text, labels, logos, people, tools, fasteners, vents, skylights, house context, decorative objects, or background distractions. Create a clean product-reference rendering of the same barrel tile profile with the Sora material integrated into it.
```

## Refinement notes
If the first result is too flat, ask for stronger but still shallow relief. If the profile is distorted, emphasize preserving `barrel_123` as geometry. If the material looks pasted on, emphasize that the Sora waves must wrap over the curved barrel forms.
