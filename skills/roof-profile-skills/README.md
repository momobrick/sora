# Sora Roof Profile Skills

This folder contains profile-specific skills for applying the Sora material signature to separate roof profiles and then creating multi-angle reference sheets for each approved result.

## Important behavior

All six skills are designed to produce a **copy/paste-ready prompt** for an external image generation tool. They should not simply describe the task.

- The three `apply-...` skills generate a prompt for applying `sora-roof-pattern_123` to a specific roof profile reference.
- The three `create-...-reference-sheet` skills generate a prompt for creating a multi-angle reference sheet from an already-approved Sora-applied roof profile.

Each skill should ask for the required reference image or images first, then output a clean prompt the user can paste into GPT Image, Sora, Midjourney, or another image generation workflow.

## Included skills

### Application prompt skills
- `apply-sora-material-to-barrel-tile.md`
- `apply-sora-material-to-shingle.md`
- `apply-sora-material-to-vertical-panel.md`

### Reference-sheet prompt skills
- `create-barrel-tile-reference-sheet.md`
- `create-shingle-reference-sheet.md`
- `create-vertical-panel-reference-sheet.md`

## Recommended workflow

1. Use the relevant application skill with:
   - `sora-roof-pattern_123`
   - the matching roof profile reference: `barrel_123`, `shingle_123`, or `vertical_123`

2. Copy the generated prompt into an image generation tool along with the two reference images.

3. Review and refine the generated Sora-applied roof profile until the profile geometry and material treatment are correct.

4. Use the matching reference-sheet skill with the approved Sora-applied roof profile image.

5. Copy the generated reference-sheet prompt into an image generation tool along with the approved roof profile image.

6. Use that final reference sheet later when applying the roof profile to blank house roofs.

## Shared Sora material signature

Across all profiles, the Sora material should preserve:
- soft sculptural wave bands
- shallow molded relief
- fine striations that follow the flow of the waves
- subtle low-sheen architectural material quality
- durable, manufacturable product character
- profile-specific roof geometry
