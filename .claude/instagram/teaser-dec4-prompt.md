# Site 2 TEASER — Fri Dec 4 — "click shots" — VIDEO PROMPT

Stills are finished: Forma_teaser_stills_FINAL.zip — 19 JPGs, each already 1080x1920,
cleaned, cropped and graded to the reference palette. The tool only assembles them.

| Code | Content | | Code | Content |
|---|---|---|---|---|
| K3a | Appliances behind the rolling shutter | | K1b | Kitchen corner, wall cabinets |
| K3b | Pantry shelves | | L1a | Arch + study nook |
| K3c | Wall cabinet open | | L1b | Bookshelf niches |
| K3d | Utensil drawer | | L1c | TV wall |
| K3e | Loft open | | L1d | Showcase |
| K4a | Appliance unit | | B1a | Upholstered headboard wall |
| K4b | Pantry door opening | | B2a | Headboard close |
| K4c | Kitchen counter + chimney | | W1a | Wardrobe |
| K4d | Plate rack | | V1a | Vanity cabinet |
| K1a | Tall units, wide | | | |

```
Build a 9.5-second teaser Reel for Forma Studio (@forma_studio_7).
1080x1920, 30 fps, H.264. Two versions: with original sound and silent.

INPUT: the 19 supplied stills (1080x1920 JPG). Use them exactly as they are:
do NOT re-grade, re-crop, sharpen, upscale or AI-edit them. No moving video.

STYLE — "CLICK SHOTS"
- Each still appears on a camera-shutter CLICK with a 2-frame white flash (60% opacity).
- Stills held longer than 0.3 s get a very slow push-in, 100→103%.
- Title on every still (not on black frames or the logo), centred at y ≈ 860 and
  never moving while the photos change underneath:
    line 1: "FORMA STUDIO" — Montserrat 500, 30 px, letter-spacing 0.35em, cream #F2EAE0
    line 2: "Lived In" — Pinyon Script (or Great Vibes), 150 px, cream #F2EAE0,
            soft dark shadow so it reads on light walls.
- Warm light-leak flashes where marked: orange #FF8A3D → yellow #FFE27A gradient,
  screen blend, 4–6 frames.

TIMELINE (seconds)
0.00–1.40  BURST 1 — 7 stills × 0.20 s, one click each:
           K3b, K3c, L1b, B2a, K3e, W1a, L1a
1.40–2.60  BLACK, title hidden. Low rising whoosh.
2.60–3.60  2 holds × 0.50 s: B1a, K4d
3.60       orange light-leak flash
3.70–4.50  2 holds × 0.40 s: L1c, K1b
4.50–5.50  BURST 2 — 10 stills × 0.10 s, rapid clicks:
           K3a, K3d, K4b, K4c, L1d, V1a, K1a, K4a, L1b, B1a
5.50–6.00  BLACK
6.00       yellow light-leak flash
6.10–6.90  HERO 1 (0.80 s, slow push): B1a
6.90       orange light-leak flash
7.00–7.80  HERO 2 (0.80 s, slow push): K3a
7.80       orange flash fading to black
8.20–9.50  Forma logo from the supplied logo PDF, cream/gold on black, centred,
           300 px wide, fade in over 10 frames. No date, no other text.

SOUND (Python, original, about -14 LUFS): a crisp synthesised camera-shutter click on
every still. Burst 1: clicks over a soft low pulse. Black: rising whoosh. Holds: a deep
bass hit on each flash. Burst 2: rapid clicks in rhythm. Heroes: warm pad swell.
Logo: one resolving tone with a short reverb tail.

CHECK BEFORE EXPORT: frame 0 is a still with the title on it (not black); every click
lands exactly on its cut; the title is readable on every still; total length 9.5 s.
```
