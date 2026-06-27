# Product Accuracy Rules

## Purpose

This file defines the non-negotiable product accuracy rules for writing, prompting, reviewing, and presenting Sora.

Use this file to prevent Sora from being described as a coating, solar product, smart-home gadget, mechanical roof, or unrealistic sci-fi material.

## Core Product Rules

### 1. Sora is the roofing material itself.

Sora is a responsive roofing system made up of modular roofing materials installed as the home's exterior roof surface.

Do not describe Sora as:

- a coating
- paint
- a finish
- a film
- an overlay
- a spray-on treatment
- an add-on applied to an existing roof surface

### 2. Sora is part of the building envelope.

Sora should be understood as an exterior roofing material that forms part of the home's building envelope.

Do not describe Sora as:

- a standalone device
- a decorative accessory
- a smart-home gadget
- a consumer electronics product
- an app-first product

### 3. Sora responds to roof surface temperature.

The product responds to the surface temperature of the roof, not directly to the weather.

Do not describe the mode change as being directly controlled by:

- outdoor air temperature
- the forecast
- time of day
- season
- sunlight alone
- cloud cover alone
- homeowner routines

Acceptable framing:

- Weather conditions influence the roof surface.
- The roof mode is determined by what the roof is physically experiencing at the surface level.

### 4. Sora has two modes.

Sora shifts between:

- reflect mode
- absorb mode

Reflect mode uses a lighter surface color to reflect solar heat and help reduce heat gain.

Absorb mode uses a darker surface color to absorb solar heat and help retain warmth.

Do not add extra modes unless they are explicitly defined in future product development.

### 5. Sora uses a buffered threshold.

The central transition point is 60°F / 15.6°C.

For clearer behavior:

- Reflect mode may trigger above 62°F / 16.7°C roof surface temperature.
- Absorb mode may trigger below 58°F / 14.4°C roof surface temperature.
- Between 58°F and 62°F / 14.4°C and 16.7°C, the roof remains in its current mode.

Do not describe the roof as switching constantly at exactly 60°F.

### 6. Sora includes a stabilization period.

After switching modes, each roof zone remains in its current mode for a defined stabilization period before switching again.

The exact stabilization period is not defined in v1 and may be refined in future product development.

Do not invent a specific duration unless a future source defines one.

### 7. The transition is visual, not mechanical.

Sora's mode change appears as a wave-like surface-color transition.

The roof does not:

- flip
- open
- lift
- vent
- unfold
- expand
- contract
- rotate
- mechanically move
- reveal a hidden layer

### 8. Roof profiles remain physically stable.

The roof profile, installation pattern, seams, sections, and structure remain consistent in both modes.

Do not change the roof type during mode transitions.

For example:

- vertical panels remain vertical panels
- rectangular shingles remain rectangular shingles
- low-profile barrel tiles remain low-profile barrel tiles

### 9. Transition direction depends on roof profile.

Use the correct direction:

- Vertical panel profile: transition moves horizontally across the roof zone.
- Rectangular shingle profile: transition moves down the roof zone.
- Low-profile barrel profile: transition moves down the roof zone.

### 10. Sora is separate from solar energy generation.

Sora reflects or absorbs solar heat. It does not generate electricity as part of the initial product.

Do not describe Sora as:

- solar panels
- photovoltaic roofing
- a power generator
- an energy storage system
- a roof battery

Future solar integration may be discussed only as a clearly labeled future possibility.

### 11. Sora supports comfort and efficiency, but does not replace building systems.

Sora may help improve comfort and reduce some heating or cooling demand.

Do not claim that Sora eliminates the need for:

- heating
- cooling
- insulation
- ventilation
- HVAC systems
- other building envelope strategies

### 12. Sora should feel practical, not sci-fi.

Sora is innovative, but the experience should feel calm, useful, and believable.

Avoid descriptions that make the product feel:

- magical
- futuristic in a gimmicky way
- digital
- glowing
- animated like a screen
- alien
- overly technical
- intimidating

### 13. The roof control interface is simple and secondary to automatic behavior.

Sora's roof control interface is an interior wall-mounted control point for selecting automatic independent mode, automatic synced mode, or temporary manual override.

The interface should feel similar in familiarity to a thermostat and should support simple homeowner understanding.

Do not describe the interface as:

- the primary product
- an app-first smart-home device
- a complex control dashboard
- a weather-prediction system
- a panel-by-panel roof controller
- a replacement for HVAC controls

The roof remains the primary product. The interface is the homeowner interaction layer.

## Approved Product Language

Use:

- responsive roofing material
- responsive roofing system
- roof surface temperature
- reflect mode
- absorb mode
- roof zone
- automatic independent mode
- automatic synced mode
- manual override
- roof control interface
- wall-mounted interface
- surface-color transition
- wave-like transition
- building envelope
- exterior roofing material
- climate-adaptive building material

Use carefully:

- smart: only if needed, and not as the primary descriptor
- adaptive: acceptable when paired with practical product behavior
- solar: only when referring to solar heat, not electricity generation
- future integration: only when clearly labeled as future-facing

Avoid:

- smart roof gadget
- color-changing paint
- roof coating
- solar roof
- photovoltaic material
- power-generating roof
- mechanical roof
- animated roof
- shape-shifting roof
- climate-control device
- complex smart-home dashboard
- weather-prediction panel
- roof skin unless clearly contextualized and not confusing

## Copy Review Checklist

Before approving Sora product copy, confirm:

- Does it describe Sora as the roofing material itself?
- Does it avoid coating, paint, film, or add-on language?
- Does it state that the roof responds to surface temperature?
- Does it correctly distinguish reflect mode and absorb mode?
- Does it avoid claiming that Sora replaces HVAC, insulation, or ventilation?
- Does it avoid claiming that Sora generates electricity?
- Does it sound practical, calm, and believable?
- Does it avoid sci-fi, glowing, or mechanical transformation language?
- If the roof control interface is mentioned, does it feel simple, residential, and secondary to automatic roof behavior?

## Image Prompt Review Checklist

Before approving Sora image prompts, confirm:

- Does the prompt preserve the roof profile and physical structure?
- Does the prompt describe a surface-color change rather than mechanical movement?
- Does the prompt use the correct transition direction for the selected profile?
- Does the prompt avoid glowing, digital, screen-like, or sci-fi effects?
- Does the prompt avoid adding solar panels unless future solar integration is explicitly requested?
- Does the prompt avoid changing the roof type, pattern, seams, or geometry?
- Does the image still look like a real residential roof?
- Does the product feel integrated into the home and environment?

## Product Claim Guardrails

Sora can claim:

- helps homes adapt to changing roof surface conditions
- supports comfort and energy efficiency
- helps reduce unwanted heat gain in warm conditions
- helps retain warmth in cooler conditions
- responds automatically to roof surface temperature
- gives homeowners simple control when needed

Sora should not claim:

- eliminates heating or cooling costs
- replaces HVAC
- guarantees lower energy bills
- generates electricity
- stores energy
- predicts weather
- responds directly to the forecast
- works like solar panels
- transforms mechanically
- can be applied to any existing roof as a coating

## Related Files

- `responsive-roofing-system.md`
- `roof-modes.md`
- `roof-profiles.md`
- `roof-zones.md`
- `../messaging.md`
- `../anti-patterns.md`
- `../visual/material-language.md`
