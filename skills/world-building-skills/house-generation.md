# Regional House Study

## Purpose

Generate a generic regional house as a clean architectural study, either:

- in a neutral staging environment, or
- in a photorealistic regional environment

This skill is used to create regionally appropriate houses that support Sora’s later roof compositing and product visualization.

## Use this skill when

- You need a believable generic house for a specific climate region.
- You want a clean source image for later roof compositing.
- You want a consistent architectural angle across multiple house types.
- You need a house that feels regionally appropriate but not overly specific.

## Do not use this skill when

- You want a final split-state Sora image.
- You want a landscape plate with no house.
- You want an exact replica of a reference image.

## Supported house types

- Southwestern desert house
- Rocky Mountain cabin / contemporary mountain home
- Tropical coastal house
- Pacific Northwest forest home

## Shared goals

Each house should be:

- generic
- realistic
- regionally believable
- refined but not overly luxurious
- suitable for later Sora roof visualization

## Shared composition rules

Use:

- elevated front-left three-quarter architectural view
- camera angled slightly downward
- broad roof plane clearly visible
- house receding diagonally from lower left to upper right
- front facade, entry, and primary roof geometry clearly visible

## Shared lighting rules

Use:

- neutral overcast lighting
- crisp even detail
- minimal directional shadow

## Roof rules

The roof must be:

- blank
- clean
- broad and clearly visible
- unobtrusive
- free from material emphasis

Do not include:

- solar panels
- skylights
- vents
- strong roof texture
- decorative roof features

In most cases, do not include chimneys unless specifically appropriate to the house type.

## Output modes

### Mode 1: Neutral staging

Use when you want a clean architectural study.

Include:

- flat matte neutral ground plane
- clean horizontal horizon line
- slightly lighter neutral background above the horizon
- subtle contact shadow only

Do not include:

- landscape
- trees
- mountains
- roads
- scenery
- environmental context

### Mode 2: House in environment

Use when you want the house already placed in a photorealistic regional setting.

The house should be seamlessly integrated into the scene with believable contact shadows, consistent scale, and correct perspective.

## Regional guidance

### Southwestern desert house

Show:

- a generic modern Southwestern residential home
- warm neutral stucco
- simple clean massing
- restrained detailing
- a clearly visible pitched roof
- roof planes that sit above the wall line

Avoid:

- flat roofs
- parapet walls concealing the roof
- luxurious villa styling

### Rocky Mountain cabin

Show:

- a generic contemporary mountain home or modern cabin
- natural wood or wood-and-stone materials
- simple alpine proportions
- clean trim
- restrained rustic character
- large practical windows

### Tropical coastal house

Show:

- an elevated house raised on piers or stilts
- light neutral exterior materials
- deep overhangs
- wraparound or extended porch elements
- railings
- airy coastal character
- broad simple roof form

Avoid:

- resort styling
- overly decorative trim

### Pacific Northwest forest home

Show:

- a refined rustic cabin or forest home
- simple gabled or lodge-like massing
- natural wood or heavy timber
- practical windows and doors
- calm handcrafted character
- restrained contemporary-rustic detailing

Avoid:

- overly themed cabin styling
- excessive rustic ornament

## Reference-image use

A reference image may be used for style only.

Borrow:

- regional architectural character
- general roof form
- massing language
- material family

Do not copy:

- exact composition
- facade layout
- window placement
- door placement
- porch layout
- stairs
- lighting
- landscaping
- camera angle
- exact architectural design

## Guardrails

- Keep the house generic, not iconic.
- Preserve regional believability.
- Keep the roof visually simple and usable for later Sora treatment.
- Do not let the environment overpower the house.
- Do not introduce unnecessary objects or decorative clutter.
- Avoid making the architecture too luxurious, themed, or stylized.

## Success criteria

A successful output:

- clearly fits the specified region
- reads as believable residential architecture
- uses the standard Sora viewpoint
- keeps the roof visible and compositing-friendly
- feels controlled, clear, and consistent across a series

## Prompt scaffold

Generate a generic [REGION] residential home. Use the provided reference image for house style only. Borrow the regional architectural character, roof form, and general material language, but do not copy the exact layout, facade, composition, window placement, door placement, porch design, lighting, or setting.

Show a house that feels [REGION-SPECIFIC CHARACTER], realistic, and regionally appropriate rather than overly decorative or highly stylized.

Use an elevated front-left three-quarter architectural view, with the camera angled slightly downward so the broad roof plane is clearly visible and compositionally important. The home should recede diagonally from lower left to upper right. Keep the front facade, entry, and primary roof geometry clearly visible.

Use neutral overcast lighting for crisp, even detail and minimal directional shadow.

Keep the roof blank and clean, with no visible roofing pattern, no featured material treatment, no solar panels, no skylights, and no vents. Keep the roof plane simple, broad, and uninterrupted.

[IF NEUTRAL STAGING MODE]
Place the home in a minimal neutral architectural staging environment. Use a flat matte neutral ground plane, a clean horizontal horizon line, and a slightly lighter neutral background above the horizon to suggest sky. Do not include environmental context.

[IF HOUSE IN ENVIRONMENT MODE]
Place the home in a photorealistic [REGIONAL ENVIRONMENT] setting with believable integration, natural scale, and consistent perspective.

Do not include people, text, signage, vehicles, or distracting nonessential objects.
