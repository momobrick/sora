# Apply Sora Shingle Profile to Home

## Purpose
Generate a paste-ready image-editing prompt that applies the Sora shingle roof profile shown in the reference image `sora-shingle_456` to a supplied home image.

Use this skill to transform only the roof surface of an existing home image into the Sora shingle roof system, while preserving the home, architecture, roof geometry, scene, lighting, camera angle, background, and realism.

This skill works for either:
- an isolated home image with a blank, plain, simplified, or replaceable roof surface
- a finished house-in-environment composite where the landscape, sky, lighting, and background must remain locked and accurate

## Use this skill when
- You have a supplied home image with a blank, plain, simplified, or replaceable roof surface.
- The home may already be placed in a realistic environment, such as desert, forest, mountain, coast, farmland, or neighborhood setting.
- You have the Sora shingle reference image named `sora-shingle_456`.
- You want the home image to keep its original architecture, environment, perspective, lighting, and camera angle.
- You want the roof to receive the rectangular shingle profile, staggered courses, shallow lapped edges, sculptural wave relief, fine striated texture, and medium neutral gray material quality seen in `sora-shingle_456`.

## Do not use this skill when
- You want to generate a house from scratch.
- You want to place a house into a new landscape.
- You want to change the house style, roof shape, roof pitch, or roofline.
- You want to change, improve, replace, extend, or reinterpret the background environment.
- You want to apply Sora vertical panels, barrel tile, or another roof profile.
- You want to apply Reflect Mode or Absorb Mode split-color treatment.

## Required inputs
1. **Home image** — the base image to edit. This may be an isolated house or a house already composited into an environment.
2. **Material reference image** — `sora-shingle_456`, used only as the roof material/profile reference.

## Output behavior
When this skill is used, return **one clean copy/paste prompt** for an image-generation or image-editing tool. Do not return analysis, options, or multiple prompt versions unless requested.

## Core task
Use the supplied home image as the locked base composition. Apply the Sora shingle roof system from `sora-shingle_456` only to the visible roof planes of the home.

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
- the rectangular shingle profile
- the staggered course layout
- the shallow lapped edges and tile thickness
- the low-relief flowing wave texture on each shingle
- the fine directional striations
- the roof color only when needed to match the medium neutral gray material shown in `sora-shingle_456`

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

## How to interpret `sora-shingle_456`
Use `sora-shingle_456` as a material and profile reference, not as a composition reference.

The roof material should include:
- rectangular shingle construction
- staggered shingle courses with believable overlap
- subtle raised edges and shallow individual shingle thickness
- medium neutral gray color
- low-sheen architectural finish, not glossy or mirror-like
- subtle sculptural wave bands flowing across the face of each shingle
- fine striations that follow the curves of the wave bands
- shallow molded relief with readable depth
- realistic highlights and shadows caused by the shingle laps, edges, and surface relief

The shingle system should feel durable, buildable, architectural, and integrated into the roof plane.

## Application rules
- Apply the Sora shingles to every visible roof plane that should receive roofing.
- Lay the shingles in horizontal courses across each roof plane, with rows stacking from eave toward ridge according to the roof perspective.
- Keep shingle sizing, spacing, and overlap consistent and believable across each roof plane.
- Allow the shingle layout to wrap naturally across different roof planes without flattening the roof or changing its geometry.
- The staggered joints should follow the perspective of the roof plane and should not drift diagonally in ways that fight the roof angle.
- The wave relief should sit on the face of each individual shingle.
- The Sora material signature should remain clearly visible, especially on larger roof planes, without becoming exaggerated or decorative.
- Fine striations must follow the flow of the wave bands, not appear as random noise or generic scratches.
- Preserve any existing roof intersections, ridges, valleys, and edges.
- Preserve fascia, gutters, soffits, underside trim, and overhangs as original non-roof elements; do not apply the shingle material to them.
- Preserve any existing roof objects only if they are already in the home image; do not add new chimneys, skylights, vents, solar panels, antennas, or decorative roof objects.

## Pattern behavior
The Sora wave texture should repeat or continue within each individual shingle. It should not behave like one oversized graphic stretched across the entire roof.

Avoid:
- one continuous wave image spanning across multiple shingles and courses
- perfectly identical repeated waves in every shingle
- waves that ignore the roof perspective
- striations that run straight when the wave bands curve
- printed or painted pattern effects
- excessive contrast or overly deep relief
- making the shingle pattern so faint that the Sora surface signature disappears

## Color handling
Default color handling: match the medium neutral gray shingle material shown in `sora-shingle_456`, adjusted naturally to the home image’s existing lighting and shadows.

If the user specifically asks to preserve the original roof color, apply only the physical shingle profile, wave relief, and striated texture while keeping the original roof color.

Do not apply Reflect Mode or Absorb Mode coloration unless specifically requested in a separate task.

## Important constraints
- Do not redesign the house.
- Do not regenerate the landscape, sky, background, ground, driveway, vegetation, mountains, or lighting.
- Do not change the camera angle or crop.
- Do not change the roof pitch, silhouette, ridge line, eaves, fascia, gutters, soffits, trim, or roof edges.
- Do not add new architectural features.
- Do not turn the roof into a reference-sheet object or product render.
- Do not paste the `sora-shingle_456` reference image onto the roof as a flat texture.
- Do not create labels, text, arrows, borders, panels, diagrams, or a collage.
- Do not make the material overly futuristic, decorative, plastic, wet, reflective, or metallic in a flashy way.
- Do not flatten the shingle edges or lose the individual course depth.
- Do not allow the roof material to spill onto walls, windows, siding, fascia, gutters, soffits, trim, ground, sky, driveway, plants, rocks, or landscape.

## Success criteria
A successful result:
- looks like the original supplied home image with only the roof material changed
- preserves the existing background and site conditions accurately
- clearly reads as a realistic rectangular shingle roof system
- matches the Sora shingle characteristics in `sora-shingle_456`
- preserves believable roof geometry and perspective
- shows staggered courses, individual shingle edges, subtle flowing wave relief, and fine striations
- keeps the Sora surface signature visible but architectural
- feels buildable, durable, and architecturally integrated
- avoids pasted-on texture, decorative patterning, environmental regeneration, or AI artifact repetition

## Paste-ready prompt scaffold
Use the supplied home image as the locked base image. Use the reference image named `sora-shingle_456` only as the roof material and profile reference.

Apply the Sora shingle roof system from `sora-shingle_456` to the visible roof planes of the home. Replace only the existing blank roof surface with realistic rectangular shingles: staggered horizontal courses, shallow lapped edges, subtle individual shingle thickness, low-relief flowing wave bands on each shingle, and fine striations that follow the curves of the wave bands. Match the medium neutral gray, low-sheen architectural material quality shown in `sora-shingle_456`, adjusted naturally to the existing lighting and shadows of the home image.

Preserve the original home image as much as possible. Treat every part of the image outside the roof planes as locked. Keep the same house design, roof shape, pitch, ridges, valleys, eaves, fascia, gutters, soffits, underside trim, overhangs, roof edges, camera angle, perspective, crop, framing, lighting, shadows, landscape, sky, clouds, horizon, background, plants, shrubs, trees, rocks, mountains, driveway, walkways, soil, ground texture, siding, windows, doors, porch, garage, trim, and all non-roof architecture. The shingle courses should follow the perspective and slope of each roof plane so the roofing looks physically installed, not pasted on.

The wave texture should live within the face of each individual shingle and should not span unrealistically across the entire roof as one oversized graphic. Keep the relief shallow, sculptural, durable, and material-based. Make the Sora wave and striated surface signature clearly visible without becoming overly deep, high-contrast, decorative, or printed. Make the roof look like a believable real shingle roofing system inspired by `sora-shingle_456`.

Do not redesign or regenerate the house, roof geometry, landscape, sky, background, ground, driveway, vegetation, mountains, camera angle, crop, or lighting. Do not apply the roof material to fascia, gutters, soffits, underside trim, walls, windows, siding, ground, driveway, sky, plants, rocks, or landscape. Do not add solar panels, skylights, vents, chimneys, antennas, labels, text, borders, diagrams, or product-reference-sheet elements. Do not apply Reflect Mode or Absorb Mode coloration. Do not make the roof glossy, wet, overly futuristic, decorative, plastic, or like a printed 2D pattern.
