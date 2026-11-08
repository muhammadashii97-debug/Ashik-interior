# Forma Studio — Packages launch week: 7 daily reels

| Day | Date | Reel | Source |
|---|---|---|---|
| Mon | Nov 9 | Kitchen | split from Week 1 |
| Tue | Nov 10 | Wardrobe | split from Week 1 |
| Wed | Nov 11 | TV unit | split from Week 2 |
| Thu | Nov 12 | Crockery unit | split from Week 2 |
| Fri | Nov 13 | Study unit | split from Week 2 |
| Sat | Nov 14 | 2BHK whole home | Week 3 (fixes only) |
| Sun | Nov 15 | 3BHK whole home | Week 4 (fixes only) |

Paste PROMPT A once for the five unit reels, PROMPT B once for the two whole-home reels.
Attach the existing Remotion project (Week 1, 2, 3, 4) so the tool reuses the same
components, colours, pendant lamp, scan wipe and music style.

---

## PROMPT A — split Week 1 and Week 2 into five single-unit reels

```
Split the existing Forma Studio package reels into FIVE standalone reels, one unit each:
Kitchen, Wardrobe, TV unit, Crockery unit, Study unit. Reuse the existing Remotion
components exactly (cream background, dark "lights on" Signature scene, pendant lamp,
gold locked dimension frame, upgrade scan wipe, odometer price, feature chips, MOST
CHOSEN badge). Each reel must work on its own — no references to other units.

FORMAT (all five)
- 1080x1920, 30 fps, H.264. Two versions each: original music and silent.
- Length 16 s. Timeline:
  0:00–0:02.2   HOOK on frame 1 (two lines, see per-unit below) over the Smart
                Essentials image with the gold dimension frame drawing itself.
  0:02.2–0:05.6 SMART ESSENTIALS — price + 3 chips.
  0:05.6–0:09.8 UPGRADE SCAN → SIGNATURE COMFORT — LIGHTS ON (dark scene) —
                MOST CHOSEN badge — price + 3 chips. Hero tier: longest hold.
  0:09.8–0:13.2 UPGRADE SCAN → FORMA LUXE — price + 3 chips.
  0:13.2–0:16.0 END CARD: Signature Comfort unit lit, "SAME SIZE. THREE STORIES."
                + CTA pill "Get your estimate · formastudio.site" fully visible for
                at least 2.5 s. Footer "From prices + 18% GST · Oct 2026 rates ·
                Machine finish extra". No separate loop-word frame — the CTA is last.
- Music (Python, original): new 16 s cue per reel at 100 BPM, same instruments as
  before, accents on each scan and a chime at lights-on. Fade out last 1.2 s. -14 LUFS.

FIXES (apply to every reel)
1. Tier title, price and chips change on the SAME frame. The price counter starts at the
   Smart Essentials value — never shows ₹0,000. Odometer roll max 12 frames.
2. The pendant-lamp cord never crosses text (keep 40 px clearance).
3. Text sizes at 1080 width: hook 88 px, tier title 64 px, price 72 px, unit label
   36 px, chips 38 px, footer 30 px.
4. Unit image at 85% of frame width; centre the whole stack between y 230 and y 1440;
   keep the right 230 px free of text.
5. No empty, grey or logo-only frames anywhere.

PER-UNIT CONTENT (use only these facts)

KITCHEN — frame Run A 120" · Run B 108" · 96" height
  Hook: "DON'T BUY A KITCHEN" / "until you see what ₹2,200 a sq ft gets you."
  Smart Essentials ₹2,200/sq ft + 18% GST: 1 tandem drawer · Cutlery + thali organiser
    · Sainik MR + laminate
  Signature Comfort ₹3,200: Bottle pull-out · Built-in bin · 710 BWP + acrylic
  Forma Luxe ₹4,200: 1 premium mechanism · 2 tandem drawers · Club Prime + PU / glass

WARDROBE — frame 72" width · 84" height
  Hook: "DON'T BUY A WARDROBE" / "until you see what ₹2,100 a sq ft gets you."
  Smart Essentials ₹2,100: 2 hanging sections · Door mirror · Sainik MR + laminate
  Signature Comfort ₹3,400: Integrated dressing · Mirror storage · 710 BWP + acrylic
  Forma Luxe ₹4,400: Pull-down hanging · Tie / belt organiser · Club Prime + PU / glass

TV UNIT — frame 72" width · 60" height
  Hook: "DON'T BUY A TV UNIT" / "until you see what ₹1,600 a sq ft gets you."
  Smart Essentials ₹1,600: 2 drawers · 2 shutters · Simple wall panel
  Signature Comfort ₹1,900: Open display tower · Feature panel · 710 BWP + acrylic
  Forma Luxe ₹2,500: Floating display ledge · Premium display tower · Club Prime + PU

CROCKERY UNIT — frame 48" width · 72" height
  Hook: "DON'T BUY A CROCKERY UNIT" / "until you see what ₹2,000 a sq ft gets you."
  Smart Essentials ₹2,000: Open serving niche · Upper + lower shelves · Sainik MR
  Signature Comfort ₹2,500: Framed glass display · Organised closed storage
    · 710 BWP + acrylic / glass
  Forma Luxe ₹3,100: Twin glass display bays · Premium lower storage
    · Club Prime + PU / glass

STUDY UNIT — frame 48" width · 72" height
  Hook: "DON'T BUY A STUDY UNIT" / "until you see what ₹1,800 a sq ft gets you."
  Smart Essentials ₹1,800: 2 drawers · Open desk · Sainik MR + laminate
  Signature Comfort ₹2,000: 3-level display · Soft-close drawers · 710 BWP + acrylic
  Forma Luxe ₹2,500: Floating book ledge · Premium drawers · Club Prime + PU

File names: Forma-Kitchen.mp4, Forma-Wardrobe.mp4, Forma-TVUnit.mp4,
Forma-Crockery.mp4, Forma-Study.mp4 (+ "-Silent" versions).
```

---

## PROMPT B — fix the 2BHK and 3BHK reels (Week 3 and Week 4)

```
Revise the existing Week 3 (2BHK) and Week 4 (3BHK) reels. Keep the concept, timing,
floor plan, drop-in counter and departure-board prices exactly as they are. Only fix:
1. End: hold the CTA pill ("Get your 2BHK estimate" / "Get your 3BHK estimate" ·
   formastudio.site) fully visible for at least 2.5 s. Shorten the final loop word
   ("2BHK" / "3BHK") to 0.5 s.
2. Remove the empty cream frame at the dark→cream switch (~0:16–0:17): crossfade
   straight from the lit floor plan into the price board.
3. Price odometer: roll max 12 frames so no wrong in-between totals are readable.
4. The pendant-lamp cord never crosses text (40 px clearance).
5. Text sizes at 1080 width: price 72 px, tier name 36 px, trust strip 42 px,
   floor-plan room labels 30 px, footer 30 px.
6. Scale the floor plan to 85% of frame width, centred between y 230 and y 1440.
7. 3BHK only: the opening callback ("ONE MORE room.") stays — it now follows the 2BHK
   reel posted the day before.
Re-export both: Forma-2BHK.mp4, Forma-3BHK.mp4 (+ "-Silent" versions).
```
