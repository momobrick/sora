# Divided Lighting

## Purpose

Create Sora’s signature split-state image treatment by transforming a single house/environment image into a two-condition composition:

- left side = Reflect Mode + bright midday lighting
- right side = Absorb Mode + dusk lighting

This skill is used to show Sora’s temperature-responsive roof behavior in a single, clear, photorealistic image.

## Use this skill when

- You already have a finished house/environment image.
- You want to apply the Sora split visual treatment without redesigning the architecture or landscape.
- You want to show Reflect Mode and Absorb Mode in one composition.
- You need a consistent Sora campaign image treatment.

## Do not use this skill when

- You need to generate a house from scratch.
- You need to generate a landscape plate from scratch.
- You want to redesign the home, environment, or roof form.

## Core task

Use the house/environment image as the base image and preserve it as much as possible. Apply a split lighting and roof-color treatment only.

## Required outcome

The final image should show:

- one original house
- one original environment
- one continuous sky
- one organic dividing boundary
- left side in Reflect Mode / midday
- right side in Absorb Mode / dusk

The result should feel like the same real image under two conditions, not two separate images stitched together.

## Inputs

- A base house/environment image
- Optional visual references for:
  - Reflect roof color
  - Absorb roof color
  - midday lighting mood
  - dusk lighting mood
  - dividing curve character
  - cloud shape and quality

## Instructions

1. Preserve the original image as much as possible.
2. Do not redesign, regenerate, restyle, or replace:
   - the house
   - the landscape
   - the roof type
   - the roof pattern
   - the materials
   - the windows and doors
   - the camera angle
   - the overall composition
3. Add one organic curvilinear dividing boundary spanning from the top edge to the bottom edge of the composition.
4. The split should be defined by the change in lighting and roof color only.
5. Do not add a visible graphic line, outline, border, halo, glow, or seam along the boundary.
6. Keep the sky continuous across the full composition.
7. Use one unified cloud system across the entire sky.
8. On the left side:
   - apply bright midday lighting
   - keep light coming from the left
   - add realistic daylight shadows
   - change only the roof color to Reflect Mode
9. On the right side:
   - apply dusk lighting
   - keep directional logic consistent
   - soften or remove strong shadows
   - change only the roof color to Absorb Mode
   - add a soft warm glow to visible windows
10. Preserve the roof material identity exactly as it exists in the original image.

## Reflect Mode roof color guidance

Use a light, slightly warm gray family such as:

- soft mineral gray
- pale stone gray
- subtle taupe-gray undertones

## Absorb Mode roof color guidance

Use a deep warm charcoal family such as:

- warm charcoal
- dark graphite
- subtle smoked-bronze undertones

## Guardrails

- Do not change the roof material or pattern.
- Do not add standing-seam lines, shingles, tiles, or any new texture.
- Do not regenerate the landscape.
- Do not alter the architecture.
- Do not create two different skies.
- Do not create mismatched cloud formations across the boundary.
- Do not add text, icons, people, or decorative elements.
- Do not make the transition feel graphic or artificial.

## Success criteria

A successful output:

- feels photorealistic
- preserves the original image
- clearly communicates Sora’s dual-mode behavior
- has a smooth, elegant split
- avoids AI artifacts
- keeps the roof type intact while changing only color

## Prompt scaffold

Use the house/environment image as the base image. Preserve the original image as much as possible. Do not redesign, regenerate, restyle, or replace the house, landscape, materials, roof type, roof pattern, windows, doors, camera angle, composition, or realism. The goal is to apply a split lighting and roof-color treatment only.

Add one organic curvilinear dividing boundary spanning from the top edge to the bottom edge of the composition. The boundary should be broad, fluid, and gently sculptural. It must remain clean and crisp but should not appear as a graphic line or stroke. Do not add any visible outline, border, glow, halo, seam, white line, black line, or colored line.

Keep one continuous sky across the whole composition. Use one unified cloud structure from left to right. The cloud forms should remain continuous across the boundary, with only the lighting and color temperature changing between sides.

On the left side, apply bright midday lighting with realistic shadows and change only the visible roof surfaces to Reflect Mode coloring. On the right side, apply dusk lighting with softened shadows, change only the visible roof surfaces to Absorb Mode coloring, and add a soft warm interior glow to visible windows.

Do not change the roof material or roof pattern in any way. Preserve the existing roof exactly as it appears in the original image and change color only.

The final result should look like the same original photorealistic house in the same real environment, shown in two environmental states: midday / Reflect Mode on the left and dusk / Absorb Mode on the right.
