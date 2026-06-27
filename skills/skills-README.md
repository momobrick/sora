# Sora Skills Workflow

## Purpose
This folder contains reusable Sora skills for creating brand writing, house studies, landscape plates, roof profile applications, house-landscape composites, and final Sora lighting treatments.

The image skills are designed to work as a production sequence. Each skill handles one clear step so prompts stay focused and image results are easier to control.

---

## Primary image workflow

```text
1. Regional House Study
   Create the blank house.

2. Apply Vertical Profile Panel
   Apply the Sora vertical standing-seam roof profile to the blank roof.

3. Landscape Background Plate
   Create the empty regional landscape.

4. House Landscape Composite
   Place the roofed house into the landscape.

5. Divided Lighting
   Apply the final Reflect Mode / Absorb Mode split treatment.
```

---

## Simple workflow diagram

```text
regional-house-study.md
        ↓
apply-vertical-profile-panel.md
        ↓
        ┌──────────────────────────────┐
        │ landscape-background-plate.md │
        └──────────────────────────────┘
                    ↓
house-landscape-composite.md
        ↓
divided-lighting.md
```

The landscape can be created before or after the regional house study. The composite step simply needs both inputs: a house image and a landscape image.

---

## Skill order

### 1. `regional-house-study.md`
Use this first to create a clean regional house with a blank, visible roof.

The goal is to generate the house form before adding the Sora roofing system.

Use when you need:
- a Southwestern desert house
- a Rocky Mountain cabin
- a tropical coastal house
- a Pacific Northwest forest home
- another regionally appropriate residential house

Main output:
- one believable house
- simple roof geometry
- blank roof surface
- neutral lighting
- controlled architectural view

---

### 2. `apply-vertical-profile-panel.md`
Use this after the blank house exists.

The goal is to apply Sora’s vertical standing-seam roof profile without changing the house, roof shape, roof color, or lighting.

Use when you need:
- raised vertical ribs
- recessed panel pans
- subtle low-relief wave bands
- fine striations within the panel pans
- a realistic architectural roof surface

Main output:
- the same house
- the same roof geometry
- Sora vertical profile panel applied to the roof
- no Reflect Mode or Absorb Mode color yet

---

### 3. `landscape-background-plate.md`
Use this to create the empty environment where the house will later be placed.

This can happen before or after the house is generated.

Use when you need:
- a Southwestern desert landscape
- a Rocky Mountain forest landscape
- a tropical coastal landscape
- a Midwest farmland landscape
- a Pacific Northwest forest landscape

Main output:
- no house
- no buildings
- no people
- clear level buildable area
- soft overcast lighting
- compositing-friendly perspective

---

### 4. `house-landscape-composite.md`
Use this after you have both:
1. a house image
2. a landscape image

The goal is to place the house into the landscape believably while preserving the house, roof profile, landscape, perspective, and realism.

Use when you need:
- correct scale
- believable placement
- contact shadows
- consistent lighting
- natural integration
- roof visibility preserved

Main output:
- one completed house-in-landscape image
- Sora roof profile preserved
- scene ready for final lighting treatment

---

### 5. `divided-lighting.md`
Use this last.

The goal is to apply Sora’s signature split treatment:
- left side: Reflect Mode + bright midday lighting
- right side: Absorb Mode + dusk lighting

Use when you need:
- final campaign image treatment
- Reflect / Absorb mode comparison
- day-to-dusk split lighting
- unified sky and cloud structure
- soft warm window glow on the dusk side

Main output:
- final Sora visual
- same house and landscape preserved
- roof color changes only for mode visualization
- no unwanted redesign or regeneration

---

## Full image pipeline

```text
Create house
→ Apply Sora roof profile
→ Create landscape
→ Composite house into landscape
→ Apply Sora divided lighting
```

Or, if you prefer to create the landscape first:

```text
Create landscape
→ Create house
→ Apply Sora roof profile
→ Composite house into landscape
→ Apply Sora divided lighting
```

Both are valid.

The important rule is:

```text
House + landscape must both exist before compositing.
Divided lighting should happen last.
```

---

## Brand writing skill

### `brand-writer.md`
Use this whenever you need Sora copy, messaging, headlines, captions, campaign language, website copy, presentation language, or brand rationale.

This skill is separate from the image production workflow, but it can support any stage of the project.

Use when you need:
- headlines
- taglines
- product descriptions
- social captions
- website copy
- campaign messaging
- presentation language
- concise rationale

Main output:
- clear, grounded, climate-aware Sora writing
- practical language
- no unsupported product claims
- no “green” or “smart” language
- no generic launch hype

---

## Suggested folder contents

```text
skills/
├── README.md
├── brand-writer.md
├── regional-house-study.md
├── apply-vertical-profile-panel.md
├── landscape-background-plate.md
├── house-landscape-composite.md
└── divided-lighting.md
```

---

## Working principle
Each skill should do one job.

Avoid combining too many image changes in one prompt. The Sora image workflow works best when the model solves one controlled task at a time:
- first the house
- then the roof profile
- then the landscape
- then the composite
- then the final lighting treatment
