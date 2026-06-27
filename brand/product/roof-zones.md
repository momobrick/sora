# Roof Zones

## Purpose

This file defines how Sora roof zones work, how they should be described, and how zone behavior should appear in product storytelling and image prompts.

## Zone Definition

A roof zone is a defined area of the roof that can sense and respond as a unit.

Zones allow different parts of the roof to respond to different roof surface temperatures based on site-specific conditions.

## How Zones Are Defined

Zones are customized to each home's roof condition and installation layout.

Zone definition may account for:

- roof shape
- roof slope
- roof orientation
- roof profile
- installation layout
- sun exposure
- shade
- roof angle
- site-specific surface temperature differences

Zones should feel architectural and practical. They should follow believable roof geometry rather than arbitrary graphic divisions.

## Automatic Independent Mode

In automatic independent mode, each defined roof zone responds to its own surface temperature and switches independently.

This allows different areas of the same roof to be in different modes at the same time.

Example:

A roof plane exposed to direct sun may warm above the reflect-mode trigger temperature and shift into reflect mode, while a shaded roof plane remains below the absorb-mode trigger temperature and stays in absorb mode.

Use automatic independent mode when communicating:

- adaptive precision
- site-specific response
- different sun and shade conditions across one roof
- practical climate responsiveness
- roof behavior that follows real surface conditions

## Automatic Synced Mode

In automatic synced mode, all roof zones respond together as one unified roof system.

When synced mode is selected, the roof shifts into the same mode at the same time rather than allowing each zone to respond independently.

Use automatic synced mode when communicating:

- a more unified appearance
- simpler roof-wide behavior
- homeowner preference
- consistent visual presentation
- a coordinated whole-roof transition

The wave-like transition may still move across or down the roof as a coordinated whole, depending on the selected roof profile.

## Manual Override Mode

In manual override mode, the homeowner temporarily selects the preferred mode, overriding automatic behavior.

Manual override may be useful for:

- personal comfort preferences
- maintenance
- unusual weather patterns
- testing
- specific household needs

Manual override should be presented as a simple control feature accessed through the roof control interface, not as the primary way Sora works.

## Zone Transition Behavior

When a roof zone crosses the transition threshold and completes the stabilization requirement, the mode change appears as a subtle wave-like surface-color transition.

The direction of the wave depends on the roof profile:

- Vertical panel profile: the transition moves horizontally across the roof zone.
- Rectangular shingle profile: the transition moves down the roof zone.
- Low-profile barrel profile: the transition moves down the roof zone.

The transition happens within the roof surface color. It is not a physical movement of the roof material.

## Visual Guidance

Zones should be visible enough to explain product behavior, but they should not make the roof look like a patchwork graphic system.

Zone behavior should feel:

- subtle
- functional
- architectural
- calm
- integrated
- based on real roof geometry

Zone behavior should not feel:

- random
- decorative
- glowing
- digital
- overly segmented
- mechanically animated
- like a roof made of screens

## Image Prompt Guidance

When prompting zone behavior, describe the roof zones as functional sections of the real roof.

Preferred prompt language:

> Show Sora's responsive roof divided into realistic roof zones based on roof planes and sun exposure. One sun-exposed zone has shifted into reflect mode while a shaded zone remains in absorb mode. Preserve the roof geometry, seams, material profile, and residential realism.

For synced behavior:

> Show the entire Sora roof shifting as one unified system in automatic synced mode. The surface-color transition moves as a coordinated wave while the roof profile, seams, pattern, and structure remain unchanged.

Avoid prompt language:

- "draw graphic sections on the roof"
- "make the roof glow by zone"
- "show animated digital panels"
- "separate the roof into bright colored blocks"
- "open some roof sections"
- "flip the roof tiles"

## Copy Guidance

Use zone language to explain how the product responds to real conditions.

Preferred copy:

- "Each roof zone responds to its own surface temperature."
- "Sun-exposed and shaded sections can respond differently."
- "Zones are customized to the roof's shape, slope, orientation, and installation layout."
- "Homeowners can choose independent or synced behavior through the roof control interface."

Avoid copy:

- "Each zone responds to the weather."
- "The roof changes whenever the sun comes out."
- "The homeowner controls every panel."
- "The system predicts the weather and adjusts in advance."

## Related Files

- `responsive-roofing-system.md`
- `roof-modes.md`
- `roof-profiles.md`
- `roof-control-interface.md`
- `product-accuracy-rules.md`
