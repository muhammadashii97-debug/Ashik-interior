# Forma Studio — Packages motion series: prompts

Series name: **SAME SIZE. THREE STORIES.**
Paste the GLOBAL BRIEF first, then one weekly prompt. Every fact below comes from the
Forma Studio brochures (Oct 2026 rates). Do not let the tool invent prices or features.

---

## GLOBAL BRIEF (paste before every weekly prompt)

```
You are making one Instagram Reel for Forma Studio, a modular interiors and bespoke
cabinetry studio in Coimbatore (www.formastudio.site, @forma_studio_7).
Export MP4, H.264, 1080x1920, 30 fps. Deliver TWO files: one with the original music,
one with no audio.

TOOLCHAIN — use each tool for its job:
- Remotion (Node.js): builds the whole motion piece — locked dimension frame, upgrade
  scan wipe (clip-path), LED "lights on" flicker, odometer price counter, feature chips,
  MOST CHOSEN badge, floor-plan line draw (SVG stroke-dashoffset), departure-board price
  flip, 15° perspective tilt (CSS 3D transform), Forma logo tag, end card. Keep every
  timing in frames on a 100 BPM grid (18 frames per beat at 30 fps) and export the cut
  list (frame numbers of every scene change, scan start, lights-on, price flip).
- FFmpeg: prepares the input images (crop each tier panel to vertical, upscale with
  lanczos, match colour across tiers so the scan wipe looks seamless), applies the final
  colour finish (warm, slightly lifted blacks, light grain), and muxes the music.
- Python: composes ORIGINAL music (no samples from existing songs) at 100 BPM,
  warm and minimal (soft piano / muted pluck + low pad + light percussion), reading the
  Remotion cut list so accents land on: each upgrade scan (soft riser into a hit),
  lights-on (a single bright chime), each price flip (tick), end card (resolve).
  Music fades out over the last 1.5 s. Loudness about -14 LUFS.
- Whisper: only if a voiceover is added — transcribe it and burn in captions inside the
  safe zone, timed per word.
- Git: setup only.

SERIES CONCEPT — "SAME SIZE. THREE STORIES."
Forma's packages keep the SAME outer size of each unit and upgrade what is inside, across
three tiers. Make that visible:
- THE LOCKED FRAME: a thin gold dimension frame (width / height arrows with real
  measurements) sits around the unit and NEVER moves. Only the inside changes.
- THE UPGRADE SCAN: a vertical gold light-line sweeps left→right across the unit. Behind
  it, the unit becomes the next tier. Smart Essentials → Signature Comfort → Forma Luxe.
- LIGHTS ON: the moment Signature Comfort is revealed, the warm LED strips in the unit
  switch on (a 6-frame flicker, then steady glow). This is the brand signature —
  the website line is "Lights on. Welcome home."
- THE PRICE METER: a slim vertical meter on the left edge fills as the tier rises, with
  the price counting up (e.g. ₹2,200 → ₹3,200 → ₹4,200 / sq ft). Numbers roll like an
  odometer, never jump.
- MOST CHOSEN: Signature Comfort gets a small taupe badge "MOST CHOSEN" that drops in with
  a soft bounce. Signature is the hero tier; hold on it 1 second longer than the others.
- FEATURE CHIPS: 3 short chips per tier slide up from the bottom one by one (max 4 words
  each), then fade as the next scan starts.

LOOK
- Colours: espresso background #120E0B, cream text #F2EAE0, gold accent #C8A27A,
  taupe badge #8C6E5A. Warm, calm, premium. No neon, no pure white backgrounds.
- Type: serif display for headlines (Playfair Display or Cormorant Garamond, caps,
  letter-spaced), clean sans for details (Montserrat or Inter). Headline min 64 px,
  details min 34 px. Text always on a dark plate or with a soft shadow — must be readable
  on a phone at arm's length, muted.
- Motion: ease-in-out cubic, nothing linear. Slow push-in (102%→108%) on every image so
  nothing is ever static. Cuts land on the beat grid of 100 BPM (every 0.6 s / 18 frames).
- Grain: very light film grain + vignette for the premium feel.

SAFE ZONE (Instagram UI covers the rest)
- All text between y = 230 and y = 1440. Keep the right 230 px free of text.
- Hook text must be on screen from frame 1. No logo intro, no black frames at the start.
- Logo: small "F | FORMA STUDIO" mark, top-left inside the safe zone, 60% opacity.

RULES
- One idea per reel. Max 6 words per on-screen line.
- Always show "+ 18% GST" next to prices, and a small footer "Oct 2026 rates · Machine
  finish extra" on price scenes.
- Use only the facts given in the weekly prompt. Do not invent prices, features,
  materials, timelines or client results.
- Final frame repeats one word/number from the hook so the loop lands cleanly.
- End card CTA (one ask only): "Get your estimate · formastudio.site".
- Total length 24–30 seconds.
```

---

## WEEK 1 — Kitchen + Wardrobe

```
WEEK 1 REEL: KITCHEN + WARDROBE.  Length: 28 s.

HOOK (0:00–0:02.4)
On screen, frame 1: "DON'T BUY A KITCHEN" / "UNTIL YOU SEE THIS"
Behind it: the Smart Essentials kitchen already visible, gold dimension frame drawing
itself around it (Run A 120" / Run B 108" / 96" height).

KITCHEN (0:02.4–0:13)
- Title chip: "KITCHEN · SAME SIZE · 3 TIERS"
- Smart Essentials — price meter ₹2,200/sq ft + 18% GST.
  Chips: "1 tandem drawer" · "Cutlery + thali organiser" · "Sainik MR + laminate"
- UPGRADE SCAN → Signature Comfort — LIGHTS ON — "MOST CHOSEN" badge — ₹3,200/sq ft.
  Chips: "Bottle pull-out" · "Built-in bin" · "710 BWP + acrylic"
- UPGRADE SCAN → Forma Luxe — ₹4,200/sq ft.
  Chips: "Premium corner solution" · "2 tandem drawers" · "Club Prime + PU / glass"

TRANSITION (0:13–0:14)
The kitchen slides up out of frame; the gold frame stays and resizes (animated arrows)
to the wardrobe size 72" W × 84" H. This resize is the bridge — make it satisfying.

WARDROBE (0:14–0:24.5)
- Title chip: "WARDROBE · SAME SIZE · 3 TIERS"
- Smart Essentials ₹2,100/sq ft. Chips: "2 hanging sections" · "Door mirror" · "Sainik MR"
- SCAN → Signature Comfort — LIGHTS ON — MOST CHOSEN — ₹3,400/sq ft.
  Chips: "Integrated dressing" · "Mirror storage" · "710 BWP + acrylic"
- SCAN → Forma Luxe ₹4,400/sq ft. Chips: "Pull-down hanging" · "Tie / belt organiser"
  · "Club Prime + PU"

END (0:24.5–0:28)
Split screen: the two Signature Comfort units side by side, lights on.
Line 1: "SAME SIZE. THREE STORIES." Line 2: "Get your estimate · formastudio.site"
Footer: "From prices + 18% GST · Oct 2026 rates · Machine finish extra"
Loop: last word on screen is "KITCHEN" fading back toward the hook.

ASSETS: kitchen_smart.png, kitchen_signature.png, kitchen_luxe.png,
wardrobe_smart.png, wardrobe_signature.png, wardrobe_luxe.png, logo.svg
(each tier image shot from the IDENTICAL camera angle and framing so the scan wipe reads
as a morph).
```

---

## WEEK 2 — TV unit + Study + Crockery

```
WEEK 2 REEL: TV UNIT + STUDY + CROCKERY.  Length: 27 s. Faster rhythm than week 1.

HOOK (0:00–0:02.4)
On screen, frame 1: "3 UNITS." / "3 TIERS." / "ONE WALL EACH."
Then: "DON'T BUY ONE UNTIL YOU SEE THIS"

STRUCTURE — "THE ROTATING WALL"
The gold locked frame stays centred the whole video. Each unit enters by the wall
rotating like a turntable (a flat 2.5D card flip, 12 frames). Inside each unit, the
UPGRADE SCAN runs Smart → Signature → Luxe, faster: 2.2 s per tier, Signature 3 s.

TV UNIT (0:02.4–0:10)  frame 72" W × 60" H
- Smart ₹1,600/sq ft: "2 drawers · 2 shutters" · "Simple wall panel"
- Signature ₹1,900/sq ft (LIGHTS ON, MOST CHOSEN): "Open display tower" · "Feature panel"
- Luxe ₹2,500/sq ft: "Floating display ledge" · "PU finish"

STUDY UNIT (0:10–0:17.5)  frame 48" W × 72" H
- Smart ₹1,800/sq ft: "2 drawers" · "Open desk"
- Signature ₹2,000/sq ft (LIGHTS ON, MOST CHOSEN): "3-level display" · "Soft-close drawers"
- Luxe ₹2,500/sq ft: "Floating book ledge" · "Premium drawers"

CROCKERY UNIT (0:17.5–0:24)  frame 48" W × 72" H
- Smart ₹2,000/sq ft: "Open serving niche" · "Upper + lower shelves"
- Signature ₹2,500/sq ft (LIGHTS ON, MOST CHOSEN): "Framed glass display"
- Luxe ₹3,100/sq ft: "Twin glass display bays" · "PU / glass"

END (0:24–0:27)
Three Signature units in a row, lights on, like one finished living wall.
"YOUR HOME. ONE DESIGN LANGUAGE." → "Get your estimate · formastudio.site"
Footer: "+ 18% GST · Oct 2026 rates · Machine finish extra"

ASSETS: tv_smart/signature/luxe.png, study_smart/signature/luxe.png,
crockery_smart/signature/luxe.png, logo.svg
```

---

## WEEK 3 — 2BHK whole home

```
WEEK 3 REEL: 2BHK WHOLE HOME PACKAGE.  Length: 28 s.

HOOK (0:00–0:02.6)
On screen, frame 1: "DON'T BUY A 2BHK INTERIOR" / "UNTIL YOU SEE WHAT ₹4.5 LAKH GETS YOU"
Spoken (if voiceover is used later): "Don't buy a 2BHK interior until you've seen what
₹4.5 lakh gets you."

STRUCTURE — "BLUEPRINT TO HOME"
1. (0:02.6–0:07) A 2BHK floor plan draws itself in thin gold line on espresso, top-down,
   walls first, then doors. Room labels type in: Kitchen, Bedroom 1, Bedroom 2,
   Living, Study corner.
2. (0:07–0:15) THE DROP-IN: each package item lands in its room as a small gold icon
   with a soft thud and a ripple, and a counter on the left ticks up:
   - Kitchen (up to 75 sq ft)  1
   - Wardrobe 6 × 7 ft  → Bedroom 1   2
   - Wardrobe 6 × 7 ft  → Bedroom 2   3
   - Study unit   4
   - TV unit + wall panel → Living   5
   - Crockery unit   6
   Counter label: "6 ITEMS. ONE PACKAGE."
3. (0:15–0:16) LIGHTS ON: every room's floor glows warm at once; the plan tilts into a
   gentle 3D perspective (15°) and the camera pushes in.
4. (0:16–0:24) THE PRICE BOARD: three cards flip like a departure board, one by one:
   SMART ESSENTIALS ₹4,50,000 · SIGNATURE COMFORT ₹6,50,000 (MOST CHOSEN badge,
   card slightly larger, held longest) · FORMA LUXE ₹8,50,000 — each "+ 18% GST".
   Under each, one line: "Laminate" / "Acrylic + Hettich-level" / "PU + premium hardware".
5. (0:24–0:28) Trust strip slides in: "45-day target delivery* · 1-year workmanship
   warranty · 2D approval before fabrication". Then CTA "Get your 2BHK estimate ·
   formastudio.site". Footer: "*Subject to approved drawings & site readiness ·
   Oct 2026 rates · Cabinetry scope only". Last frame shows "2BHK" for the loop.

ASSETS: floor plan (2BHK, any representative plan or SVG), 1 hero living-room image,
logo.svg, icons for kitchen/wardrobe/study/TV/crockery (or let the tool draw line icons).
```

---

## WEEK 4 — 3BHK whole home

```
WEEK 4 REEL: 3BHK WHOLE HOME PACKAGE.  Length: 28 s.
Use EXACTLY the Week 3 template so the series feels like one family, with these changes:

HOOK (0:00–0:02.6)
"DON'T BUY A 3BHK INTERIOR" / "UNTIL YOU SEE WHAT ₹6 LAKH GETS YOU"

CALLBACK OPENING (new): start on the finished, lit 2BHK plan from last week for 0.5 s,
then a third bedroom slides in from the right and the walls redraw — "ONE MORE ROOM."

DROP-IN items and counter:
- Kitchen (up to 80 sq ft) · Wardrobe 6×7 ft → Bedroom 1 · Bedroom 2 · Bedroom 3
- Study unit · TV unit + wall panel · Crockery unit
Counter label: "7 ITEMS. ONE PACKAGE."

PRICE BOARD: SMART ESSENTIALS ₹6,00,000 · SIGNATURE COMFORT ₹8,00,000 (MOST CHOSEN)
· FORMA LUXE ₹10,00,000 — each "+ 18% GST".

END: "2BHK OR 3BHK — SAME CLARITY." → "Get your 3BHK estimate · formastudio.site"
Same footer and trust strip as Week 3. Last frame shows "3BHK" for the loop.

ASSETS: 3BHK floor plan, hero image, logo.svg, same icons as Week 3.
```

---

## Details to send before production
1. Separate high-res tier images for each unit (kitchen, wardrobe, TV, study, crockery x
   Smart/Signature/Luxe = 15), vertical, identical camera angle per unit.
2. 2BHK and 3BHK floor plans (or OK to use a representative plan marked "Representative layout").
3. Logo as SVG or transparent PNG; brand fonts if you have them.
4. Confirm billing: per sq ft on front area (W x H)? Enables a worked example line.
5. Were the images AI-generated? (→ turn on Instagram's AI label.)
6. Text only, or a voiceover (English / Tamil)?
