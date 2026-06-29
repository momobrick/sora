# Apply Sora Barrel Profile to Home

## Purpose
Generate a paste-ready image-editing prompt that applies the Sora barrel roof profile shown in the reference image `sora-barrel_456` to a supplied home image.

Use this skill to transform only the roof surface of an existing home image into the Sora barrel tile roof system, while preserving the home, architecture, roof geometry, scene, lighting, camera angle, background, and realism.

This skill works for either:
- an isolated home image with a blank, plain, simplified, or replaceable roof surface
- a finished house-in-environment composite where the landscape, sky, lighting, and background must remain locked and accurate

## Use this skill when
- You have a supplied home image with a blank, plain, simplified, or replaceable roof surface.
- The home may already be placed in a realistic environment, such as desert, forest, mountain, coast, farmland, or neighborhood setting.
- You have the Sora barrel reference image named `sora-barrel_456`.
- You want the home image to keep its original architecture, environment, perspective, lighting, and camera angle.
- You want the roof to receive the rounded barrel tile profile, repeating curved channels, lapped rows, sculptural wave relief, fine striated texture, and charcoal gray material quality seen in `sora-barrel_456`.

## Do not use this skill when
- You want to generate a house from scratch.
- You want to place a house into a new landscape.
- You want to change the house style, roof shape, roof pitch, or roofline.
- You want to change, improve, replace, extend, or reinterpret the background environment.
- You want to apply Sora vertical panels, shingles, or another roof profile.
- You want to apply Reflect Mode or Absorb Mode split-color treatment.

## Required inputs
1. **Home image** — the base image to edit. This may be an isolated house or a house already composited into an environment.
2. **Material reference image** — `sora-barrel_456`, used only as the roof material/profile reference.

## Output behavior
When this skill is used, return **one clean copy/paste prompt** for an image-generation or image-editing tool. Do not return analysis, options, or multiple prompt versions unless requested.

## Core task
Use the supplied home image as the locked base composition. Apply the Sora barrel tile roof system from `sora-barrel_456` only to the visible roof planes of the home.

The edit should preserve:
- house design
- roof shape
- roof pitch
- roof edges
- ridges, valleys, eaves, fascia, gutters, soffits, trim, and overhangs
- perspective and camera angle
- crop, framing, and image proportions
- lighting, shadows, and weather conditions
- landscape, sky, horizon, background, and staging environment
- plants, trees, shrubs, rocks, mountains, ground texture, driveway, walkways, and surrounding site details
- windows, doors, siding, walls, porch, garage, trim, and all non-roof architecture

The edit should change only:
- the visible roof surface material
- the rounded barrel tile profile
- the repeating curved tile channels
- the lapped rows and tile depth
- the low-relief flowing wave texture on the curved tile surfaces
- the fine directional striations
- the roof color only when needed to match the charcoal gray material shown in `sora-barrel_456`

## Base image preservation priority
Treat the supplied home image as the source of truth. The image-editing model should behave as if the entire image is locked except for the blank roof planes that receive the new roofing material.

If the home is already in an environment, preserve the environment exactly. Do not regenerate, beautify, simplify, expand, replace, or reinterpret the landscape, sky, ground, vegetation, background, or lighting.

If the editing tool supports masking, mask only the visible roof planes and leave everything outside the roof mask unchanged.

## Environmental preservation rules
When the base image already includes a background or landscape:
- Preserve the exact environment already present in the image.
- Preserve the same sky, clouds, horizon line, mountains, hills, trees, plants, shrubs, grasses, rocks, driveway, walkways, soil, ground texture, and background depth.
- Preserve the existing lighting quality, weather, time of day, shadow softness, color temperature, and atmospheric conditions.
- Do not add new landscaping, plants, trees, rocks, pathways, fences, roads, vehicles, people, clouds, haze, mountains, structures, or environmental props.
- Do not remove existing environmental details.
- Do not change the camera angle, lens, crop, framing, scale, or house placement within the scene.
- Do not make the background more dramatic, more polished, more cinematic, or more stylized.
- The new roof material should adapt to the existing scene lighting, but the scene lighting itself should not change.

## How to interpret `sora-barrel_456`
Use `sora-barrel_456` as a material and profile reference, not as a composition reference.

The roof material should include:
- rounded barrel tile construction
- repeating half-round curved tiles or channels running with the roof slope
- overlapping courses with believable lap shadows
- charcoal gray color
- low-sheen architectural finish, not glossy or mirror-like
- subtle sculptural wave bands wrapping over the curved tile surfaces
- fine striations that follow the curves of the wave bands and the tile curvature
- shallow molded relief with readable depth
- realistic highlights and shadows caused by the rounded barrel geometry, tile overlaps, and surface relief

The barrel tile system should feel durable, buildable, architectural, and integrated into the roof plane.

## Application rules
- Apply the Sora barrel tile system to every visible roof plane that should receive roofing.
- Align the repeating barrel channels with the roof slope, running from ridge toward eave according to the perspective of each roof plane.
- Keep tile spacing, channel width, overlap, and depth consistent and believable across each roof plane.
- Allow the tile layout to wrap naturally across different roof planes without flattening the roof or changing its geometry.
- The barrel rows should follow the actual roof angles and perspective so the channels look installed on the roof, not diagonal or pasted over the image.
- The wave relief should wrap across the curved barrel surfaces and respond to the rounded form.
- The Sora material signature should remain clearly visible, especially on larger roof planes, without becoming exaggerated or decorative.
- Fine striations must follow the flow of the wave bands, not appear as random noise or generic scratches.
- Preserve any existing roof intersections, ridges, valleys, and edges.
- Preserve fascia, gutters, soffits, underside trim, and overhangs as original non-roof elements; do not apply the barrel material to them.
- Preserve any existing roof objects only if they are already in the home image; do not add new chimneys, skylights, vents, solar panels, antennas, or decorative roof objects.

## Pattern behavior
The Sora wave texture should repeat or continue within each barrel tile surface. It should not behave like one oversized graphic stretched across the entire roof.

Avoid:
- one continuous wave image spanning across all barrel channels and courses
- perfectly identical repeated waves in every tile
- waves that ignore the roof perspective or rounded tile curvature
- striations that run straight when the wave bands curve
- printed or painted pattern effects
- excessive contrast or overly deep relief
- making the barrel pattern so faint that the Sora surface signature disappears

## Color handling
Default color handling: match the charcoal gray barrel tile material shown in `sora-barrel_456`, adjusted naturally to the home image’s existing lighting and shadows.

If the user specifically asks to preserve the original roof color, apply only the physical barrel tile profile, wave relief, and striated texture while keeping the original roof color.

Do not apply Reflect Mode or Absorb Mode coloration unless specifically requested in a separate task.

## Important constraints
- Do not redesign the house.
- Do not regenerate the landscape, sky, background, ground, driveway, vegetation, mountains, or lighting.
- Do not change the camera angle or crop.
- Do not change the roof pitch, silhouette, ridge line, eaves, fascia, gutters, soffits, trim, or roof edges.
- Do not add new architectural features.
- Do not turn the roof into a reference-sheet object or product render.
- Do not paste the `sora-barrel_456` reference image onto the roof as a flat texture.
- Do not create labels, text, arrows, borders, panels, diagrams, or a collage.
- Do not make the material overly futuristic, decorative, plastic, wet, reflective, or metallic in a flashy way.
- Do not flatten the barrel forms or lose the rounded tile depth.
- Do not allow the roof material to spill onto walls, windows, siding, fascia, gutters, soffits, trim, ground, sky, driveway, plants, rocks, or landscape.

## Success criteria
A successful result:
- looks like the original supplied home image with only the roof material changed
- preserves the existing background and site conditions accurately
- clearly reads as a realistic rounded barrel tile roof system
- matches the Sora barrel tile characteristics in `sora-barrel_456`
- preserves believable roof geometry and perspective
- shows rounded barrel channels, overlapping courses, subtle flowing wave relief, and fine striations
- keeps the Sora surface signature visible but architectural
- feels buildable, durable, and architecturally integrated
- avoids pasted-on texture, decorative patterning, environmental regeneration, or AI artifact repetition

## Paste-ready prompt scaffold
Use the supplied home image as the locked base image. Use the reference image named `sora-barrel_456` only as the roof material and profile reference.

Apply the Sora barrel tile roof system from `sora-barrel_456` to the visible roof planes of the home. Replace only the existing blank roof surface with realistic rounded barrel tiles: repeating curved channels running from ridge toward eave, overlapping tile courses, believable lap shadows, low-relief flowing wave bands wrapping over the curved tile surfaces, and fine striations that follow the curves of the wave bands. Match the charcoal gray, low-sheen architectural material quality shown in `sora-barrel_456`, adjusted naturally to the existing lighting and shadows of the home image.

Preserve the original home image as much as possible. Treat every part of the image outside the roof planes as locked. Keep the same house design, roof shape, pitch, ridges, valleys, eaves, fascia, gutters, soffits, underside trim, overhangs, roof edges, camera angle, perspective, crop, framing, lighting, shadows, landscape, sky, clouds, horizon, background, plants, shrubs, trees, rocks, mountains, driveway, walkways, soil, ground texture, siding, windows, doors, porch, garage, trim, and all non-roof architecture. Align the barrel channels according to the perspective and slope of each roof plane so the roofing looks physically installed, not pasted on or angled incorrectly.

The wave texture should wrap over the curved face of each barrel tile and should not span unrealistically across the entire roof as one oversized graphic. Keep the relief shallow, sculptural, durable, and material-based. Make the Sora wave and striated surface signature clearly visible without becoming overly deep, high-contrast, decorative, or printed. Make the roof look like a believable real barrel tile roofing system inspired by `sora-barrel_456`.

Do not redesign or regenerate the house, roof geometry, landscape, sky, background, ground, driveway, vegetation, mountains, camera angle, crop, or lighting. Do not apply the roof material to fascia, gutters, soffits, underside trim, walls, windows, siding, ground, driveway, sky, plants, rocks, or landscape. Do not add solar panels, skylights, vents, chimneys, antennas, labels, text, borders, diagrams, or product-reference-sheet elements. Do not apply Reflect Mode or Absorb Mode coloration. Do not make the roof glossy, wet, overly futuristic, decorative, plastic, or like a printed 2D pattern.
