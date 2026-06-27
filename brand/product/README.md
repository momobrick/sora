# Sora Product Guidance

This folder defines the product accuracy layer for Sora’s responsive roofing system. Use these files whenever Sora’s product behavior, roof modes, material profiles, roof zones, homeowner controls, visual transitions, or product claims are described.

The goal of this folder is to keep Sora grounded, believable, and consistent. Sora should always be represented as a responsive roofing material installed as the home’s exterior roof surface — not as a coating, gadget, solar panel, mechanical roof, or sci-fi transformation.

## What This Folder Is For

Use the `product/` folder when creating or reviewing:

- product descriptions
- product captions and callouts
- image-generation prompts
- campaign concepts
- website or presentation copy
- diagrams or product explainers
- claims about how Sora works
- any visual representation of roof behavior

## Product Files

| File | Role |
|---|---|
| `responsive-roofing-system.md` | Defines Sora’s core product category, system components, primary function, homeowner experience, and practical product framing. |
| `roof-modes.md` | Defines Reflect Mode and Absorb Mode, including temperature logic, threshold behavior, stabilization, and transition language. |
| `roof-profiles.md` | Defines the initial roof profiles — vertical panel, rectangular shingle, and low-profile barrel — and how transitions behave for each. |
| `roof-zones.md` | Defines how roof zones work, how independent and synced behavior should be described, and how zones should appear visually. |
| `roof-control-interface.md` | Defines the simple wall-mounted homeowner control interface, including automatic independent mode, automatic synced mode, and temporary manual override. |
| `product-accuracy-rules.md` | Defines non-negotiable product guardrails, approved language, avoided claims, copy review checks, and image prompt review checks. |

## Recommended Workflow

1. Start with `responsive-roofing-system.md` to understand what Sora is.
2. Use `roof-modes.md` when describing Reflect Mode, Absorb Mode, temperature thresholds, or mode transitions.
3. Use `roof-profiles.md` when the visual form of the roof material matters.
4. Use `roof-zones.md` when describing independent roof sections, sun/shade behavior, synced behavior, or roof-plane-specific response.
5. Use `roof-control-interface.md` when describing homeowner interaction, automatic settings, or manual override.
6. Check `product-accuracy-rules.md` before finalizing copy, prompts, captions, diagrams, or claims.

## Core Product Principles

Sora is the roofing material itself. It is a modular responsive roofing system installed as the exterior roof surface of a home.

Sora responds to roof surface temperature. Weather, sunlight, shade, season, and time of day can influence the roof surface, but they do not directly control the system.

Sora shifts between two modes:

- **Reflect Mode:** a lighter roof state that reflects solar heat and helps reduce heat gain in warmer roof-surface conditions.
- **Absorb Mode:** a darker roof state that absorbs solar heat and helps retain warmth in cooler roof-surface conditions.

Sora’s transition is visual, not mechanical. The roof does not flip, open, lift, rotate, vent, unfold, or reveal a hidden layer. The physical profile, seams, geometry, and installation pattern remain stable.

Sora should feel practical, architectural, residential, and believable. It should not feel like a futuristic gadget, animated screen, glowing surface, or complex smart-home dashboard.

## Key Accuracy Rules

Always describe Sora as:

- a responsive roofing material
- a responsive roofing system
- part of the building envelope
- an exterior roofing material
- a climate-adaptive building material

Do not describe Sora as:

- a coating
- paint
- a film
- an overlay
- a smart-home gadget
- a solar panel or photovoltaic roof
- a mechanical roof system
- a decorative finish
- a roof that predicts the weather
- a replacement for HVAC, insulation, or ventilation

## Transition Direction by Roof Profile

| Roof profile | Correct transition behavior |
|---|---|
| Vertical panel profile | The surface-color transition moves horizontally across the roof zone while the vertical panel rhythm remains stable. |
| Rectangular shingle profile | The surface-color transition moves down the roof zone, following the shingle rows. |
| Low-profile barrel profile | The surface-color transition moves down the roof zone, following the roof slope and barrel profile. |

## Homeowner Control

Sora’s primary behavior is automatic. The homeowner should not be shown as constantly managing the roof.

The roof control interface is a simple interior wall-mounted control point, similar in familiarity to a thermostat. It may allow the homeowner to choose:

- automatic independent mode
- automatic synced mode
- temporary manual override

The interface is secondary to the roof system. It should help homeowners understand and adjust Sora when needed without making the product feel complicated, app-first, or overly technical.

## Prompting Guidance

When prompting Sora imagery, prioritize product accuracy and architectural realism.

Use language like:

> Show a residential home with Sora’s responsive roofing material installed as the exterior roof surface. The roof is in Reflect Mode, using a lighter surface color to reflect solar heat. Preserve the roof profile, seams, geometry, material rhythm, lighting, perspective, and residential realism.

For transitions, specify the correct direction for the roof profile and clarify that the transition is a surface-color shift only.

Avoid language that implies:

- glowing or digital effects
- mechanical movement
- panels flipping or opening
- shingles peeling back
- tiles rotating
- solar power generation
- weather prediction
- a coating applied over an existing roof

## Review Checklist

Before finalizing any Sora product description, caption, prompt, or diagram, confirm:

- Is Sora described as the roofing material itself?
- Does the product respond to roof surface temperature?
- Are Reflect Mode and Absorb Mode described correctly?
- Are roof profiles, seams, zones, and geometry preserved?
- Is the transition visual rather than mechanical?
- Is the correct transition direction used for the selected roof profile?
- Are solar-energy, HVAC-replacement, weather-prediction, and coating claims avoided?
- Does the result feel practical, architectural, calm, and believable?

## Related Brand Files

Use these product files with the broader Sora brand system:

- `../foundation.md`
- `../messaging.md`
- `../voice.md`
- `../lexicon.md`
- `../anti-patterns.md`
- `../creative-direction.md`
- `../surfaces/product-caption.md`
