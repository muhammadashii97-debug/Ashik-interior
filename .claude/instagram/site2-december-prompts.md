# Site 2 — "LIVED IN" — December reels (Fri Dec 4, 11, 18)

| Post | Reel | Hook (score) |
|---|---|---|
| Fri Dec 4 | TEASER — black-and-white → colour flips (~8 s) | "A Forma home. Coming soon." |
| Fri Dec 11 | KITCHEN — what hides inside (~21 s) | "Don't leave your mixer on the counter. Hide it behind a shutter." (80 STRONG) |
| Fri Dec 18 | REST OF THE HOME — TV wall, bookshelf, bed wall, vanity (~21 s) | "Don't stop at the kitchen. Plan 4 more walls." (95 STRONG) |

RULES
- Every shot is used in ONE reel only (alternate takes are split between reels).
- No package names, no prices.
- Captions describe cabinetry only — counter, hob, chimney, sink, basin, tap, appliances
  and loose furniture are outside Forma's scope.

## Source clips (Drive folder "raw")
| Code | File | Content | Format |
|---|---|---|---|
| K1 | DJI_20261113_152901_634_video.mp4 | Kitchen full sweep (13 s) | vertical 816x1920, 59.94 fps |
| K3 | DJI_20261113_153609_094_video.mp4 | Hand opening every unit (57 s) | vertical 816x1920, 59.94 fps |
| K4 | IMG_3457.MOV | Man demonstrating every unit (54 s) | vertical 1080x1920, 29.97 fps |
| L1 | IMG_0332.MOV | Living room: arch + study nook, bookshelf niches, TV unit, showcase (20 s) | vertical 1080x1920, 30 fps |
| B1 | IMG_0341.MOV | Upholstered headboard wall, mirror, side table (6.5 s) | vertical 1080x1920, 30 fps |
| B2 | IMG_0342.MOV | Bed, headboard, pouf, window (5.4 s) | LANDSCAPE 1920x1080, 30 fps |
| W1 | IMG_0329.MOV | White wardrobe (4.6 s) | vertical, 30 fps |
| W2 | IMG_0330.MOV | White wardrobe, door opening (4 s) | vertical, 30 fps |
| V1 | IMG_0326.MOV | Vanity, tilt up to mirror (5.9 s) | vertical, 30 fps |
| V2 | IMG_0327.MOV | Vanity, slide in (4.7 s) | vertical, 30 fps |
Do not use: DJI_20261113_153253 (tilted/rotating), IMG_0328 (spinning).
DJI clips carry rotation flags — let FFmpeg auto-rotate.

---

## SITE 2 SHARED BRIEF (paste first for every December reel)

```
Build an Instagram Reel for Forma Studio (Coimbatore, @forma_studio_7). Series:
"LIVED IN" — finished homes that families already live in. 1080x1920, 30 fps, H.264.
Two versions: original music and silent.

LOOK (same brand as the IN THE MAKING reels)
- Espresso #120E0B, cream #F2EAE0, gold #C8A27A. Headlines: Cormorant Garamond 600 caps
  with LINING (full-height) numerals; captions: Montserrat 500, 40 px, dark plate.
- Tag top-left: "F | FORMA STUDIO · LIVED IN", 60% opacity.
- Chapter titles: gold numeral "01" (180 px, 30% opacity) behind a cream label
  (56 px, letter-spaced). Soft dark gradient behind the top 30% of the frame so all text
  reads on light walls (max 45% opacity).
- The source clips are vertical — use them FULL SCREEN. (Only B2 is landscape: crop a
  vertical 608x1080 window from it and pan slowly across.)
- Grade: bright, clean, neutral-warm; match the DJI and iPhone clips to each other.
  White walls read white, wood reads warm.
- Crop or soften (small blur patch) anything that is not Forma's work or looks messy:
  basin sticker, boxes on top of wardrobe, cables/set-top box/router/UPS, bags, cups.

MOTION
- Fast cuts on the beat (95 BPM): every cut lands on a door, shutter or drawer MOVING.
- Speed ramps: 130–150% into each action, back to 100% the moment it opens.
  DJI clips (59.94 fps) may drop to 50% slow motion at the reveal; iPhone clips
  (30 fps) never go below 100%.
- Transitions: horizontal motion-blur whip (8 frames) with a warm light-leak flash.
- Every shot keeps moving: slow push 100→106% if the camera itself is still.

SAFE ZONE: all text between y 230 and y 1440; right 230 px clear.
END CARD (hold ≥ 2.5 s): logo builds from its gold tips; "LIVED IN" /
  "Follow @forma_studio_7". No date.
MUSIC (Python, original, about -14 LUFS): warm and upbeat — muted piano, light
  percussion, soft bass; a pluck on every door/drawer opening, a chime on each chapter,
  resolve on the end card; fade out the last 1.5 s.
CHECK BEFORE EXPORT: text visible on frame 0; no black/empty frames except the end card;
  no repeated shot.
```

---

## REEL 1 — TEASER (Fri Dec 4, ~8 s)

```
TEASER — "A Forma home. Coming soon."  ~8 s.
Every shot is 0.7 s: it starts in BLACK AND WHITE, and on the beat (0.25 s in) flips
to full colour with a soft flash. Fast, rhythmic, no captions. Small centred text
from frame 0 to the end: "a forma home · coming soon" (Cormorant italic, 40 px, cream).

SHOTS (in order)
 1. K3 0:02.4–0:03.4 — rolling shutter rising (50%) — FIRST FRAME, strongest shot
 2. K3 0:12.0–0:13.0 — tall pantry doors opening
 3. K3 0:17.0–0:18.0 — wall cabinet door opening
 4. K3 0:48.0–0:49.5 — loft doors lifting (50%)
 5. L1 0:00.0–0:01.2 — arch with the study nook
 6. B2 0:01.0–0:02.0 — headboard and pouf (vertical crop, slow pan)
 7. V1 0:03.5–0:04.7 — mirror above the vanity (frame the mirror; sticker out of shot)
 8. W2 0:02.5–0:03.5 — wardrobe door opening
 9. K1 0:08.0–0:09.0 — kitchen wall cabinets, wide
END 0:06.3–0:08.3 — black, logo builds from its gold tips, "COMING SOON".
```

---

## REEL 2 — KITCHEN (Fri Dec 11, ~21 s)

```
KITCHEN — "what hides inside".  ~21 s.

HOOK 0:00–0:02 — PROBLEM ANIMATIC (Remotion, no footage)
  Grey line drawing of a kitchen counter crowded with a mixer, kettle, toaster, jars.
  Text on frame 0: "DON'T LEAVE YOUR MIXER" / "ON THE COUNTER."   (80 STRONG)
  At 0:01.4 a gold line sweeps across, the clutter slides away, gold text:
  "Hide it behind a shutter."

01 · APPLIANCE UNIT 0:02–0:05
  K4 0:00–0:06 → use the 3 s where the rolling shutter rises and the appliances appear.
  Caption: "Appliances behind a rolling shutter."
02 · PANTRY 0:05–0:07.5
  K4 0:15.5–0:20 — double doors open on jars and shelves (use 2.5 s).
  Caption: "Tall pantry unit."
03 · PLATES 0:07.5–0:12
  K4 0:28.9–0:31.5 — plate basket drawer pulled out.  Caption: "Pull-out plate drawer."
  K4 0:36.0–0:38.0 — plate rack inside the wall cabinet.  Caption: "Plate rack, built in."
04 · DRAWER 0:12–0:14
  K3 0:33.3–0:35.5 at 50% — cutlery and utensil organiser drawer.
  Caption: "Every utensil, its own place."
05 · LOFT 0:14–0:16.5
  K4 0:46.7–0:49.5 — loft doors lifted open to the ceiling.
  Caption: "Loft storage, up to the ceiling."
06 · THE KITCHEN 0:16.5–0:18.5
  K1 0:05.5–0:09.5 at 100% — calm wide sweep along the wall cabinets.
  Crop out the bag under the sink. Caption: "One kitchen. Nothing on the counter."
END CARD 0:18.5–0:21
Note: K4 shows a team member — use the shots as they are, or crop to his hands.
```

---

## REEL 3 — REST OF THE HOME (Fri Dec 18, ~21 s)

```
REST OF THE HOME.  ~21 s.

HOOK 0:00–0:02.4 — 4-TILE GRID
  Frame 0: the screen split into 4 tiles (TV wall, bookshelf, bed wall, vanity), all
  desaturated, numbered 1–4. Text on frame 0: "DON'T STOP AT THE KITCHEN." /
  "PLAN 4 MORE WALLS."   (95 STRONG)
  At 0:01.6 tile 1 turns to colour and expands to full screen →

01 · TV WALL 0:02.4–0:07
  L1 0:12.0–0:15.0 — TV unit on the navy wall (crop the cables, set-top box, router).
  L1 0:14.5–0:17.0 — tall showcase beside it (crop the UPS and devices on the bottom
  shelf). Caption: "TV unit and showcase, one wall."
02 · BOOKSHELF 0:07–0:10
  L1 0:06.0–0:09.5 — recessed bookshelf niches above the sofa.
  Caption: "Bookshelf niches, built in."
03 · BED WALL 0:10–0:15
  B1 0:00–0:04 — upholstered headboard wall, slow pan to the mirror and side table.
  Caption: "Upholstered bed wall."
  W1 0:00–0:03 — white wardrobe (crop the bedsheet; no boxes in frame).
  Caption: "Wardrobe, built in."
04 · VANITY 0:15–0:18.5
  V2 0:00–0:04.5 — vanity cabinet and mirror (soft blur patch over the basin sticker,
  or crop so it is out of frame). Caption: "Vanity cabinet."
  After each chapter, the matching grid tile flips from grey to gold in a small corner
  inset (top-right, 140 px) — 1/4, 2/4, 3/4, 4/4.
END CARD 0:18.5–0:21
```

## Confirm before captions go live
- The upholstered headboard wall and the vanity cabinet are Forma's work (if either is
  not, drop its caption and keep the shot without text).
