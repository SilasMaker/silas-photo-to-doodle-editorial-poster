---
name: silas-photo-to-doodle-editorial-poster
description: Use when a user asks to turn a photo into a 3:4 editorial diptych with the faithful source photograph above and the same subject redrawn below in sparse black-and-ivory crayon, charcoal, or dry-brush style.
---

# Silas Photo to Doodle Editorial Poster

## Core principle

Preserve the source before interpreting it. The upper panel is the photograph itself; the lower panel redraws the same recognizable subject and relationship with fewer, rougher marks.

**REQUIRED TOOL:** Use the available image-generation/editing capability for the lower illustration only. Use deterministic image tooling for source cleanup, proportional cropping, light grading, final assembly, and geometry verification.

## Workflow

1. Inspect each source at full useful detail. Treat every source as an independent poster unless the user explicitly requests a collage.
2. Write a private source-reading card covering identity anchors, expression, pose, decisive relationship, removable background, forbidden additions, and three short English text layers.
3. Read [references/prompt-template.zh-CN.md](references/prompt-template.zh-CN.md) before prompting or composing.
4. Build two separate 3:2 panels:
   - upper: use the source photo directly; remove screenshot chrome or borders, crop proportionally, and apply only a subtle editorial grade;
   - lower: generate the same subject and relationship on warm ivory paper using only rough black crayon, charcoal, and dry-brush marks;
   - final: stack the panels without a frame, gutter, shadow, or extra strip.
5. If the lower panel looks etched, photographic, or finely cross-hatched, make one style-only correction: simplify detail, thicken broken marks, and increase exposed paper.
6. Inspect identity, anatomy, relationship, text, negative space, and geometry. Correct one defect per iteration and save with a versioned filename.

## Non-negotiable visual contract

| Area | Required result |
|---|---|
| Canvas | One 3:4 portrait; straight boundary at exactly 50% height; both panels are 3:2 |
| Upper | The processed source photo itself; no generated replacement, identity drift, stretching, or redesigned scene |
| Lower | The same recognizable subject, pose, expression, and relationship, redrawn rather than mechanically traced |
| Palette | Black pigment and warm ivory paper only; mark density may vary, but no smooth grayscale gradient or color |
| Marks | Rough wax crayon, charcoal blocks, dry-brush skips, broken contours, exposed paper, and irregular edges |
| Copy | `No.XX`, one 2–4 word English title, and one very short English sentence; no extra text unless the user asks |
| Finish | Old black-and-white children's picture book × restrained independent art magazine; generous negative space |

Do not generate the whole poster in one pass when the upper photograph must stay faithful. Do not accept “approximately half.” Reassemble equal panels deterministically and compare the decoded final halves with their approved panel inputs.

## Privacy

Treat source photos, identity references, and private outputs as confidential. Never copy them into the Skill directory, examples, documentation, commits, or a public repository unless the user explicitly authorizes those exact files. Public packages should contain instructions and metadata only by default.
