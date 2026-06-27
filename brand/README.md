# Sora Brand System

This folder contains the source-of-truth guidance for Sora’s brand strategy, audience, voice, messaging, product representation, creative direction, and applied communication surfaces.

Use this folder when generating, reviewing, or refining any Sora-facing brand output, including copy, prompts, product descriptions, campaign concepts, presentation slides, website sections, social content, and brand book material.

## How the Brand Files Work Together

The Sora brand system is organized in three layers:

1. **Core brand guidance** defines what Sora means, who it serves, how it sounds, and what it should avoid.
2. **Product guidance** defines what the responsive roofing system is, how it behaves, and how it should be represented accurately.
3. **Surface guidance** defines how the brand translates into specific formats and touchpoints.

Together, these files help Sora stay consistent while still allowing the brand to adapt across assignments, prompts, images, campaigns, and presentation formats.

## Recommended Workflow

1. Start with `foundation.md` to understand the core brand idea, mission, vision, positioning, and role.
2. Review `audience.md` to ground the work in real homeowners, communities, and climate-exposed contexts.
3. Use `messaging.md`, `voice.md`, and `lexicon.md` when writing or revising copy.
4. Use the `product/` folder whenever the work describes what the roofing system does or how it behaves.
5. Use `creative-direction.md` when shaping visual direction, imagery, material cues, composition, or art direction.
6. Use the `surfaces/` folder when creating a specific touchpoint or assignment output.
7. Check `anti-patterns.md` before finalizing work.

## Core Brand Files

| File | Role |
|---|---|
| `foundation.md` | Defines Sora’s core belief, purpose, mission, vision, positioning, brand promise, and role in the world. |
| `audience.md` | Defines who Sora is for, what they need, and how the brand should meet them. |
| `messaging.md` | Defines the core message, messaging pillars, value themes, launch language, and brand-level product framing. |
| `voice.md` | Defines how Sora should sound across copy, captions, presentations, and AI-generated text. |
| `lexicon.md` | Defines preferred language, careful-use terms, avoided phrases, and better substitutions. |
| `creative-direction.md` | Defines the visual and conceptual direction for Sora’s brand world, imagery, material cues, and composition. |
| `anti-patterns.md` | Defines off-brand verbal, visual, strategic, and product-representation patterns to avoid. |

## Product Folder

The `product/` folder is the accuracy layer for Sora’s first product: a responsive roofing system.

Use these files whenever copy, prompts, diagrams, captions, or campaign concepts describe product behavior.

| File | Role |
|---|---|
| `responsive-roofing-system.md` | Defines the core product category, function, system components, and product experience. |
| `roof-modes.md` | Defines Reflect Mode and Absorb Mode. |
| `roof-profiles.md` | Defines the roofing profiles and material behavior across different roof types. |
| `roof-zones.md` | Defines how roof sections or zones behave independently or together. |
| `roof-control-interface.md` | Defines the homeowner-facing control interface and manual override behavior. |
| `product-accuracy-rules.md` | Defines product claims, technical guardrails, and accuracy checks. |

## Surfaces Folder

The `surfaces/` folder translates the brand system into applied formats. Use it when developing assignment deliverables, brand book examples, campaigns, social posts, website sections, presentation slides, or product captions.

| File | Role |
|---|---|
| `surfaces/README.md` | Explains how surface files support assignments, touchpoint testing, and governance. |
| `headline.md` | Guides campaign headlines, slide titles, and hero statements. |
| `social.md` | Guides social, feed, story, and motion-oriented applications. |
| `website.md` | Guides landing page, digital, and product-explainer applications. |
| `presentation-slide.md` | Guides class presentations and final brand book slides. |
| `campaign-panel.md` | Guides posters, campaign panels, billboards, and high-impact static layouts. |
| `product-caption.md` | Guides captions, callouts, labels, and short product explanations. |

## Decision Rules

Use the most specific file for the task:

- For brand purpose or positioning, use `foundation.md`.
- For audience relevance or emotional framing, use `audience.md`.
- For copywriting, use `messaging.md`, `voice.md`, and `lexicon.md` together.
- For product behavior or claims, use the `product/` folder.
- For visual direction, use `creative-direction.md`.
- For a specific format, use the matching file in `surfaces/`.
- For final review, use `anti-patterns.md` and `product/product-accuracy-rules.md`.

## Prompting Use

When using these files to guide AI work, stack the context in this order:

```text
1. Brand foundation
2. Product accuracy rules
3. Relevant voice, messaging, or lexicon guidance
4. Relevant creative direction or surface guidance
5. Specific task instructions
```

This helps AI-generated work stay grounded in the brand while still adapting to the requested output.

## Governance Checklist

Before finalizing any Sora output, check:

- Does it clearly communicate Sora as a responsive roofing material or climate-adaptive building materials brand?
- Does it avoid misrepresenting the product as a coating, gadget, solar panel, decorative finish, or mechanical roof transformation?
- Does the product respond to roof surface temperature rather than weather, time of day, season, or mood?
- Does the tone feel warm, clear, practical, and grounded?
- Does the work avoid fear-based, luxury-only, overly technical, or sci-fi framing?
- Does the output feel useful for real homes and communities?

## Current Note

At this stage, visual guidance lives primarily in `creative-direction.md`, while format-specific application guidance lives in `surfaces/`. Future visual identity files can be added later if the system expands into a dedicated visual folder.
