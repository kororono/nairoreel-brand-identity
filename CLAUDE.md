# Nairoreel — Brand Identity System

## What This Project Is

Building a studio-level Instagram presence for Nairoreel Productions.
The goal: a grid that looks intentionally designed — cohesive colour, consistent
thumbnail treatment, and typography that signals "high-end production studio"
at a glance. Not raw exports. Every post gets graphic design treatment.

The deliverable is a replicable system so any post can be made to look like
it belongs on the same page.

---

## Folder Structure

```
Brand Identity/
  references/                ← Screenshots of IG pages we're drawing inspiration from
  brand-tokens/              ← Colour, type, spacing rules distilled into usable specs
  grid-system/               ← Grid planning: row themes, cell patterns, content cadence
  templates/                 ← Reusable post/thumbnail layout templates (for Nano Bannana)
  assets/
    fonts/                   ← Font files (Playfair Display, Montserrat)
    logos/                   ← Nairoreel logo variants
    textures/                ← Grain overlays, noise textures, gradients
  outputs/
    posts/                   ← Finished square posts (1:1)
    thumbnails/              ← YouTube / Reels cover frames (16:9 or 9:16)
    reels-covers/            ← IG Reels cover thumbnails (portrait)
  nano-bannana/              ← Nano Bannana workspace files and export configs
  nairoreel-brand-kit-v1.html ← Original brand kit HTML (foundation, not fully finalised)
```

---

## Source of Truth

`nairoreel-brand-kit-v1.html` is the current brand foundation — treat it as a
*starting point*, not gospel. Some decisions in there are not yet locked in.
As decisions get confirmed, they get written into `brand-tokens/`.

---

## Brand Tokens (Quick Reference)

### Colours

| Role            | Name     | Hex       |
|-----------------|----------|-----------|
| Primary         | Black    | `#000000` |
| Accent          | Red      | `#EA1821` |
| Light           | White    | `#FFFFFF` |
| Off-white       | Off-White| `#F2F0ED` |
| Extended        | Midnight | `#180161` |
| Extended        | Violet   | `#4F1787` |
| Extended        | Orange   | `#FB773C` |
| Extended        | Pink     | `#EB3678` |
| Surface         | Dark     | `#0A0A0A` |
| Card            | Dark Card| `#111111` |

### Typography

| Role       | Font             | Weight/Style          |
|------------|------------------|-----------------------|
| Display    | Playfair Display | 900, tight tracking   |
| Display    | Playfair Display | 400 italic, editorial |
| UI / Body  | Montserrat       | 300–800               |
| Labels     | Montserrat       | 700, ALL CAPS, tracked|

### Grid System (IG)
- Posts: 1:1 square
- Reels covers: 9:16 portrait
- Grid reads in rows of 3 — each row is a visual "campaign"
- Gap between cells: 3px (mirrors IG default)
- Every post has: typography element + brand colour application
  (no raw images without design treatment)

---

## Workflow (Nano Bannana Integration)

1. Plan grid row in `grid-system/`
2. Design template in Nano Bannana, save workspace to `nano-bannana/`
3. Export finished assets to `outputs/`
4. Document any new system decisions in `brand-tokens/`

---

## References We're Drawing From

- `young media ke` — clean dark aesthetic, strong grid cohesion
- `openbook studio` — studio-level thumbnail treatment
- `mylenesmind` — typographic consistency across posts

Reference screenshots in `references/`.

---

## Token Efficiency Rules (inherited from NRR project)

- Do not explain what you are about to do — just do it
- Do not summarize completed steps
- Write complete files in one shot
- Ask one clarifying question if stuck
