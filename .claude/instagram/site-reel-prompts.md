# Forma Studio — "IN THE MAKING" site series (4 reels from one video)

Source: in-progress walkthrough, 98 s, 1920x816, 59.94 fps, HEVC, rotation flag -180
(FFmpeg auto-rotates; the footage plays upright). All timestamps below are in seconds of
that source file.

Posting: Sat Nov 14 · Sat Nov 21 · Sat Nov 28 · Sat Dec 5
(package reels stay on Fridays: Nov 13, 20, 27, Dec 4).

Paste the SITE GLOBAL BRIEF first, then one reel prompt. Fill every {{...}} with real
details before running — the tool must not invent materials, numbers or dates.

---

## SITE GLOBAL BRIEF

```
You are cutting one Instagram Reel for Forma Studio (Coimbatore, @forma_studio_7,
www.formastudio.site) from a real, in-progress site walkthrough. Series name:
"IN THE MAKING". Export MP4 H.264 1080x1920 30 fps, two versions: original music and silent.

SOURCE HANDLING (FFmpeg)
- Source is 1920x816 at 59.94 fps. Use ONLY the timestamps given in the reel prompt.
- Slow motion: play at 50% speed and output 30 fps — this uses the real 60 fps frames,
  so no frame interpolation is needed. Never slow below 50%.
- Stabilise every clip (vidstab two-pass, smoothing 20). Drop any clip that still shakes.
- Do NOT stretch the footage to full screen (a full-height vertical crop of 816 px would be
  upscaled 2.35x and look soft). Instead place the footage in a 4:5 WINDOW CARD,
  960x1200 px, centred at y = 300–1500 area, cropped from the source at 653x816 and
  scaled with lanczos. Pan the crop window slowly left→right inside the source frame
  (Ken Burns) so the shot always moves.
- Crop to avoid clutter (bags, paint buckets, loose wires, workers' belongings). If a
  moment cannot be cropped clean, skip it.
- Colour: warm and clean — lift shadows slightly, white balance toward warm white,
  +10% saturation on wood tones only, light grain. Match all clips to each other.

MOTION DESIGN (Remotion) — same family as the packages series
- Background: espresso #120E0B with a soft warm vignette. Text cream #F2EAE0,
  accent gold #C8A27A. Serif display headlines (Playfair Display / Cormorant, caps),
  sans details (Montserrat / Inter). Headlines min 64 px, details min 36 px.
- WINDOW REVEAL OPEN: frame 1 already shows the hook text AND the window card opening
  (scale 92%→100%, corner radius 28 px). No black frames, no logo intro.
- THE DESIGN LINE (signature effect of this series): on the hero shot, a thin gold line
  (3 px) draws itself along the key edge of the element — stair nosing, wardrobe outline,
  panel curve, window arch — over 18 frames, then softly fades. It reads as "the design
  guiding the build".
- Transitions between clips: sideways motion-blur push (12 frames).
- Tag top-left inside the safe zone: "IN THE MAKING · {{site area, e.g. Saravanampatti}}".
  Small progress chip under it: "{{N}} days to handover" (omit if unknown).
- The pendant-lamp cord from the packages series may hang above the window card, but it
  must never cross text.
- Captions: max 6 words per line, on a dark plate, inside y 230–1440, right 230 px clear.
- End card (hold 2.5 s minimum): "FULL REVEAL · {{reveal date}}" + "Follow @forma_studio_7".
  Last frame echoes one word of the hook for the loop.
- Length 18–22 s.

MUSIC (Python) — original, 90 BPM, warm and minimal (felt piano + soft pad + light
percussion). Accents: a soft riser into each design-line draw, a light chime on the end
card. Fade out last 1.5 s. Loudness about -14 LUFS.

RULES: one idea per reel. Never invent materials, sizes, costs or dates — use only the
{{...}} values filled in. If a value is blank, leave that line out.
```

---

## REEL 1 — STAIRS (post Sat Nov 14)

```
HOOK (frame 1): "DON'T LEAVE YOUR STAIRCASE WALL PLAIN."   (hook score 85.6 STRONG)
Second line at 1.2 s: "Every guest sees it first."

CLIPS (source seconds → use 50% slow motion unless noted)
1. 19.0–23.0  Stair base with the panelled wall and rounded arch. HERO SHOT.
   Design line traces the arch curve, then the stair nosing.
   Caption: "{{wall finish, e.g. fluted laminate panelling}}"
2. 42.0–46.0  Climbing toward the landing, panels on the left.
   Caption: "{{step count}} steps · {{stair finish}}"
3. 46.5–49.0  Landing with the jali screen at the top.
   Design line traces the jali frame. Caption: "{{jali material}} screen up top"
4. 49.0–52.5  Camera tilts up the stairwell to the jali. Normal speed (100%) for energy.
   Caption: "Light from the top."
END (2.5 s): "STAIRCASE · IN THE MAKING" / "FULL REVEAL · {{reveal date}}"
Loop word: "STAIRCASE".
```

---

## REEL 2 — WARDROBE (post Sat Nov 21)

```
HOOK (frame 1): "DON'T JUDGE A WARDROBE BY ITS SHUTTERS."   (hook score 85.8 STRONG)
Second line at 1.2 s: "Look inside first."

CLIPS
1. 33.5–37.5  Bedroom wardrobe with shutters still in protective film. HERO SHOT.
   Design line traces the full wardrobe outline (floor to loft).
   Caption: "Shutters on. Film still on."
2. SIDEWAYS-BLUR PUSH "inside" → 64.5–66.5  Open carcass, shelves and cubbies.
   Caption: "{{carcass ply, e.g. 710 BWP}} carcass"
3. 66.5–69.5  Carpenters fitting the frame by the window (crop to the work, not the room).
   Caption: "Built on site, to the inch."
4. 71.0–75.0  Drawers and shelf grid close-up.
   Caption: "{{N}} drawers · {{N}} shelves · {{hanging?}}"
5. 88.0–90.5  Close-up of interior edge / shelf detail. Design line along one shelf edge.
   Caption: "{{hardware, e.g. soft-close}}"
END (2.5 s): "WARDROBE · IN THE MAKING" / "FULL REVEAL · {{reveal date}}"
Loop word: "SHUTTERS".
```

---

## REEL 3 — BEDFRAME + BACK PANEL (post Sat Nov 28)

```
HOOK (frame 1): "DON'T LEAVE THE WALL BEHIND YOUR BED EMPTY."   (hook score 81.4 STRONG)
Second line at 1.2 s: "Panel it."

Footage is short (about 9 s), so every clip runs at 50% and the hero is held longer.
CLIPS
1. 55.0–57.0  Back panel with the grey inlay strip and rounded top corner, leaning
   before fixing. HERO SHOT. Design line traces the rounded corner and the inlay strip.
   Caption: "{{panel finish}} with {{inlay finish}} strip"
2. 56.0–58.5  The raised bed platform / base. Design line traces the platform edge.
   Caption: "{{bed size, e.g. 6 x 6.5 ft}} bedframe"
3. 62.0–63.8  Close-up of the panel's curved corner. Hold the last frame 1 s
   (freeze + slow push-in 100%→106%).
   Caption: "Curves, not sharp corners."
4. Optional overlay for 1.5 s: a simple gold line sketch of the finished bed wall
   (panel + bed) drawn over the frozen frame — label it "Design".
END (2.5 s): "BEDROOM · IN THE MAKING" / "FULL REVEAL · {{reveal date}}"
Loop word: "WALL".
```

---

## REEL 4 — BAY WINDOW + BACK PANEL (post Sat Dec 5)

```
HOOK (frame 1): "DON'T WASTE YOUR BAY WINDOW."   (hook score 87.0 STRONG)
Second line at 1.2 s: "Turn it into a seat."

CLIPS
1. 77.0–79.5  Bay window with the rounded dark wood frame. HERO SHOT.
   Design line traces the rounded window frame.
   Caption: "{{frame finish}} wrap, rounded corners"
2. 80.0–83.5  Dark rounded wall panel beside the window (crop out loose wires at the
   panel's switch cut-out). Caption: "Matching back panel"
3. 85.0–87.5  Someone sits on the window ledge — PROOF SHOT, the seat in use.
   Normal speed (100%). Caption: "{{seat depth}} deep seat"
4. 92.5–96.5  Wide of the last room: window wall + panel together.
   Design line traces window and panel as one line. Caption: "One room. One design line."
END (2.5 s): "BAY WINDOW · IN THE MAKING" / "FULL REVEAL · {{reveal date}}"
Loop word: "WINDOW".
```

---

## Details needed from Forma before running
1. Site area name (or "Coimbatore" only) and client OK to show the home.
2. Staircase: wall/panel finish, step count, stair finish, jali material.
3. Wardrobe: carcass ply, shutter finish, number of drawers/shelves, hardware.
4. Bedroom: back-panel finish, inlay strip finish, bed size.
5. Bay window: frame finish, seat depth.
6. Days to handover (or leave out) and the full-reveal date (Dec 25/26).
