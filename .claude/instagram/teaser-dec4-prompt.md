# Site 2 TEASER — Fri Dec 4 — "click shots" (style B)

Reference: mock folder, 5th file (SaveClip … AQOGj3aw…), 9.7 s. What it does:
- Every shot is a STILL photo (freeze frame), cut on a camera-shutter click.
- Rhythm: fast burst (0.2 s per photo) → black pause → slower holds (0.4–0.5 s) →
  very fast burst (0.1 s per photo) → short black → 2 hero holds (0.8 s) with warm
  orange/yellow light-leak flashes between them → small logo on black.
- An elegant script title sits in the centre of every shot (the project name), with a
  small line of caps above it.
We copy the format and rhythm only — not their name, font or logo.

## Stills (sharpest frame already picked from each clip)
| Code | Source file | Time | Content | Fix |
|---|---|---|---|---|
| K3a | DJI_20261113_153609 | 5.50 s | Appliance shutter open | — |
| K3b | DJI_20261113_153609 | 14.62 s | Pantry shelves with jars | — |
| K3c | DJI_20261113_153609 | 21.00 s | Wall cabinet open | — |
| K3d | DJI_20261113_153609 | 34.92 s | Utensil drawer | — |
| K3e | DJI_20261113_153609 | 52.38 s | Loft open | — |
| K4a | IMG_3457 | 9.50 s | Appliance unit, team member | — |
| K4b | IMG_3457 | 18.75 s | Pantry door opening | — |
| K4c | IMG_3457 | 33.12 s | Drawer below the hob | — |
| K4d | IMG_3457 | 39.12 s | Plate rack | — |
| K1a | DJI_20261113_152901 | 4.12 s | Tall units, wide | white-balance: remove orange cast |
| K1b | DJI_20261113_152901 | 8.50 s | Wall cabinets, wide | white-balance: remove orange cast |
| L1a | IMG_0332 | 0.62 s | Arch + study nook | — |
| L1b | IMG_0332 | 8.12 s | Bookshelf niches | — |
| L1c | IMG_0332 | 14.30 s | TV unit, navy wall | crop cables / set-top box / table edge |
| L1d | IMG_0332 | 16.48 s | Showcase | crop UPS + table edge |
| B1a | IMG_0341 | 0.75 s | Upholstered headboard wall | — |
| B2a | IMG_0342 | 3.62 s | Bed + headboard (landscape) | crop a vertical window |
| W1a | IMG_0329 | 0.00 s | Wardrobe | crop boxes on top + bedsheet |
| V1a | IMG_0326 | 0.00 s | Vanity | crop/blur basin sticker |
| V2a | IMG_0327 | 4.62 s | Vanity + mirror | crop/blur basin sticker |
The same stills are supplied as JPGs (Forma_teaser_stills.zip) — use those directly.

---

## PROMPT (paste into your tool)

```
Build a 9.5-second teaser Reel for Forma Studio (@forma_studio_7), Site 2.
1080x1920, 30 fps, H.264. Two versions: original sound design/music and silent.

STYLE — "CLICK SHOTS"
- Every shot is a STILL (use the supplied stills / freeze frames, never moving video).
- Each still appears on a camera-shutter CLICK with a 2-frame white flash.
- Each still fills the full 1080x1920 frame (cover-crop, lanczos). Apply the crops and
  white-balance fixes listed in the stills table. Very slow push 100→103% on every still
  held longer than 0.3 s.
- Grade all stills to match: bright, clean, neutral-warm; whites read white.
- Title on every shot (except black frames and the logo), centred at y ≈ 860:
  small line "FORMA STUDIO" (Montserrat 500, 30 px, letter-spacing 0.35em, cream)
  and under it "Lived In" in an elegant script (Pinyon Script or Great Vibes, 150 px,
  cream #F2EAE0, soft shadow). The title never moves while the photos change under it.
- Warm light-leak flashes (orange #FF8A3D → yellow #FFE27A gradient, screen blend,
  4–6 frames) where marked below.

TIMELINE
0.00–1.40  BURST 1 — 7 stills × 0.20 s, one click each:
           K3b, K3c, L1b, B2a, K3e, W1a, L1a
1.40–2.60  BLACK (title hidden). Low whoosh rising.
2.60–3.60  2 holds × 0.50 s: B1a, K4d
3.60       Orange light-leak flash
3.70–4.50  2 holds × 0.40 s: L1c, K1b
4.50–5.50  BURST 2 — 10 stills × 0.10 s (rapid clicks):
           K3a, K3d, K4b, K4c, L1d, V2a, K1a, K4a, L1b, B1a
5.50–6.00  BLACK
6.00       Yellow light-leak flash
6.10–6.90  HERO 1 (0.80 s, slow push): B1a — upholstered headboard wall
6.90       Orange light-leak flash
7.00–7.80  HERO 2 (0.80 s, slow push): K3a — appliances behind the rolling shutter
7.80       Orange flash fading to black
8.20–9.50  Forma logo (from the logo PDF, cream/gold on black), centred, small
           (width 300 px), fades in. No date, no other text.

SOUND (Python, original): a crisp camera-shutter click on every still (synthesised,
not sampled). Burst 1: clicks over a soft low pulse. Black: rising whoosh. Holds: a deep
bass hit on each flash. Burst 2: rapid clicks in rhythm. Heroes: warm pad swell.
Logo: one resolving tone with a short reverb tail. About -14 LUFS.

CHECK: title readable on every still (add a soft dark vignette if a still is very
bright); no basin sticker, boxes, cables or UPS visible; no orange cast on K1a/K1b.
```
