# Nairoreel — Nano Banana Master Prompt

Copy the relevant block below into Nano Banana. Always attach the source image.
The INSTRUCTION block is constant. Swap the TREATMENT block per post.

---

## CONSTANT — Paste at the top of every prompt

```
INSTRUCTION: You are applying Nairoreel Productions' brand treatment system to the attached image. This is ADDITIVE design work — preserve all existing image content exactly as it appears. Do not remove, replace, alter, or recompose any part of the original image. Every change is layered on top.

BRAND TOKENS:
- Primary: #000000 Black
- Accent: #EA1821 Red
- Light: #FFFFFF White
- Surface: #0A0A0A Dark
- Card: #111111 Dark Card
- Extended: #180161 Midnight | #4F1787 Violet | #FB773C Orange | #EB3678 Pink
- Display font: Playfair Display — 900 weight, tight tracking
- UI font: Montserrat — 700 weight, ALL CAPS, wide letter-spacing for labels
- Logo placement (if added): bottom-right corner, 8% of canvas width, white version only

UNIVERSAL BASE (apply to every post):
1. Add a 6px solid #000000 border frame inset on all four edges of the image
2. Apply a subtle monochromatic film grain / noise texture overlay at 15% opacity across the entire image
```

---

## TREATMENT BLOCKS — Swap per post

### Filter Low (post is already close to brand)
```
TREATMENT — FILTER LOW:
Apply the universal base. Then apply a light cinematic colour grade: deepen blacks slightly, reduce global saturation by 10%, apply a very subtle cool temperature shift. Keep it natural — the image should still feel like itself, just more cohesive.
```

---

### Filter Medium (post needs pulling in)
```
TREATMENT — FILTER MEDIUM:
Apply the universal base. Then apply a moderate cinematic colour grade: deepen blacks, reduce global saturation by 20%, apply a cool temperature shift (push slightly toward blue-grey, not cyan). The image should feel like it passed through the same camera as the rest of the grid.
```

---

### Filter High + Desaturation (rescue mode)
```
TREATMENT — FILTER HIGH:
Apply the universal base. Then apply a strong cinematic colour grade: crush the blacks, reduce global saturation by 40–50%, strong cool temperature shift. The image should move significantly toward neutral dark. This is rescue mode — prioritise grid cohesion over preserving the original colour temperature.
```

---

### Monochrome + Accent Type (Level 3 — last resort)
```
TREATMENT — MONOCHROME + ACCENT:
Apply the universal base. Desaturate the image fully to monochrome (greyscale). Then add minimal typography:
- Short ALL CAPS label in Montserrat 700, #EA1821 red, tight letter-spacing, positioned bottom-left
- 2px horizontal #EA1821 accent line above the label
No other text. Do not add a headline unless the image genuinely cannot stand alone.
```

---

### Treatment A — Dark Frame + Label
```
TREATMENT A — DARK FRAME + LABEL:
Apply the universal base + Filter Medium colour grade. Then add:
- Eyebrow label: Montserrat 700, ALL CAPS, white, 1.5px letter-spacing, 11px size — infer a short label from the image content (e.g. "PRODUCTION" / "CLIENT WORK" / "BRAND FILM")
- 2px solid #EA1821 horizontal accent line directly above the label
- Both positioned bottom-left, 20px from the edge, consistent margin
Do NOT add a headline. Do NOT add a logo unless specified. Let the image breathe.
```

---

### Treatment B — Dark Overlay + Typography Hero
```
TREATMENT B — DARK OVERLAY + TYPOGRAPHY HERO:
Apply the universal base. Then:
- Apply a 50% opacity #000000 overlay across the image
- Add a bold Playfair Display headline, 900 weight, white, 2–4 words, editorial tone — infer from image content
- Position: centre-left or bottom-left, large scale
- Optional: small Montserrat ALL CAPS label in #EA1821, 10px, above the headline with a 1px gap
Apply Filter Low grade on top (the overlay handles most of the colour work).
```

---

### Treatment C — Studio Card Split
```
TREATMENT C — STUDIO CARD SPLIT:
Apply the universal base to the image portion. Then:
- Crop the image to occupy 60% of the canvas (top portion or left portion)
- Add a solid #111111 panel occupying the remaining 40%
- In the panel, add:
  - Montserrat 700 ALL CAPS eyebrow label, white, tracked — infer from image (e.g. "3D VISUALISATION" / "ARCHITECTURE")
  - 2px #EA1821 accent line below the label
  - Playfair Display headline, 700 weight, white, 2–4 words
  - Optional: one-line descriptor in Montserrat 300, #888888, below the headline
- Apply Filter Low grain to the panel as well so it matches the image portion
```

---

### Treatment D — Full Dark Composition
```
TREATMENT D — FULL DARK COMPOSITION:
Do not use the source image as a background. Instead:
- Create a full brand palette background using [SPECIFY: #000000 / #0A0A0A / #180161 / #4F1787]
- Composite the source image into the composition as a design element — cropped, masked, or treated
- Apply the universal base grain across the entire composition
- Add typographic elements using Playfair Display and Montserrat as needed
- The source image is a component, not the canvas
```

---

## Row Campaign Colour Grades

Add one of these to the colour grade instruction to tie a row together:

**Dark Red Row:** `Shift shadow tone slightly warm-red. The blacks should have a faint red undertone, not neutral black.`

**Midnight Row:** `Shift shadow tone toward deep blue-violet. Blacks should have a faint #180161 midnight undertone.`

**Neutral Dark Row:** `Keep the grade strictly neutral — no colour cast in shadows. Pure cool-neutral dark.`

**Orange Burst Row:** `Allow warm amber-orange tones to remain or be amplified slightly in highlights. Shadows stay dark and neutral.`

---

## How to Use

1. Copy the CONSTANT block
2. Add the TREATMENT block for this specific post
3. Add the ROW CAMPAIGN colour grade if this post is part of a row
4. Attach the source image
5. Send

Example — Post 3 (golden hour portrait, Row 3 Neutral Dark):

```
INSTRUCTION: [paste constant block]

TREATMENT — FILTER MEDIUM:
Apply the universal base. Then apply a moderate cinematic colour grade: deepen blacks, reduce global saturation by 20%, apply a cool temperature shift. The image should feel like it passed through the same camera as the rest of the grid.

ROW: Keep the grade strictly neutral — no colour cast in shadows. Pure cool-neutral dark.
```
