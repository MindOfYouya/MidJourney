# ChatGPT single-figure re-pose prompt - fire-wielding swashbuckler

Same system as the goblin apothecary in `../README.md` (read that for the general approach and tips), adapted to this character from the reference image. Not yet tested in ChatGPT: the goblin version was confirmed working, this one has not been run.

Files: `master-prompt.txt` (attach the reference image; includes a default pose) and `poses.md` (pose slot template and six pose blocks).

## What is different from the goblin

- The reference is front-facing, not three-quarter, so turn direction matters (see `poses.md`).
- The gold object in his right fist is described by geometry rather than by name, because it was not identifiable from the image. Naming it (once confirmed) and adding one clause may help; the geometry is intended to reduce the chance of a generic war hammer.
- Halftone dots are bolder here and sit only on the stained lower trousers, boot shafts and bracer wraps.
- The fireball is flat, hard-edged and painted, and casts no light.
- The hair is painted hair with flame-shaped locks, not burning.

## Check against your image

1. What is the large gold object, and does the small gold knob behind his left hip belong to it (for example, the end of a long haft passing behind his legs)? The prompt treats the knob as a separate small detail.
2. The raised hand: the description says palm toward the camera, fingers spread, fingertips bare. Confirm.
3. The pointed gold plate behind his left shoulder: keep or delete that clause. If the model keeps inventing a sword or a second pauldron, delete it.
4. The pauldron emblem: described as a raised ring.
5. Hair: if you meant literal flame hair, change "painted as hair, not burning".
6. Height: reviewers disagreed on head count (about 7.5 vs 9), so the prompt gives no head count, only the shape. Check that outputs keep the broad-shouldered, long-legged stature.

## Follow-ups for this character

Do not reuse the goblin README follow-ups; they mention goblin items and glass highlights.

Copied the pose:

```
Redraw with only these pose facts, keeping the same character, costume, style and plain background: [paste 3-4 lines of the POSE]. Paint it from scratch; do not reuse the reference's silhouette or raised hand.
```

Style drift (re-attach the reference; if the pose or face shifts, start a fresh chat):

```
Keep this pose and character, and repaint the finish to match the attached reference: visible dry-brush strokes, angular faceted colour planes, flat matte faceted gold, hard-edged painted fire, and bold rust-orange halftone dots on the stained lower trousers and boot shafts. No airbrushing, glossy metal or thick outlines.
```

Gold object redesigned:

```
Keep the gold object exactly as in the reference image: same shape, size, round end cap, small stepped knob, flat slab and round cutout. Change only its position.
```

A tight crop of the object attached as a second image named object_ref (shape only) may also help.

Fire glows or lights the background:

```
Keep the fireball flat, hard-edged and painted, small as in the reference, with no glow bloom and no light on the background.
```

Wrong hand:

```
Put the gold object in his right hand, the viewer's left, and the fireball over his left hand, the viewer's right. Do not mirror the figure: the large gold pauldron stays on the viewer's-left shoulder.
```

Cropped:

```
One single full-body figure on a plain background, no panels or text. Zoom out so the hair, flame tip, both hands, the gold object and both boots are all inside the frame with a margin.
```

Halftone spreads onto skin or shirt: add "dots only on the stained lower trousers, boot shafts and bracer wraps". If the dots vanish: "bold rust-orange halftone dots on the lower trousers and boot shafts".
