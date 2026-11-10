# Forma Studio — IN THE MAKING: 2 premium reels (replaces the 4 "3 Walls" reels)

| Post | Reel | Hook (score) |
|---|---|---|
| Fri Nov 13 | REEL A — "THE FIRST IMPRESSION": exterior → entrance → staircase & jali → hall panelling → TV wall | "Don't leave the first 3 walls your guests see bare." (87 STRONG) |
| Fri Nov 20 | REEL B — "THE BEDROOM": team on site → bed back panel → wardrobe → bay window seat | "Don't waste 3 walls of your bedroom." (87 STRONG) |

RULE: every shot appears in ONE reel only. Nothing repeats between A and B.
Walls3 (walk-in) and Walls4 (on site) are retired; their best unique moments are folded in
(exterior + gate + speed ramps → Reel A; team on site + measuring → Reel B).

Sources (same Drive folder): C1 = DJI_..113851 (bedroom, team, wardrobe), C2 = DJI_..114355
(staircase, hall, TV wall), C4 = DJI_..115142 (exterior, 23.976 fps), C7 = DJI_..115533
(gate), W = DJI_..115815 (98 s walkthrough). All 1920x816 clips: auto-rotate (-180 flag).

---

## PREMIUM MOTION BRIEF (paste first for both reels)

```
Build a premium, high-end Instagram Reel for Forma Studio (Coimbatore, @forma_studio_7).
1080x1920, 30 fps, H.264, 18–20 s. Two versions: original music and silent.
The look must feel like a luxury real-estate film, not a slideshow.

1. FILL THE SCREEN — no thin strips.
   - Background layer: the SAME clip, scaled to cover 1080x1920, Gaussian blur 40,
     brightness -35%, slight warm tint. It moves with the footage (live, not a still).
   - Foreground "hero card": 1080x640 (crop 1440x816 from the source, lanczos), rounded
     corners 0, soft shadow, centred at y ≈ 640–1280. It PANS across the source
     (left→right or right→left, 6–10% per second) so the FULL width of every wall is
     revealed during the shot.
   - Tall subjects (wardrobe interior, a person) use a 900x1200 card instead.

2. SKETCH-TO-REAL (signature effect, once per chapter)
   - For the first frame of each chapter clip, generate line art from the REAL frame
     (tested settings): brighten the frame (eq brightness 0.06, contrast 1.08) →
     hqdn3d=6:6 → edgedetect=low=0.08:high=0.22 → threshold to white lines on black →
     thicken lines with a 3x3 max filter (dilate 1 px) → remove specks under 20 px →
     colour the lines gold #D8B488 on transparent → add a 5 px gold glow (screen blend). In Remotion, draw that line art on over 14 frames (stroke reveal
     left→right), hold 4 frames, then cross-dissolve (10 frames) into the live footage
     exactly underneath. Reads as "design drawing becomes the real build".

3. KINETIC TYPE
   - Hook: 3 lines, serif caps (Cormorant Garamond 600 or Playfair Display 600),
     104 px, cream #F2EAE0, keyword in gold. Each line rises 40 px with a mask reveal,
     5 frames apart. Placed at y 300–620, full width, centred. On screen from frame 1.
   - Chapter titles: big gold numeral "01" (180 px, Cormorant, 30% opacity) behind a
     cream label "STAIRCASE" (56 px, letter-spaced 0.2em); numeral slides in from the
     left, label wipes in from a 2 px gold line.
   - Captions: Montserrat 500, 40 px, below the hero card, max 6 words, fade-up.

4. CAMERA & LIGHT
   - Every shot moves: slow push 100→108% plus the pan. 3D card tilt between chapters
     (rotateY 8° → 0° with perspective 1400 px) on the transition.
   - Transitions: horizontal motion-blur whip (8 frames) with a warm light-leak flash
     (amber #FFB45A, screen blend, 25% peak).
   - Grade: bright and clean — exposure +0.35, shadows lifted, white balance neutral-
     warm, wood saturation +10%, very light grain. White walls must read white.
   - Crop out paint buckets, bags, loose wires, debris. If a moment cannot be cropped
     clean, skip it.

5. TIMING & SPEED
   - 59.94 fps clips: 50% slow motion on hero moments (real frames, no interpolation);
     200% speed ramps between moments. The 23.976 fps exterior: 100% only.

6. LAYOUT & SAFE ZONE
   - All text inside y 230–1440; right 230 px clear of text.
   - Small "F | FORMA STUDIO · IN THE MAKING" tag top-left, 60% opacity.

7. END CARD (hold 2.5 s): logo builds from its gold tips; "IN THE MAKING" /
   "FULL REVEAL · DEC 26" / "Follow @forma_studio_7". Last frame dissolves toward the
   first frame for a clean loop.

8. MUSIC (Python, original): 92 BPM, cinematic and warm — felt piano + soft strings
   pad + low pulse. A rising swell into each chapter, a soft "whoosh" on every whip, a
   chime on each sketch-to-real dissolve, resolving chord on the end card.
   Fade last 1.5 s. About -14 LUFS.

Use only the text given below. No invented materials, sizes, prices or dates.
```

---

## REEL A — "THE FIRST IMPRESSION" (Fri Nov 13)

```
HOOK 0:00–0:02.2 — real footage behind the type from frame 1 (no abstract drawing):
  W 0:04–0:07, desaturated to 15% colour, darkened: bare walls and raw cement.
  Kinetic hook: "DON'T LEAVE" / "THE FIRST 3 WALLS" / "YOUR GUESTS SEE BARE."
  ("3 WALLS" in gold.)   (87 STRONG)
  At 0:01.6 a gold line sweeps across; colour floods back as it passes →

OPEN 0:02.2–0:04 — C4 0:05–0:07 exterior at 100% (hero card pans up the façade),
  whip → C7 0:00–0:01.5 through the gate at 200%. Caption: "Our site in Coimbatore."

01 · STAIRCASE 0:04–0:09.5
  Sketch-to-real on C2 0:00 frame → C2 0:00–0:03.5 at 50%: staircase, wood arch and
  panelled wall; card pans right to left across the full wall. Caption: "Wood arch.
  Panelled stair wall."
  Ramp up the stairs W 0:42–0:46 at 200% → W 0:48–0:51 at 50%, tall 900x1200 card,
  looking up at the jali. Caption: "Jali at the top."

02 · HALL 0:09.5–0:12.5
  Sketch-to-real on C2 0:05 frame → C2 0:05–0:08.5 at 50%: framed moulding panels,
  full-width pan. Caption: "Framed panel moulding."

03 · TV WALL 0:12.5–0:17
  Sketch-to-real on C2 0:10 frame (the zig-zag strip draws itself in gold) →
  C2 0:09.5–0:13.9 at 50%, slow push. Caption: "Marble-finish TV wall."

END CARD 0:17–0:19.5
```

---

## REEL B — "THE BEDROOM" (Fri Nov 20)

```
HOOK 0:00–0:02.2 — W 0:54–0:57 desaturated: unfinished room, panels leaning on the wall.
  Kinetic hook: "DON'T WASTE" / "3 WALLS" / "OF YOUR BEDROOM."   (87 STRONG)
  Gold sweep at 0:01.6, colour floods back →

OPEN 0:02.2–0:04.2 — C1 0:04.5–0:08 at 50%, tall card: a team member walks into the
  room and studies the work. Caption: "Forma Studio, on site."

01 · BED WALL 0:04.2–0:08
  Sketch-to-real on C1 0:01 frame (the wooden frame of the back panel draws itself) →
  C1 0:01–0:04.5 at 50%, full-width pan. Caption: "Framed back panel behind the bed."

02 · WARDROBE 0:08–0:12.5
  Sketch-to-real on C1 0:10 frame (shelf grid draws itself) → C1 0:09–0:14 at 50%,
  tall card: wardrobe shelving with the carpenter at work.
  Caption: "Wardrobe, taking shape."
  Whip → W 1:06–1:09 at 50%: two carpenters measuring at the window (crop clean).
  Caption: "Measured to the inch."

03 · BAY WINDOW 0:12.5–0:17
  Sketch-to-real on W 1:18 frame (the curved frame draws itself) → W 1:17–1:20 at 50%,
  full-width pan revealing the whole curve; crop the orange bags out of the bottom.
  Caption: "Curved bay window frame."
  → W 1:25–1:27.5 at 100%: someone sits on the ledge. Caption: "Deep enough to sit."

END CARD 0:17–0:19.5
```
