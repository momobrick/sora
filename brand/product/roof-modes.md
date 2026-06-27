# Roof Modes

## Purpose

This file defines Sora's two roof modes, how they function, how they should be described, and how the roof transitions between them.

## Mode Overview

Sora roof materials shift between two visual and functional states:

- reflect mode
- absorb mode

Both modes are part of the same roofing material. The roof does not change shape, expose a separate layer, rotate, open, vent, or mechanically move.

## Reflect Mode

Reflect mode is the lighter roof state.

When the roof surface temperature rises above the reflect-mode trigger point, the roof shifts into a lighter reflective tone to help reflect solar heat and reduce heat gain.

Reflect mode should communicate:

- heat reflection
- reduced heat absorption
- warm-weather adaptation
- surface brightness without glare
- practical cooling support

Preferred language:

- "shifts into reflect mode"
- "uses a lighter surface color to reflect solar heat"
- "helps reduce heat gain"
- "supports comfort in warmer surface conditions"

Avoid language:

- "turns white"
- "becomes mirror-like"
- "blocks all heat"
- "cools the home by itself"
- "eliminates air conditioning"

## Absorb Mode

Absorb mode is the darker roof state.

When the roof surface temperature falls below the absorb-mode trigger point, the roof shifts into a darker absorptive tone to help absorb solar heat and retain warmth.

Absorb mode should communicate:

- passive warmth
- heat absorption
- cooler-weather adaptation
- visual depth without heaviness
- practical comfort support

Preferred language:

- "shifts into absorb mode"
- "uses a darker surface color to absorb solar heat"
- "helps retain warmth"
- "supports comfort in cooler surface conditions"

Avoid language:

- "turns black instantly"
- "heats the whole home"
- "replaces heating systems"
- "stores energy like a battery"
- "generates power"

## Surface Temperature Logic

Sora responds to the surface temperature of the roof.

Do not describe the product as responding directly to:

- outdoor air temperature
- weather forecasts
- time of day
- seasons
- sunlight alone
- smart-home routines

Weather conditions influence the roof surface, but the surface temperature is what determines the mode.

## Temperature Thresholds

The central functional transition point is 60°F / 15.6°C.

For clearer product behavior, the system may be described with a buffer range:

- The roof shifts into reflect mode when the roof surface temperature rises above 62°F / 16.7°C.
- The roof shifts into absorb mode when the roof surface temperature falls below 58°F / 14.4°C.
- Between 58°F and 62°F / 14.4°C and 16.7°C, the roof remains in its current mode.

This buffer prevents unnecessary back-and-forth switching when the roof surface temperature hovers near the central threshold.

## Stabilization Period

Once a roof zone switches modes, it remains in that mode for a defined stabilization period before switching again.

The exact stabilization period may be refined in future product development. For v1 language, describe it as a short minimum hold period that prevents rapid switching while still allowing the roof to respond to meaningful temperature changes.

Preferred language:

- "a short stabilization period"
- "a minimum hold period"
- "designed to prevent unnecessary mode changes"
- "calm, intentional, and reliable response behavior"

Avoid language:

- exact timing unless defined later
- rapid blinking or pulsing
- constant fluctuation
- reactive smart-device behavior

## Visual Transition

Mode changes appear as a subtle wave-like surface-color transition across or down each roof zone.

The visual transition is:

- coordinated
- architectural
- subtle
- integrated with the roof profile
- clearly visible enough to communicate function

The visual transition is not:

- a glow
- an animation effect for its own sake
- a digital screen effect
- a mechanical flip
- a physical surface movement
- a sci-fi transformation

## Control Behaviors

Sora has three primary control behaviors:

### Automatic Independent Mode

Each defined roof zone responds to its own surface temperature and switches independently.

Use this when describing site-specific roof behavior, such as one side of the roof responding differently than another due to sun exposure, shade, orientation, or slope.

### Automatic Synced Mode

The entire roof responds as one unified system.

Use this when describing a homeowner preference for a more unified appearance, simpler behavior, or consistent roof-wide setting.

### Manual Override Mode

The homeowner temporarily selects the preferred mode, overriding automatic behavior.

Manual override is a simple control feature, not the primary way Sora works.

## Roof Control Interface

Sora's controls are envisioned as a simple interior wall-mounted roof control interface, similar in familiarity to a furnace or air conditioning thermostat.

The interface allows the homeowner to select automatic independent mode, automatic synced mode, or temporary manual override without needing to interact directly with the roof surface.

The interface should support the product's automatic behavior rather than making the roof feel like something the homeowner has to constantly manage.

For detailed guidance on the homeowner-facing control experience, see `roof-control-interface.md`.

## Related Files

- `responsive-roofing-system.md`
- `roof-zones.md`
- `roof-profiles.md`
- `roof-control-interface.md`
- `product-accuracy-rules.md`
