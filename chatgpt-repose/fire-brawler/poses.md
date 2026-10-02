# Pose blocks - fire-wielding swashbuckler

Replace only the `POSE (follow exactly)` section at the end of `master-prompt.txt` (from the `POSE` line to the end). Leave everything above it untouched.

The reference is front-facing, so neither turn direction is native:
- Turning toward the viewer's LEFT brings his left side (viewer's right: fire hand, ragged sleeve, hip knob) toward the camera and tucks the pauldron and gold-object side back. Safer for left/right.
- Turning toward the viewer's RIGHT brings his right side (pauldron, gold object, strap tail) forward and puts the fire hand on the far side. Higher swap risk; if sides swap, cut the turn to about 25-35 degrees.
- Head-turn angles are measured from the body, so the head ends up closer to facing the camera.
- Leg-driven poses (lunge, walk, crouch) need about 45-55 degrees of turn; arm-driven poses can stay at 25-40.

Suggested test order: 1 (the default in the master), then 3 and 5, then 2. Treat 4 and 6 as experimental until the gold object's grip is confirmed.

## Slot template

```
POSE (follow exactly)
[NAME].
View: [front-three-quarter, TURN IN DEGREES toward the viewer's left or right; head turn so both eyes show].
Legs: [WHICH LEG IS FORWARD OR CARRIES THE WEIGHT; HEEL OR TOE; both boots fully visible].
Torso and head: [LEAN IN DEGREES; CHIN; GAZE; BROWS AND MOUTH].
His right arm (viewer's left): [ELBOW; HAND POSITION].
His left arm (viewer's right): [ELBOW; HAND POSITION; PALM DIRECTION].
Gold object: [held as in the reference, barrel out sideways from the fist, slab hanging beside the thigh; one rigid piece, same shape and size; ANY CLEARANCE RULES].
Fire: [fireball floating a finger-length above the middle fingertip, or above the palm if palm up; never touching].
Cloth and gear: [SLEEVE STRIPS AND SASH TAIL DIRECTION; small gold knob visible behind his left hip].
Ground: [GROUND SMEAR SHAPE].
```

Keep the Gold object and Fire lines in every pose; they carry most of the fidelity. If a pose keeps failing, cut it to the 3-4 key facts.

## 1. Fireball wind-up, mid-lunge (default in the master)

Difficulty: hard. Copy risk: medium. Likely drift: the fireball swells into a glow, the casting hand drifts back up to head height, the gold object hides behind the forward thigh or lands in the wrong hand.

```
POSE (follow exactly)
Fireball wind-up, mid-lunge.
View: front-three-quarter, turned about 50 degrees toward the viewer's left so his left side and the fire hand are nearest the camera; head turned about 25 degrees back toward the camera from the body's direction, both eyes visible.
Legs: lunge toward the viewer's left; viewer's-left knee bent about 40 degrees, viewer's-right leg behind with the heel lifted; both boots fully visible.
Torso and head: leans forward about 15 degrees; chin lowered, deepened scowl.
His right arm (viewer's left): elbow slightly bent, fist beside the hip, slightly behind the forward thigh.
His left arm (viewer's right): drawn back, elbow bent about 90 degrees, open hand at shoulder height, palm toward the camera, hand and fireball at least one head-width clear of the head.
Gold object: held as in the reference, barrel out sideways from the fist, slab hanging beside the thigh and clear of the knee and strap tail; one rigid piece, same shape and size.
Fire: fireball floating a finger-length above the middle fingertip, flame tongue streaming back.
Cloth and gear: ragged sleeve strips sweep back; small gold knob visible behind his left hip.
Ground: ground smear stretched under the lunge.
```

## 2. Confident march, fire side forward

Difficulty: medium. Copy risk: low. Likely drift: the object lifts or gets redrawn as a generic hammer while swinging.

```
POSE (follow exactly)
Confident march, fire side forward.
View: front-three-quarter, turned about 50 degrees toward the viewer's left, walking that way; head turned about 30 degrees back toward the camera, both eyes visible.
Legs: viewer's-left leg forward, heel down; viewer's-right leg trailing, heel lifted; both boots fully visible.
Torso and head: upright, chest out; chin level, one brow raised, stern.
His right arm (viewer's left): relaxed, swinging slightly back, fist beside the hip.
His left arm (viewer's right): swung forward and out, elbow slightly bent, open hand at waist height, palm toward the camera, fingers up.
Gold object: held as in the reference, barrel out sideways from the fist, slab hanging beside the thigh, swinging slightly back; one rigid piece, same shape and size.
Fire: fireball floating a finger-length above the middle fingertip.
Cloth and gear: ragged sleeve strips and sash tail swing back; small gold knob visible behind his left hip.
Ground: ground smear under both boots.
```

## 3. Idle swagger, flame hovering over the palm

Difficulty: easy. Copy risk: high (closest to the reference; may snap back to the frozen frontal stance, or cup the fireball in the palm).

```
POSE (follow exactly)
Idle swagger, flame hovering over the palm.
View: front-three-quarter, turned about 25 degrees toward the viewer's left; head turned about 15 degrees back toward the camera.
Legs: weight on the viewer's-right leg, knee soft; viewer's-left leg relaxed, toe out; both boots fully visible.
Torso and head: relaxed, shoulders loose; chin lowered about 10 degrees, eyes glancing down toward the fireball, both eyes visible, smug, one brow raised.
His right arm (viewer's left): hangs relaxed, fist by the thigh.
His left arm (viewer's right): elbow bent about 90 degrees at the ribs, forearm level and pointing out to the side, open hand palm up at lower-chest height (this pose deliberately turns the palm up).
Gold object: held as in the reference, barrel out sideways from the fist, slab hanging beside the thigh; one rigid piece, same shape and size.
Fire: fireball floating a few finger-widths above the open palm, not touching it.
Cloth and gear: shirt panels hang loose; small gold knob visible behind his left hip.
Ground: ground smear under both boots.
```

## 4. Overhead strike, mid-lunge (experimental)

Difficulty: hard. Swap risk: high. The object's grip is not fully visible in the reference, so expect a lengthened or generic weapon, a two-handed grip, or the cutout and knob lost when it is raised. If so, re-attach the reference and use the "keep the gold object exactly" follow-up; if it still fails, swap in a low backswing (fist behind the right hip, object tilted back about 35 degrees). Start at a 35-degree turn.

```
POSE (follow exactly)
Overhead strike, mid-lunge.
View: front-three-quarter, turned about 35 degrees toward the viewer's right so his right side is nearer the camera; head turned about 20 degrees back toward the camera.
Legs: deep lunge toward the viewer's right; viewer's-right knee bent about 60 degrees; viewer's-left leg behind, heel lifted; both boots fully visible.
Torso and head: leans forward about 20 degrees; chin down, jaw clenched, eyes on the target.
His right arm (viewer's left): elbow bent about 100 degrees, fist above and behind the head.
His left arm (viewer's right): thrown forward, open hand at shoulder height, palm toward the camera.
Gold object: raised above and behind the head, slab pointing up and back, rotated as one rigid piece about 120 degrees from its hanging position; shape and size unchanged; empty margin above it.
Fire: fireball floating a finger-length above the middle fingertip.
Cloth and gear: right sleeve tatters hang from the raised elbow, the pauldron rides up clear of the jaw; ragged sleeve strips and sash tail whip back.
Ground: ground smear under the lunge.
```

## 5. Bracing guard, coiled and low

Difficulty: hard. Copy risk: medium-high (the guard arm resembles the reference's raised arm, only lowered). Guard is an inferred ability from the bracers, not shown in the image. The guard forearm may hide the face or fireball, and the object may vanish behind the thigh.

```
POSE (follow exactly)
Bracing guard, coiled and low.
View: front-three-quarter, turned about 45 degrees toward the viewer's left so his left side is nearest the camera; head turned toward the camera.
Legs: wide crouch, knees bent about 35 degrees, weight on the viewer's-right leg; viewer's-left foot wide, toe out; both boots fully visible.
Torso and head: hunched forward about 20 degrees, shoulders raised; chin tucked, cyan eyes glaring over the raised hand.
His right arm (viewer's left): fist low at the hip, forearm slightly forward, gold object visible beside the thigh.
His left arm (viewer's right): elbow bent about 110 degrees, forearm angled across in front of the chest and shoulder, open hand at chin height, palm toward the camera, about half a head-width in front of the chin; both eyes visible above the wrist.
Gold object: held as in the reference, barrel out sideways from the fist, slab hanging beside the thigh; one rigid piece, same shape and size.
Fire: fireball floating a finger-length above the middle fingertip, clear of the face.
Cloth and gear: shirt panels bunch at the belt; small gold knob visible behind his left hip.
Ground: ground smear narrower than the reference, still a sketchy dry-brush streak.
```

## 6. Triumphant rally, arms flung wide (experimental)

Difficulty: hard. Likely drift: the object redesigned or landing in the wrong hand, the flame tip cropped (the reference flame tip is only about 1 percent from the top edge), the figure shrinking to fit.

```
POSE (follow exactly)
Triumphant rally, arms flung wide.
View: front-three-quarter, turned about 20 degrees toward the viewer's right; head turned about 15 degrees toward the camera.
Legs: wide planted stance, boots about two boot-lengths apart, knees slightly bent; both boots fully visible.
Torso and head: chest out, shoulders back; chin raised, mouth open in a roar, eyes on the camera.
His right arm (viewer's left): thrown out and up, fist at head height two head-widths from the head, holding the gold object aloft.
His left arm (viewer's right): thrown up and out, open hand level with the top of the head, about two head-widths from it, clear of the hair.
Gold object: held aloft in the same orientation as the reference, slab below the fist, clear of the pauldron and face; one rigid piece, same shape and size.
Fire: fireball floating a finger-length above the middle fingertip; keep the whole figure scaled so the flame tip stays inside the frame with 8 percent margin, without shrinking the stature.
Cloth and gear: right sleeve tatters hang from the raised elbow; ragged sleeve strips flutter outward.
Ground: ground smear under the stance.
```

## Not included

There is no "leaning on the hammer" pose. In the reference the object's base hangs well above the ground, so planting it would force the model to lengthen or redesign it. Do not add a pose where the object touches the ground until you confirm how it is held.
