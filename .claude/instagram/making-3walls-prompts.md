# Forma Studio — "3 WALLS" making series (problem animatic → real footage)

Two reels (+1 optional bonus). Each opens with a 3-second Remotion animatic that shows the
PROBLEM, then real site footage shows how Forma is solving it. The finished result is
the Dec 26 full reveal.

| Post | Reel | Hook (score) |
|---|---|---|
| Fri Nov 13 | MAKING 1 — Ground floor: staircase, hall panelling, TV wall | "Don't leave the first 3 walls your guests see bare." (87 STRONG) |
| Fri Nov 20 | MAKING 2 — Bedroom: back panel, wardrobe, bay window | "Don't waste 3 walls of your bedroom." (87 STRONG) |
| Fri Nov 27 | BONUS 1 — "Walk in with us" one-take house tour | "Don't judge a home by its outside. Walk in with us." (80 STRONG) |
| Fri Dec 4 | BONUS 2 — Founder on site | "Your designer should be on site every week. Ours is." (78 STRONG) — only if true |

## Source files (Drive folder "making")
| Code | File | What it is | Notes |
|---|---|---|---|
| C1 | DJI_20261101_113851_176_video.mp4 | Bedroom: bed back-panel wall → person in orange T-shirt walks in → wardrobe / walk-in shelving with carpenter | 1920x816, 59.94 fps, 16 s |
| C2 | DJI_20261101_114355_508_video.mp4 | Hall: staircase + wood arch + panelled walls → marble TV wall with metal zig-zag strip | 1920x816, 59.94 fps, 14 s |
| C4 | DJI_20261101_115142_649_video.mp4 | Exterior orbit of the house, louvred window box | 1920x1080, 23.976 fps — do NOT slow down |
| C7 | DJI_20261101_115533_144_video.mp4 | Entering through the gate | 1920x816, 59.94 fps |
| W  | DJI_20261101_115815_780_video.mp4 | 98 s walkthrough (bay window, jali, wardrobe build) | 1920x816, 59.94 fps |
Skip DJI_..._115333 and _115438 (tilted overhead shots of paint buckets — not usable).
All 1920x816 clips carry a -180 rotation flag: let FFmpeg auto-rotate.

---

## SHARED BRIEF (paste first, once per reel)

```
Build one Instagram Reel for Forma Studio (Coimbatore, @forma_studio_7). 1080x1920,
30 fps, H.264. Two versions: original music and silent. Length 20–22 s.

STRUCTURE
A) PROBLEM ANIMATIC (Remotion, 0:00–0:03.2) — no footage.
   Espresso background #120E0B. A clean isometric line drawing of the room in muted
   grey (#6E6862) — walls blank and flat. Hook text from frame 1 (serif, cream #F2EAE0,
   88 px, two lines). The 3 problem walls pulse one after another with a small grey
   "BARE" tag and a counter "1 / 2 / 3" (0.5 s each). Feeling: dull, empty, lifeless.
B) THE TURN (0:03.2–0:03.8): a gold line (#C8A27A, 3 px, glow) sweeps across the
   drawing; every line it passes turns gold; text: "Here's how we're fixing it."
   Sideways-blur push straight into the first footage clip.
C) RESOLUTION FOOTAGE (0:03.8–0:18.5): three wall chapters, each with a chip
   "WALL 1 / 3 · NAME", a 6-word-max caption, and the gold design line tracing the key
   edge of the work once. A tiny inset of the animatic wall (top-right, 160 px) flips
   from grey "BARE" to gold "DONE" as each chapter starts — this ties every shot back to
   the hook.
D) END CARD (0:18.5–0:21.5, hold ≥ 2.5 s): "3 WALLS. IN THE MAKING." /
   "FULL REVEAL · DEC 26" / "Follow @forma_studio_7". Last frame loops into the hook.

FOOTAGE RULES (FFmpeg)
- FULL VIEW: wide subjects (walls, staircase, bay window, rooms) use a FULL-WIDTH card
  1080 px wide showing the whole source frame (2.35:1 → 1080x459) with a slow 104→110%
  push. Never crop a wide wall into a narrow 4:5 card. Tall subjects (wardrobe interior,
  a person) may use a 4:5 card 1000x1250.
- 59.94 fps clips: 50% slow motion using real frames. The 23.976 fps exterior plays at
  100% only.
- Stabilise (vidstab two-pass). Crop out paint buckets, bags, loose wires, debris; skip
  any moment that cannot be cropped clean.
- Colour: bright and clean — exposure +0.3, lift shadows, neutral-warm white balance;
  white walls read white, wood reads warm.
- Text inside y 230–1440; right 230 px clear. Captions on a dark plate.

MUSIC (Python, original): 90 BPM. Animatic: sparse low piano + soft ticking (dull).
At THE TURN: warm pad swells in + chime. Each WALL chip: soft pluck accent. End card:
resolving chord. Fade last 1.5 s. About -14 LUFS.
Use only the text given. No invented materials, sizes or prices.
```

---

## MAKING 1 — GROUND FLOOR (post Fri Nov 13)

```
HOOK (frame 1): "DON'T LEAVE THE FIRST 3 WALLS" / "YOUR GUESTS SEE BARE."   (87)
ANIMATIC ROOM: entrance hall in grey line drawing — a staircase against a blank wall,
a blank side wall, a blank TV wall. Problem tags pulse on: 1 STAIRCASE WALL · 2 HALL
WALL · 3 TV WALL.

ESTABLISH (0:03.8–0:05.0): C4 exterior orbit, 1.2 s at 100% speed, full-width card.
  Caption: "Our site in Coimbatore."
  then C7 gate entry 0:00–0:01.5 (50%) as a 1 s push-through into the house.

WALL 1 / 3 · STAIRCASE (0:06–0:10.5)
  C2 0:00–0:04.5 (50% → ~4.5 s used) — full-width card, the whole staircase with the
  wooden arch and panelled walls in view. Gold line traces the arch.
  Caption: "Wood arch. Panelled stair wall."
  Then W 0:46.5–0:49.5 (50%) — the jali screen at the top. Caption: "Jali at the top."

WALL 2 / 3 · HALL PANELLING (0:10.5–0:13.5)
  C2 0:05–0:08.5 (50%) — the white wall with framed moulding panels, full width.
  Gold line traces one moulding frame. Caption: "Framed panel moulding."

WALL 3 / 3 · TV WALL (0:13.5–0:18.5)
  C2 0:09.5–0:13.9 (50%) — marble-finish TV wall with the metal zig-zag strip,
  full width, slow push. Gold line traces the zig-zag. Caption: "Marble-finish TV wall."

END CARD as in the shared brief.
```

---

## MAKING 2 — BEDROOM (post Fri Nov 20)

```
HOOK (frame 1): "DON'T WASTE" / "3 WALLS OF YOUR BEDROOM."   (87)
ANIMATIC ROOM: bedroom in grey line drawing — blank wall behind the bed, blank wardrobe
wall, a plain window. Problem tags: 1 BED WALL · 2 WARDROBE WALL · 3 WINDOW.

WALL 1 / 3 · BED BACK PANEL (0:03.8–0:08)
  C1 0:01–0:04.5 (50%) — the bed wall with the wooden frame and centre panel, full
  width. Gold line traces the frame. Caption: "Framed back panel behind the bed."
  Then C1 0:05–0:07 (50%) — the person in the orange T-shirt walks into the room.
  Caption: "Checking every line on site."

WALL 2 / 3 · WARDROBE (0:08–0:13)
  C1 0:09–0:15 (50%, use ~4 s) — wardrobe / walk-in shelving with the carpenter at work,
  4:5 card (tall subject). Gold line traces the shelving outline.
  Caption: "Wardrobe built in, to the inch."
  Optional 1 s cut: W 1:10–1:12 (shelf grid close-up) if it crops clean.

WALL 3 / 3 · BAY WINDOW (0:13–0:18.5)
  W 1:17–1:20 (50%) — curved bay window frame, FULL WIDTH so the whole curve shows.
  Gold line traces the curve. Caption: "Curved bay window frame."
  Then W 1:25–1:27.5 (100%) — someone sitting on the ledge, full width.
  Caption: "Deep enough to sit."

END CARD as in the shared brief, title "3 WALLS. ONE BEDROOM."
```

---

## BONUS 1 — "WALK IN WITH US" (post Fri Nov 27)

```
Use the SHARED BRIEF look and music, but no animatic — this one hooks with motion.
Length 20 s. Feels like ONE continuous walk from the street into the bedroom.

HOOK (frame 1): exterior already moving.
  "DON'T JUDGE A HOME BY ITS OUTSIDE." / "Walk in with us."   (80 STRONG)
  C4 0:05–0:08 at 100% (23.976 fps clip — never slow it), full-width card that grows
  to fill the frame as the camera nears the house.

ONE-TAKE ILLUSION — match cuts through doorways, with speed ramps:
  - Between rooms: 200% speed + directional motion blur (0.4–0.6 s).
  - On each hero: drop to 50% slow motion (real 60 fps frames) for 2–2.5 s.
  - Sound: a soft "whoosh" on every ramp, a warm pluck when slow motion lands.
  A thin gold progress line runs along the bottom of the card (inside the safe zone)
  and a room chip counts "ROOM 1/4 … 4/4" — viewers stay to see the last room.

SEQUENCE
  1. C7 0:00–0:02 — through the gate (ramp in).
  2. ROOM 1/4 · HALL — C2 0:00–0:04 slow: staircase, wood arch, panelled walls
     (full width). Caption: "Staircase wall, panelled."
  3. ramp → ROOM 2/4 · LIVING — C2 0:09.5–0:13.5 slow: marble-finish TV wall
     with the zig-zag strip. Caption: "Marble-finish TV wall."
  4. ramp up the stairs — W 0:42–0:48 at 200%, then W 0:48–0:51 slow looking up
     at the jali. Caption: "Jali at the top."
  5. ROOM 3/4 · BEDROOM — C1 0:01–0:04 slow: bed back-panel wall, then
     C1 0:09–0:13 wardrobe being built (4:5 card). Caption: "Wardrobe, taking shape."
  6. ROOM 4/4 · BAY WINDOW — W 1:17–1:20 slow, FULL WIDTH, then W 1:25–1:27.5 at 100%
     someone sitting on the ledge. Caption: "Deep enough to sit."
END (2.5 s): "THIS IS THE MAKING." / "THE FINISHED HOME · DEC 26" /
  "Follow @forma_studio_7"
```

---

## BONUS 2 — FOUNDER ON SITE (post Fri Dec 4)

Use ONLY if (a) the person in the orange T-shirt is the founder and happy to be named, and
(b) the hook is true. If the designer is not on site every week, use the fallback hook.

```
Length 12 s, 4:5 card, bright grade, SHARED BRIEF look and music.

HOOK (frame 1): "YOUR DESIGNER SHOULD BE ON SITE" / "EVERY WEEK. OURS IS."   (78)
  Fallback hook if not literally true: "THIS IS WHO CHECKS EVERY LINE."
  Clip: C1 0:04.5–0:09 at 50% — he walks into the bedroom and looks over the work.
  Lower third at 0:02: "{{Name}} · Founder, Forma Studio"
Then C1 0:09–0:13 at 50% — carpenter at the wardrobe. Caption: "With our carpenters,
  on every site."
Then W 1:06–1:09 at 50% — two carpenters measuring at the window (crop clean).
  Caption: "Measured on site, to the inch."
END (2.5 s): "MEET THE PEOPLE BUILDING YOUR HOME." / "Follow @forma_studio_7"
```
