# Forma Studio — Packages reels, NOV 2026 RATES (replaces the Oct 2026 package reels)

Source: 5 unit comparison sheets (Kitchen, Wardrobe, TV unit, Study unit, Crockery unit) and
Forma_2D_Whole_Home_Nov2026.pdf. Every fact below is copied from those files.
Posting: on hold until reach grows (Forma's decision, Nov 20).

| Reel | Hook (score) |
|---|---|
| Kitchen | "Don't buy a kitchen until you see what ₹1,800 a sq ft gets you." (79) |
| Wardrobe | "Don't buy a wardrobe until you see what ₹1,300 a sq ft gets you." (79) |
| TV unit | "Don't buy a TV unit until you see what ₹1,300 a sq ft gets you." (74) |
| Crockery | "Don't buy a crockery unit until you see what ₹1,300 a sq ft gets you." (74) |
| Study | "Don't buy a study unit until you see what ₹1,300 a sq ft gets you." (74) |
| 2BHK | "Don't buy a 2BHK interior until you see what ₹3.5 lakh gets you." (82) |
| 3BHK | "Don't buy a 3BHK interior until you see what ₹4 lakh gets you." (88) |

## What changed vs the Oct 2026 reels (tell the tool to replace these exactly)
| | Smart Essentials | Signature Comfort | Forma Luxe |
|---|---|---|---|
| Kitchen /sq ft | 2,200 → **1,800** | 3,200 → **2,800** | 4,200 → **3,800** |
| Wardrobe /sq ft | 2,100 → **1,300** | 3,400 → **2,500** | 4,400 → **4,200** |
| TV unit /sq ft | 1,600 → **1,300** | 1,900 → **2,500** | 2,500 → **4,000** |
| Study /sq ft | 1,800 → **1,300** | 2,000 → **2,000** | 2,500 → **3,500** |
| Crockery /sq ft | 2,000 → **1,300** | 2,500 → **2,500** | 3,100 → **4,200** |
| 2BHK | 4.5 L → **3.5 L** | 6.5 L → **5.5 L** | 8.5 L → **8.5 L** |
| 3BHK | 6 L → **4 L** | 8 L → **7 L** | 10 L → **10 L** |
Materials also changed (Smart is now pre-laminated MDF for the four non-kitchen units).
Footer changes from "Oct 2026 rates" to "Nov 2026 rates".

---

## SHARED NOTE (paste before both prompts)

```
Update the existing Forma Studio package reels to the NOV 2026 rates. Reuse the existing
Remotion components and timing exactly (cream background, dark "lights on" Signature scene,
pendant lamp, gold locked dimension frame, upgrade scan, odometer price, chips, MOST CHOSEN
badge, end card). Replace every price, chip, material line and the tier images with the new
values below. Use ONLY these facts.

TIER IMAGES: crop each tier's picture from the new comparison sheets (one image per tier,
cropped to the cabinet drawing, upscaled lanczos 2x). The new sheets show some items that are
NOT included (lighting, extra drawers, dressing unit, etc.). Do not put those items in the
chips, and keep this footer on every price scene:
  "From prices + 18% GST · Nov 2026 rates · Lighting & items shown as extras quoted separately"

Each tier scene also gets a small material line under the price (Montserrat 30 px, gold),
and the Signature + Luxe scenes get a warranty chip.
Fixes from earlier reviews still apply: tier title/price/chips change on the same frame;
odometer starts at the Smart value; lamp cord never crosses text; CTA "Get your estimate ·
formastudio.site" held ≥ 2.5 s; no empty frames; text inside y 230–1440.
Export 1080x1920, 30 fps, two versions (music + silent).
```

---

## MOTION UPGRADE — paste after the Shared Note (makes every reel unique)

```
This series must look like nothing else on Instagram interiors. Keep the brand system
(cream/espresso/gold, serif + Montserrat, MOST CHOSEN, price footer) but give EACH reel its
own signature motion idea. All of it is buildable in Remotion with 2.5D layers, CSS 3D
transforms, SVG path drawing, clip-path masks and spring() easing.

GLOBAL MOTION LANGUAGE (all 7 reels)
- 2.5D depth: split every tier image into 3 layers (background wall, cabinet body, front
  props) using masks; move them at different speeds (parallax 4% / 8% / 14%) during a slow
  camera drift. Nothing is ever a flat still.
- Spring physics: chips, badges and prices enter with spring({damping: 14, mass: 0.6}),
  overshoot then settle. Never linear.
- Kinetic price: digits roll individually like a mechanical counter (each digit its own
  wheel with motion blur), gold glint sweeps across when it lands.
- Light as a character: a warm light beam (radial gradient, screen blend) travels across
  the cabinet when the tier upgrades; dust particles (40–60, slow drift) visible in the beam.
- Micro-sound on every motion (click, slide, soft thud, chime), timed to the frame.
- Hook text: each word drops in with a 3D flip (rotateX 90°→0°) staggered 3 frames.

SIGNATURE IDEA PER REEL (do not reuse between reels)
1 KITCHEN — "THE DRAWER REVEAL": tiers change by drawers sliding out in 3D (translateZ +
  shadow), each drawer front carrying the next tier name and price; closes on the new tier.
2 WARDROBE — "DOORS OPEN": wardrobe shutters swing open on 3D hinges (rotateY 0→-105°,
  perspective 1600) to reveal each tier's interior; mirror shutter catches a light flare.
3 TV UNIT — "SCREEN ON": the TV screen itself is the info panel — it powers on with a
  CRT-style line, shows tier name + price on screen, then the unit lights up around it.
4 CROCKERY — "GLASS & LIGHT": glass doors get a moving reflection sweep; shelves light up
  one by one bottom→top; plates "clink" into place (tiny spring bounce) on Signature/Luxe.
5 STUDY — "DESK LAMP": scene starts dark; a desk lamp clicks on, its light cone reveals
  each tier; price written by a pen-stroke animation (SVG path) on a notepad card.
6 2BHK — "BLUEPRINT TO 3D": floor plan draws in gold, then walls extrude upward into an
  isometric 3D model (CSS 3D, 30° tilt); camera flies room to room as each unit drops in.
7 3BHK — "ONE MORE ROOM": opens on the finished 2BHK model, which slides apart to make room
  for a third bedroom that builds itself; then the same flythrough and price board.

END CARD (all): the F of the logo is drawn as a gold line (SVG stroke), the rest of the
logo fades in, CTA rises on a spring. Hold ≥ 2.5 s.
Keep every text element readable for at least 1.2 s — motion must never hide a price.
```

## PROMPT A — five unit reels (16 s each)

```
KITCHEN — frame Run A 120" · Run B 108" · 96" height
  Hook: "DON'T BUY A KITCHEN" / "until you see what ₹1,800 a sq ft gets you."
  Smart Essentials ₹1,800/sq ft — HDHMR pre-laminated 16 mm
    chips: Internal shelves · Soft-close hinges · Sink cabinet
  Signature Comfort ₹2,800/sq ft (MOST CHOSEN, LIGHTS ON) — Sainik 710 BWP
    chips: Acrylic shutters · 12 mm + WPC double back · Hettich hardware
  Forma Luxe ₹3,800/sq ft — Archidply BWP
    chips: PU / glass shutters · Blum hinges · Hettich runners

WARDROBE — frame 72" width · 84" height
  Hook: "DON'T BUY A WARDROBE" / "until you see what ₹1,300 a sq ft gets you."
  Smart Essentials ₹1,300 — Pre-laminated MDF
    chips: Hanging rods · Mirror on one shutter · 1 drawer
  Signature Comfort ₹2,500 (MOST CHOSEN) — HDHMR 16 mm · 5-year wood warranty
    chips: 2 drawers · Tie & belt organiser · Aluminium profile handles
  Forma Luxe ₹4,200 — HDHMR 18 mm
    chips: Mirror pull-out · Jewellery / watch tray · 2 Blum Tandembox drawers

TV UNIT — frame 72" width · 60" height
  Hook: "DON'T BUY A TV UNIT" / "until you see what ₹1,300 a sq ft gets you."
  Smart Essentials ₹1,300 — Pre-laminated MDF
    chips: Closed storage · Cable holes · Basic handles
  Signature Comfort ₹2,500 (MOST CHOSEN) — HDHMR 16 mm · 5-year wood warranty
    chips: Closed storage + open niche · Floor or wall-hung · Hettich soft-close
  Forma Luxe ₹4,000 — HDHMR 18 mm
    chips: Wall-hung floating unit · Glass display · Concealed cable channel

CROCKERY UNIT — frame 48" width · 72" height
  Hook: "DON'T BUY A CROCKERY UNIT" / "until you see what ₹1,300 a sq ft gets you."
  Smart Essentials ₹1,300 — Pre-laminated MDF
    chips: Closed storage · Open niche · 1 drawer
  Signature Comfort ₹2,500 (MOST CHOSEN) — HDHMR 16 mm · 5-year wood warranty
    chips: Glass doors, wooden frame · Cutlery tray · Contrast niche back
  Forma Luxe ₹4,200 — HDHMR 18 mm
    chips: Fluted / tinted glass · 2 Blum Tandembox drawers · Wine + plate rack

STUDY UNIT — frame 48" width · 72" height
  Hook: "DON'T BUY A STUDY UNIT" / "until you see what ₹1,300 a sq ft gets you."
  Smart Essentials ₹1,300 — Pre-laminated MDF
    chips: Worktop · Open shelves · 1 drawer
  Signature Comfort ₹2,000 (MOST CHOSEN) — HDHMR 16 mm · 5-year wood warranty
    chips: Overhead shelf · Cable grommet · Soft-close drawer
  Forma Luxe ₹3,500 — HDHMR 18 mm
    chips: 36 mm thick-look worktop · Glass overhead cabinet · Keyboard tray + pin-up board

File names: Forma-Kitchen-Nov26.mp4, Forma-Wardrobe-Nov26.mp4, Forma-TVUnit-Nov26.mp4,
Forma-Crockery-Nov26.mp4, Forma-Study-Nov26.mp4 (+ "-Silent").
```

---

## PROMPT B — 2BHK and 3BHK (29 s each, existing floor-plan template)

```
Keep the Week 3 / Week 4 template (floor plan draws itself, items drop into rooms with a
counter, lights on, departure-board prices, trust strip, CTA). Change only:

2BHK — Hook: "DON'T BUY A 2BHK INTERIOR" / "UNTIL YOU SEE WHAT ₹3.5 LAKH GETS YOU"
  Drop-in: Kitchen (75 sq ft) · Wardrobe 6×7 ft ×2 · TV unit + wall panel · Crockery 4×6 ft
           · Study 4×6 ft  → counter "6 ITEMS. ONE PACKAGE."
  Price board: SMART ESSENTIALS ₹3,50,000 · SIGNATURE COMFORT ₹5,50,000 (MOST CHOSEN)
               · FORMA LUXE ₹8,50,000 — each "+ 18% GST"
  Lines under each: "Pre-laminated MDF · 2-yr warranty" / "HDHMR + acrylic · 5-yr warranty"
                    / "HDHMR 18 mm + PU · Blum · 5-yr warranty"

3BHK — Hook: "DON'T BUY A 3BHK INTERIOR" / "UNTIL YOU SEE WHAT ₹4 LAKH GETS YOU"
  Drop-in: Kitchen (80 sq ft) · Wardrobe 6×7 ft ×3 · TV unit + wall panel · Crockery 4×6 ft
           · Study 4×6 ft  → counter "7 ITEMS. ONE PACKAGE."
  Price board: SMART ESSENTIALS ₹4,00,000 · SIGNATURE COMFORT ₹7,00,000 (MOST CHOSEN)
               · FORMA LUXE ₹10,00,000 — each "+ 18% GST"
  Same lines under each tier as 2BHK.

Both: footer "Nov 2026 rates · Transport ₹2,000 per project · Lighting quoted separately".
File names: Forma-2BHK-Nov26.mp4, Forma-3BHK-Nov26.mp4 (+ "-Silent").
```

Confirmed by Forma (Nov 24): 45-day target delivery still valid — keep it in the 2BHK/3BHK
trust strip as "45-day target delivery*" with "*subject to approved drawings & site readiness".
Kitchen Smart = HDHMR pre-laminated 16 mm (correct as printed).
