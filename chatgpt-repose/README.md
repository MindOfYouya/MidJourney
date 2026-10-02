# ChatGPT single-figure re-pose prompt (goblin apothecary)

Re-poses an existing character as ONE full-body figure (no character sheet) while keeping its painterly style, halftone shading, palette and costume detail. Derived from a character-sheet prompt that gave perfect fidelity; the sheet layout was removed and the character, costume and style wording was kept nearly verbatim. Confirmed working by the author in ChatGPT image generation.

## Files

- `master-prompt.txt` - paste this into ChatGPT with the reference image attached. Includes a default pose (tired road walk).
- `poses.md` - the swappable POSE section: a slot template plus ready-made poses.

## Usage

1. Start a new chat for each pose and attach the reference image every time. Long chats, especially one that already contains a sheet, may drift back toward sheet layouts or soften the style.
2. Paste `master-prompt.txt`. To change the pose, replace only the `POSE (follow exactly)` section at the end, from the `POSE` line to the end of the prompt.
3. Change one thing at a time. If a pose keeps failing, cut its block to the 3-4 key facts (leg spread, lean angle, head tilt, what each hand holds).

The reference image itself is not stored in this repo. The prompt assumes the original goblin image is attached.

## Design notes

- **SIDES block** pins left/right to the viewer's side and says never to mirror, so the strap, satchel and pouch stay on the same sides of his body when the figure turns.
- **Lighting lock** (warm key from the upper right, cool blue-violet shadows opposite) keeps the light from flipping with the pose.
- **Anti-copy sentence** in TASK tells the model to treat the image as a character and style reference only. Dial: if identity or style drifts, soften "paint a new figure from scratch" toward "same character, new pose"; if it still copies the pose, tighten it.
- **Belt details** (dark sash with red accent, small frayed grey cloth, small rust-brown vial at the top of the pouch) are named because a re-posed figure redraws that area and would otherwise drop or invent them.
- Prefer poses facing the viewer's left, as the reference does. Facing right hides the satchel and makes left/right swaps more likely.
- Leg-driven poses (walk, crouch, sit) need a turn of about 50-60 degrees; arm-driven poses can stay near 30.
- The reference looks closer to 4:5. ChatGPT's available image sizes may differ (unconfirmed), so the prompt just says portrait.

## If it keeps copying the reference pose

Attach a second image of a plain grey stick figure in the target pose. Name both files and say: "character_ref is character and style; pose_guide is pose only, ignore its look". It may also pull in the guide's proportions, so keep it very simple.

## Follow-ups (positive-first)

Copied the pose:

```
Redraw with only these pose facts, keeping the same goblin, costume, style and plain background: [paste 3-4 lines of the POSE]. Paint it from scratch; do not reuse the reference's silhouette.
```

Style drift (re-attach the reference; if the pose or face shifts, start a fresh chat):

```
Keep this pose and character, and repaint the finish to match the attached reference: visible dry-brush strokes, angular faceted colour planes, layered opaque paint, small low-contrast halftone dots in the shaded areas, painted glass highlights, no airbrushing or thick outlines.
```

Wrong hand (poses where the flask is held):

```
Put the flask in his right hand, which is on the viewer's left. Do not mirror the figure: the strap still runs from the viewer's-left shoulder to the satchel on the viewer's-right hip.
```

Cropped or sheet residue:

```
One single full-body figure on a plain background, no panels or text. Zoom out so ears, boots, coat hem and flask are all inside the frame with a margin.
```
