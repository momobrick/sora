# Divided Lighting Treatment

## Purpose
Generate a paste-ready image-editing prompt that applies Sora’s signature split-state lighting treatment to a supplied house/environment image.

Use this skill to transform one finished house-in-environment image into a clear two-condition composition:
- left side = Reflect Mode + bright midday lighting
- right side = Absorb Mode + dusk lighting

This skill is used to show Sora’s temperature-responsive roof behavior in a single, clear, photorealistic campaign image while preserving the original house, landscape, roof material, camera angle, and composition.

## Use this skill when
- You already have a finished house/environment image.
- The house may already have a Sora roof profile applied, such as vertical panel, shingle, or barrel tile.
- You want to apply the Sora split visual treatment without redesigning the architecture or landscape.
- You want to show Reflect Mode and Absorb Mode in one composition.
- You need a consistent Sora campaign image treatment.
- You want a clean prompt that can be copied and pasted into an image-generation or image-editing tool along with the reference images.

## Do not use this skill when
- You need to generate a house from scratch.
- You need to generate a landscape plate from scratch.
- You need to place a house into a landscape.
- You want to change the house style, roof shape, roof pitch, roof material, roof pattern, or roofline.
- You want to apply a new roof profile, such as barrel tile, shingle, or vertical panel.
- You want to redesign, improve, replace, expand, or reinterpret the environment.

## Required inputs
1. **Base house/environment image** — the finished image to edit. This should already contain the house, roof, site, landscape, sky, lighting, camera angle, and composition that should be preserved.

## Optional reference inputs
Use these when available. The reference names may be replaced with the user’s actual image names.

1. **Reflect roof color reference** — `Reflect_123`, used only for the left-side Reflect Mode roof color.
2. **Absorb roof color reference** — `Absorb_456`, used only for the right-side Absorb Mode roof color.
3. **Midday lighting reference** — `Midday_345`, used only for the left-side bright daylight mood.
4. **Dusk lighting reference** — `Dusk_567`, used only for the right-side dusk mood and overall cloud quality if requested.
5. **Dividing curve reference** — `Curve_234`, used only for the organic boundary shape and curve character.

## Output behavior
When this skill is used, return **one clean copy/paste prompt** for an image-generation or image-editing tool. Do not return analysis, options, alternate prompt versions, or explanatory notes unless requested.

The prompt should assume the user will upload the base image and any named reference images to the image-editing tool.

## Core task
Use the supplied house/environment image as the locked base composition. Apply only a split lighting and roof-color treatment.

The final image should show:
- one original house
- one original environment
- one continuous sky
- one organic dividing boundary
- left side in Reflect Mode / midday
- right side in Absorb Mode / dusk

The result should feel like the same real image shown under two environmental states, not two separate images stitched together.

## Base image preservation priority
Treat the supplied house/environment image as the source of truth. The image-editing model should behave as if the full image is locked except for lighting, color temperature, roof color, and the soft window glow on the dusk side.

Preserve:
- house design
- architectural style
- roof shape
- roof pitch
- roof edges
- roof material
- roof profile
- roof pattern
- ridges, valleys, eaves, fascia, gutters, soffits, trim, and overhangs
- walls, siding, stone, stucco, cladding, porch, garage, stairs, railings, windows, and doors
- camera angle and perspective
- crop, framing, and image proportions
- landscape, sky, clouds, horizon, background, and staging environment
- plants, trees, shrubs, rocks, mountains, soil, ground texture, driveway, walkways, and surrounding site details
- realism and photographic integrity

Change only:
- the lighting condition on the left side
- the lighting condition on the right side
- the visible roof color on the left side
- the visible roof color on the right side
- the soft warm interior glow in visible windows on the right side

## Split boundary rules
- Add one organic curvilinear dividing boundary spanning from the top edge to the bottom edge of the composition.
- The boundary should be broad, long, fluid, and gently sculptural.
- The boundary may have a subtle diagonal flow, but it should not feel like a hard vertical split.
- The boundary should be clear enough to communicate the two conditions.
- The boundary should be crisp in the sky, roof, and upper house areas.
- Do not add a visible graphic line, outline, border, halo, glow, seam, white line, black line, or colored line along the boundary.
- The split should be defined only by the change in lighting, color temperature, and roof color.

## Sky and cloud rules
- Preserve one continuous sky across the entire composition.
- Use one unified cloud system from left to right.
- Do not create two different skies.
- Do not create mismatched cloud formations across the boundary.
- Cloud shapes should remain continuous across the split, with only lighting and color temperature changing between sides.
- If a dusk reference image is supplied, use it for cloud shape and cloud quality across the full composition while still preserving the original composition.

## Left side: Reflect Mode / midday
On the left side of the boundary:
- apply bright midday lighting
- keep light direction coming from the left
- add realistic daylight shadows that match the house and site geometry
- keep the scene photorealistic and natural
- change only the visible roof surfaces on the left side to Reflect Mode coloring
- use the Reflect roof color reference if supplied
- if no Reflect reference is supplied, use a light, slightly warm gray family such as soft mineral gray, pale stone gray, or subtle taupe-gray undertones

## Right side: Absorb Mode / dusk
On the right side of the boundary:
- apply dusk lighting
- keep the directional logic consistent with the overall image
- soften or remove strong shadows
- shift the color temperature toward warm dusk light
- change only the visible roof surfaces on the right side to Absorb Mode coloring
- use the Absorb roof color reference if supplied
- if no Absorb reference is supplied, use a deep warm charcoal family such as warm charcoal, dark graphite, or subtle smoked-bronze undertones
- add a soft, warm interior glow to visible windows
- keep the window glow subtle and realistic, not theatrical or overexposed

## Roof preservation rules
- Preserve the roof material identity exactly as it exists in the original image.
- Change roof color only.
- Do not change the roof material, profile, pattern, relief, tile shape, panel spacing, seams, shingles, or texture.
- Do not add standing-seam lines, shingles, barrel tiles, vents, skylights, chimneys, solar panels, antennas, or new roof objects.
- Do not flatten, redraw, simplify, or replace the roof geometry.
- The Reflect and Absorb colors should follow the existing roof planes, shadows, perspective, and material texture.

## Environmental preservation rules
- Preserve the exact environment already present in the image.
- Do not regenerate, beautify, simplify, expand, replace, or reinterpret the landscape, sky, ground, vegetation, background, or lighting structure.
- Do not add new landscaping, plants, trees, rocks, pathways, fences, roads, vehicles, people, clouds, haze, mountains, structures, or environmental props.
- Do not remove existing environmental details.
- Do not change the camera angle, lens, crop, framing, scale, or house placement within the scene.
- Do not make the background more dramatic, more polished, more cinematic, or more stylized.

## Important constraints
- Do not redesign the house.
- Do not alter the architecture.
- Do not regenerate the landscape.
- Do not change the roof type or roof pattern.
- Do not create two different skies.
- Do not create mismatched cloud formations across the boundary.
- Do not add text, icons, people, labels, arrows, decorative elements, borders, diagrams, or collage elements.
- Do not make the transition feel graphic, artificial, posterized, or like a filter overlay.
- Do not make the roof look newly textured or materially different.
- Do not apply Reflect Mode or Absorb Mode colors to walls, trim, windows, landscape, ground, driveway, sky, plants, rocks, or background.

## Success criteria
A successful output:
- looks photorealistic
- preserves the original house and environment
- clearly communicates Sora’s dual-mode behavior
- feels like one image under two environmental states
- has a smooth, elegant, organic split
- uses one continuous sky and cloud system
- keeps the roof type, material, and pattern intact while changing only color
- avoids AI artifacts, pasted-on color, environmental regeneration, and graphic seams

## Paste-ready prompt scaffold
Use the supplied house/environment image as the locked base image. Apply only Sora’s divided lighting and roof-color treatment. Preserve the original image as much as possible. Do not redesign, regenerate, restyle, replace, improve, expand, or reinterpret the house, architecture, roof geometry, roof material, roof pattern, landscape, sky, background, camera angle, composition, crop, framing, or realism.

Create one organic curvilinear dividing boundary that spans from the top edge to the bottom edge of the composition. The boundary should be broad, fluid, gently sculptural, and slightly natural in its curve. It should clearly separate the two environmental states, but it must not appear as a graphic line or stroke. Do not add any visible outline, border, glow, halo, seam, white line, black line, or colored line.

Keep one continuous sky across the whole composition. Use one unified cloud structure from left to right so the image feels like a single real photograph. The cloud forms should remain continuous across the boundary, with only the lighting and color temperature changing between sides. Do not create two different skies or mismatched cloud formations.

On the left side of the boundary, apply bright midday lighting with light coming from the left. Add realistic daylight shadows that match the house, roof planes, landscape, and site geometry. Change only the visible roof surfaces on the left side to Reflect Mode coloring. If a Reflect roof color reference is supplied, use it only for the roof color on the left side. If no Reflect reference is supplied, use a light, slightly warm gray roof color such as soft mineral gray, pale stone gray, or subtle taupe-gray.

On the right side of the boundary, apply warm dusk lighting with softened or removed strong shadows. Change only the visible roof surfaces on the right side to Absorb Mode coloring. If an Absorb roof color reference is supplied, use it only for the roof color on the right side. If no Absorb reference is supplied, use a deep warm charcoal roof color such as warm charcoal, dark graphite, or subtle smoked-bronze. Add a soft, warm, realistic interior glow to visible windows on the dusk side only.

Preserve the existing roof material identity exactly. Change roof color only. Do not change the roof type, profile, texture, pattern, relief, seams, shingles, tiles, panel spacing, edges, ridges, valleys, pitch, eaves, fascia, gutters, soffits, trim, or overhangs. Do not add standing-seam lines, shingles, tiles, vents, skylights, chimneys, solar panels, antennas, or any new roof objects.

Treat every part of the image outside the lighting and roof-color transition as locked. Preserve the same house design, walls, siding, stone, stucco, cladding, porch, garage, stairs, railings, windows, doors, trim, landscape, sky, clouds, horizon, plants, trees, shrubs, rocks, mountains, driveway, walkways, soil, ground texture, camera angle, perspective, lens, crop, framing, scale, and overall composition.

The final result should look like the same original photorealistic house in the same real environment, shown in two environmental states: midday / Reflect Mode on the left and dusk / Absorb Mode on the right. Do not add text, icons, labels, people, arrows, diagrams, decorative elements, borders, product-reference-sheet elements, or graphic overlays. Do not make the transition artificial, posterized, theatrical, overly cinematic, or like two separate images stitched together.
