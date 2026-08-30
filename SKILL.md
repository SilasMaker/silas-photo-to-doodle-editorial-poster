---
name: silas-photo-to-doodle-editorial-poster
description: Use when a user asks to turn one or more photos into separate 3:4 editorial posters, photo-and-doodle reinterpretations, lifestyle-zine layouts, or meaning-driven real-subject plus black-line-doodle compositions.
---

# Silas Photo to Doodle Editorial Poster

## Core principle

Read the relationship before selecting the object. The lower panel must preserve what makes the source memorable—identity, gesture, distance, contrast, or emotion—not merely the largest shape.

**REQUIRED TOOL:** Use the available image-generation/editing capability for photoreal reconstruction. Use deterministic image tooling only for lossless sizing, cropping, background extension, and final panel assembly.

## Workflow

1. Inspect every source image at full useful detail. Treat each source as an independent poster unless the user explicitly requests a collage.
2. Write a private source-reading card covering identity anchors, decisive relationship, memorable meaning, removable details, must-keep subjects, forbidden additions, and one short handwritten line.
3. Read [references/prompt-template.zh-CN.md](references/prompt-template.zh-CN.md) before prompting or composing.
4. Prefer a two-panel build:
   - upper panel: the source photo itself, lightly graded and cropped or naturally outpainted to 3:2 without stretching subjects;
   - lower panel: a separately generated 3:2 editorial reinterpretation using photoreal source anchors, 2–3 tiny black-line doodle people, and large pale negative space;
   - final poster: stack the two equal-height panels into an exact 3:4 canvas.
5. Generate one lower panel per source. Do not reuse fixed doodle actions across unrelated photos.
6. Inspect identity, anatomy, relationship, text, negative space, and geometry. Correct one defect per iteration, then save non-destructively with a versioned filename.

## Non-negotiable visual contract

| Area | Required result |
|---|---|
| Canvas | One 3:4 portrait; straight boundary at exactly 50% height; both panels are 3:2 |
| Upper | Source photograph remains real and recognizable; no identity drift or subject distortion |
| Lower | Real source-derived anchors carry color and material; doodles remain sparse secondary actors |
| Relationships | If people or animals define the story, every participant remains substantially recognizable in the lower panel—not only a paw, sleeve, prop, or shadow |
| Non-human scenes | Keep a real anchor traceable to the source; do not invent an unrelated photoreal symbol to explain the story |
| Copy | One short, correct handwritten phrase; meaning-led, not an object label or generic title |
| Finish | Restrained palette, fine dark lines, generous negative space, no sticker or template look |

Do not accept “approximately half.” Use the geometry equations, quality gates, prompt contract, and correction order in the required reference. If generation misses the boundary, reassemble equal panels without stretching subjects.

## Privacy

Treat source photos, identity references, and private outputs as confidential. Never copy them into the Skill directory, examples, documentation, commits, or a public repository unless the user explicitly authorizes those exact files. Public packages should contain instructions and metadata only by default.
