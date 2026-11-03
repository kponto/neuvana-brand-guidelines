# How to produce human-readable guidelines

Use this file when the task is a brand guidelines document, style guide, one-pager, or deck derived from this kit. These rules override a model’s default tendency to invent a generic guidelines structure.

You are in the repository. Read the files listed under Required files yourself. Do not ask the user to paste them.

Always also load `verbal/constraints.yaml`.

## Rules

1. **Copy.** Do not invent copy unless the prompt explicitly asks for new copy. Placeholder and sample copy come only from the production lines in `verbal/messaging.md`. No near-synonyms, no rewrites.

2. **Logos.** Do not invent, redraw, restyle, or recolor logos outside the Cloud and Tar assets. Use the files in `visual/assets/brand/`. If an asset cannot be placed, leave the space and say so.

3. **Corners.** Corners are square. If a radius is required, the maximum is 4px.

4. **Frame.** Use the Frame whenever possible. Do not use bento boxes or card grids as the layout system. Treat sections as multiple Frames. A section without a Frame is an exception and should be rare. See `visual/frame.md`.

5. **No filler.** Include only sections that are in the kit or explicitly requested. Do not add principles, process, handoff, or “how to use this document” sections to fill space.

6. **No invented principles.** Do not invent design, product, company, or positioning principles. Use the rules in the kit or say nothing. Do not paraphrase existing rules into new principle names.

7. **Type.** Set all text in Figtree or Instrument Sans per `visual/visual-system.json`, unless the prompt specifies otherwise. Hero and H1 are Figtree Bold. H2 and below are Figtree Semibold. Body is Instrument Sans. Font files are in `visual/fonts/`. If a font cannot be loaded, stop. Do not substitute and continue.

8. **App vs marketing.** Do not apply app UI patterns, app color usage, or app component styles to marketing layouts. App screens, if shown, come from `visual/assets/app/` and are labeled as app reference only. See `visual/app.md`.

9. **One concept per page.** In multi-page documents and decks, use one concept per page if possible. Do not combine palette, type, and logo on a single page unless the format is a one-pager or the prompt asks for it.

## Default sections

If the prompt does not specify sections, use only these, in this order:

1. Color
2. Type
3. Logo
4. Frame
5. Voice and constraints

App reference only if the prompt asks for it.

## Required files

Read these yourself:

- `how-to-guidelines.md` (this file)
- `verbal/constraints.yaml`
- `visual/visual-system.json`
- `visual/frame.md`
- `visual/logo.md`
- `verbal/messaging.md`
- `verbal/voice-and-tone.md`

Add `visual/app.md` only if app screens are requested. Logo assets are in `visual/assets/brand/`. Font files are in `visual/fonts/`.
