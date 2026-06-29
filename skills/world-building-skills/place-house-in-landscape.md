# Place House in Landscape

## Purpose
Create a **single, polished, copy/paste-ready prompt** for an AI image generator that places a provided house reference image into a provided landscape reference image.

This skill should produce a prompt the user can paste directly into an image-generation tool **along with the reference images**. The output should read like final image-generation instructions, not like a framework, checklist, or analysis.

## When to use
Use this skill when the user wants to:
- place a house into a landscape
- composite a house image into a new environment
- preserve a house design while changing the setting
- match a house image to a landscape image for a coordinated visual series
- optionally align the result to a third image for camera angle, framing, perspective, roof visibility, or series consistency

## Activation behavior
When this skill file is provided or referenced, **immediately use it to generate the final image-generator prompt** unless required reference-image names are missing.

Do **not** summarize, explain, or analyze the skill unless the user specifically asks. The default behavior is to produce the finished prompt.

Before generating the final prompt, ask the user for the exact names of the reference images so the prompt can be customized to those images.

Ask for:
1. **House reference image name** – the architectural source to preserve
2. **Landscape reference image name** – the environmental source to apply
3. **Composition reference image name** – optional camera/framing guide only

If the user does not want to use a composition reference image, ask them to say **none**.

If the user has already provided the exact reference-image names in the current request, do not ask again. Generate the finished prompt using those names.

If the user has attached images but has not provided their names, ask for the image names before generating the final prompt.

## Required inputs
Ask the user to provide:
1. **House reference image name** – the architectural source to preserve
2. **Landscape reference image name** – the environmental source to apply

Optional:
3. **Composition reference image name** – use only for viewpoint, framing, perspective, scale in frame, roof visibility, and series consistency
4. Any special constraints, such as:
   - architectural features that must remain unchanged
   - desired camera angle
   - lighting conditions
   - desired amount of roof visibility
   - level of environmental realism
   - whether the result should feel like part of a series
   - whether the roof must remain blank, smooth, and unfeatured for a later roof-material step

If the user has already provided the reference-image names or constraints, do not ask again. Generate the finished prompt using the information available.

## Core behavior
When using this skill, return a prompt that:
- can be pasted directly into an AI image generator
- assumes the user will attach or include the relevant reference images
- clearly defines the role of each named reference image
- treats the **house reference image as the architectural source to preserve**
- treats the **landscape reference image as the environmental source to apply**
- treats the **composition reference image**, if provided, only as a camera/framing guide
- uses the exact reference-image names provided by the user throughout the summary and prompt
- strongly protects the house from being redesigned
- integrates the house naturally into the landscape with believable scale, realistic contact with the terrain, subtle ambient occlusion, grading, vegetation blending, neutral lighting, and atmosphere
- uses restrained site-integration details when helpful, such as walkways, mown paths, disturbed soil, and climate-appropriate planting
- defaults to neutral, even, overcast lighting unless the user specifically requests another lighting condition
- protects blank, smooth roofs when the reference image or user request requires an unfeatured roof plane

The final prompt should be written as direct instructions to the image generator.

## Output requirements
Return:
1. A short summary of the reference-image roles using the exact image names provided by the user
2. A single polished prompt under a `### Prompt` heading

The prompt itself should be ready to copy and paste. It should not include placeholder brackets unless a necessary detail is unknown. Avoid explaining why the prompt is written a certain way.

## Prompt-writing rules

### 1) Define image roles clearly
The final prompt must state how each reference image should be used:
- **House reference image** = architectural source to preserve
- **Landscape reference image** = environmental source for terrain, vegetation, atmosphere, horizon, and regional context
- **Composition reference image** = optional source only for camera angle, framing, perspective, scale, roof visibility, and series consistency

Use the exact reference-image names provided by the user whenever identifying these roles.

### 2) Preserve the house design
Explicitly preserve the house’s existing:
- overall design and architectural identity
- massing and proportions
- roof shape, roof pitch, and roof type
- porch layout
- stairs
- columns
- railings
- windows and doors
- material character and finishes
- foundation type, including raised or stilted construction when relevant
- climate-appropriate construction logic

### 3) Apply the landscape realistically
Use the landscape reference image to guide:
- terrain and ground plane
- vegetation type and density
- horizon and background context
- climate and regional cues
- atmosphere and color relationships
- site conditions around the house

The house should look naturally built into the site, not pasted on top of the landscape.

### 4) Integrate perspective and composition
The final prompt should instruct the image generator to align:
- camera height
- angle of view
- perspective
- house scale in frame
- amount of foreground
- roof visibility
- relationship between the house, ground plane, and background

If a composition reference is provided, the prompt should use it only for:
- viewpoint
- framing
- overall compositional rhythm
- series consistency
- diagonal recession of the house in space

### 5) Protect against unwanted regeneration
The final prompt must explicitly say not to:
- redesign the house
- change the architectural style
- replace the roof type
- invent new porches, stairs, railings, windows, or doors
- copy architectural features from the landscape or composition reference image
- copy the landscape from the composition reference image
- over-stylize the result
- make the house look like a different building type

### 6) Use precise integration language
Include language about:
- grounding the house naturally on the site
- matching lighting and atmosphere
- believable scale and placement
- realistic contact with the terrain
- subtle ambient occlusion
- grading around the foundation
- vegetation, grass, and soil blending around the house footprint
- keeping the final image photorealistic and cohesive

Avoid relying on strong shadows as the primary grounding device unless the user specifically requests directional lighting.

### 7) Integrate the house into the site
The final prompt should make the house feel naturally built into the landscape, not pasted on top of it. When appropriate, include restrained site-integration details such as:
- subtle grading around the foundation
- a simple walkway or path leading to the entry
- lightly worn or mown paths in the grass
- small areas of disturbed soil near the house footprint
- modest foundation planting or climate-appropriate foliage
- grass, soil, and vegetation blending naturally around the base of the house

These additions should remain quiet, realistic, and regionally appropriate. They should support the composition without redesigning the house or distracting from the architecture.

### 8) Use neutral overcast lighting by default
Unless the user specifically requests directional sunlight, golden hour, dusk, dramatic lighting, or another named lighting condition, the final prompt should default to neutral, even, overcast lighting.

The prompt should explicitly avoid:
- strong sunlight
- dramatic highlights
- hard cast shadows
- visible or implied directional light sources
- shadows that suggest a specific sun angle

The house should feel grounded through realistic contact with the terrain, subtle ambient occlusion, grading, vegetation, and material blending rather than pronounced shadows. If any shadows are present, they should be extremely soft, minimal, and non-directional.

### 9) Protect blank smooth roofs when relevant
If the house reference image has a blank or smooth roof, or if the user says the roof should remain blank, the final prompt must strongly protect the roof from unwanted material generation.

The prompt should state:
- preserve the roof shape, pitch, and geometry
- keep the roof blank, smooth, clean, and unfeatured
- do not add shingles, seams, tiles, vents, skylights, chimneys, texture, pattern, panel lines, or featured roof material treatment

This is especially important when the image is being prepared for a later step where a separate roof material or roof profile will be applied.

## Default user question when reference-image names are missing
Use this exact question before generating the prompt:

Please send me the exact reference image names for:
1. House reference image
2. Landscape reference image
3. Composition reference image, or say **none**

Once I have those names, I’ll generate the copy/paste-ready image prompt customized to your references.

## Default output structure
Use this structure when generating the final result:

### Summary
- **[House image name]** = house reference image; architecture to preserve
- **[Landscape image name]** = landscape reference image; environment to apply
- **[Composition image name]**, if provided = composition reference image; camera/framing guide only
- Goal = create a photorealistic composite where the house feels naturally built into the landscape with neutral overcast lighting and no directional light source

### Prompt
Use **[House image name]** as the house reference image and architectural source. Preserve the house’s existing design, massing, proportions, roof shape, roof pitch, roof type, porch layout, stairs, railings, columns, windows, doors, materials, foundation type, and overall architectural character.

Use **[Landscape image name]** as the landscape reference image and environmental source. Place the house naturally into that landscape, using the landscape image to guide the terrain, ground plane, vegetation, horizon, background, atmosphere, regional character, and natural color relationships. The house should feel realistically built into the site, with believable scale, realistic contact with the terrain, subtle ambient occlusion, grading around the foundation, vegetation blending, and interaction with the surrounding grass, soil, and landscape.

If **[Composition image name]** is provided as a composition reference image, use it only as a guide for camera angle, framing, perspective, amount of foreground, roof visibility, scale in frame, and overall series consistency. Do not copy the composition reference image’s architecture, materials, porch details, roof design, landscape, vegetation, or background.

Integrate the house fully into the site so it feels genuinely built into the landscape rather than placed on top of it. Add restrained site elements only as needed to improve realism, such as a simple walkway or path leading to the entry, lightly worn or mown paths in the grass, small areas of disturbed soil near the house footprint, modest foundation planting, and climate-appropriate foliage around the base. Keep these additions subtle, natural, regionally appropriate, and secondary to the preserved house design.

Adjust the house placement, scale, and perspective only as needed so it sits convincingly in the landscape. Match the atmosphere and color relationships of the landscape while preserving the original architectural identity of the house. Show an appropriate amount of the roof for the desired angle, but do not redesign the roof or change its type.

Keep the lighting neutral, even, and overcast unless the user specifically requests another lighting condition. Do not create strong sunlight, dramatic highlights, hard cast shadows, or any visible or implied directional light source. The house should feel grounded through realistic contact with the terrain, subtle ambient occlusion, grading, vegetation, and material blending rather than pronounced shadows. If any shadows are present, they should be extremely soft, minimal, and non-directional.

If the house reference image has a blank or smooth roof, or if the user says the roof should remain blank, preserve the roof shape, pitch, and geometry while keeping the roof blank, smooth, clean, and unfeatured. Do not add shingles, seams, tiles, vents, skylights, chimneys, texture, pattern, panel lines, or any featured roof material treatment.

Keep the result photorealistic, calm, natural, and cohesive. The final image should look like a finished architectural photograph of the same house located in the new landscape.

Do **not** redesign the house. Do **not** change the architectural style, roof type, porch layout, stair placement, railing style, window style, door placement, foundation type, or material character. Do **not** add new architectural features unless they are absolutely necessary for realistic site integration. Do **not** copy architecture from the landscape or composition reference images. Only change what is necessary to place the house believably into the landscape.

## Customization notes
When relevant, tailor the final prompt to the specific house and landscape by naming important protected features.

Examples:
- For a beach house: preserve the raised foundation, wraparound porch, white railings, light coastal materials, stairs, columns, and airy coastal character.
- For a mountain cabin: preserve the gabled massing, timber or wood character, cabin proportions, roof shape, chimney if present, and restrained alpine character.
- For a desert house: preserve the stucco walls, simple massing, parapets or low-slope roof geometry if present, and desert-appropriate architectural character.
- For a farmhouse: preserve the simple rural massing, porch forms, restrained detailing, light finishes, and practical farmhouse character.
- For a modern forest house: preserve the clean contemporary massing, natural wood or dark cladding, large windows, simple roof geometry, and restrained detailing.

## Quality bar
A good output from this skill should:
- be a final prompt the user can paste into an image-generation tool
- clearly instruct the user to use the prompt with the attached reference images
- use the exact reference-image names provided by the user
- preserve the original house identity
- place the house convincingly into the new landscape
- integrate the house with realistic grading, pathways, planting, terrain contact, and vegetation blending when appropriate
- default to neutral, even, overcast lighting without a directional light source unless the user requests another lighting condition
- protect blank, smooth roofs when relevant
- maintain photorealism
- avoid architectural drift
- clearly separate the roles of all references
- avoid generic or vague compositing language
