# Teaser stills — clean-up + one colour grade (before building the Dec 4 teaser)

Order of work: 1) colour grade (DONE — Forma_teaser_stills_refpalette.zip, reference palette) → 2) remove clutter
(AI image editor, prompt below) → 3) upscale → 4) build the teaser with
teaser-dec4-prompt.md using the cleaned stills.

## Colour palette = the REFERENCE teaser (not the website)
Measured from the reference teaser: matte, airy, warm-greige.
- Shadows lifted to soft warm brown (about RGB 40–60) — never pure black.
- Mid-tones warm greige with a slight rosy-beige bias (about RGB 145/136/128).
- Highlights soft neutral white, capped around RGB 225 — never blown out.
- Low saturation, soft contrast.

DONE: all 20 stills already graded to this palette — Forma_teaser_stills_refpalette.zip.
Method (to re-apply in your tool, e.g. on video): match each image's Lab colour
statistics to the reference (L mean 54.9 / std 24.8, a mean 1.6 / std 3.5, b mean 5.3 /
std 4.5) at 85% strength, then matte curve: output = 0.15 + 0.74 × input (lifted blacks,
whites capped at ~0.89).
Note: this palette mutes strong colours — the navy TV wall reads slate-mauve and the
bedsheets go soft. That matches the reference look.

---

## PROMPT — paste into your AI image editor (Gemini / "banana" skill / Photoshop
## Generative Fill / iPhone Photos "Clean Up"), one image at a time

```
Edit this interior photo of a real Forma Studio project. Remove ONLY the items listed
below and fill the area so it matches the surrounding wall, floor or surface naturally
(same texture, lighting and perspective).
STRICT RULES:
- Do NOT change any cabinet, shutter, handle, panel, shelf or headboard — same shape,
  size, colour, finish and position.
- Do NOT add any new objects, decor, lighting or furniture.
- Do NOT change the colour grade, the camera angle or the framing.
- Output the same resolution as the input.
Remove: {{items for this image — see table}}
```

| Still | Remove | Then crop |
|---|---|---|
| K3a | — | — |
| K3b | — | — |
| K3c | — | — |
| K3d | — | — |
| K3e | — | — |
| K4a | — | — |
| K4b | — | — |
| K4c | striped floor mat | — |
| K4d | steel water pot at bottom-left | — |
| K1a | striped floor mat | — |
| K1b | striped floor mat; blue/silver water pot near the sink | — |
| L1a | loose cable under the switch plate; yellow item on the right desk | — |
| L1b | — | — |
| L1c | set-top box, cables and charger under the TV unit; loose wire below the TV | crop the white table corner out of the bottom-left |
| L1d | UPS and power strip on the bottom shelf | crop the white table out of the bottom |
| B1a | — | crop to the upper 60% (headboard + mirror), so the bedsheet is out |
| B2a | — | vertical crop on the headboard |
| W1a | cardboard boxes on top of the wardrobe | crop the bedsheet out of the bottom |
| V1a | green/white label sticker on the basin | — |
| V2a | green/white label sticker on the basin | — |
People (team member in K4a–K4d, arm in K3c): keep them — do not remove people with AI.

## After clean-up
- Upscale every still to 1080x1920 with an AI upscaler (Real-ESRGAN x2, "photo" model),
  light denoise, light sharpen. The DJI stills (K1, K3) start at 816 px wide and need it most.
- Check each still at 100% zoom for AI smears, warped edges or changed handles; redo any
  that look wrong.
- Then build the teaser with teaser-dec4-prompt.md using the cleaned stills.

## Instagram note
Generative-AI edits can add metadata that makes Instagram show an "AI info" label. If the
label appears on upload, leave it on — never hide that AI edits were used.
