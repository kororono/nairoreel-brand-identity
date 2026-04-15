# Nairoreel Treatment System

The system that makes every post look like it passed through the same machine.
Two universal rules. One rescue stack. Four named treatments. One filter.

---

## Universal Base — Every Post, No Exceptions

Before anything else, every post on the grid gets these two things:

| Layer | Spec |
|---|---|
| Black border frame | 6px solid #000000, inset on all four edges |
| Film grain overlay | Noise texture at 15% opacity, monochromatic grain |

These two alone are enough for posts that are already close to the visual identity.
If a post looks right with just border + grain, stop there.

---

## Colour Rescue Stack

When the source image colour is too far from the brand (too bright, too saturated, wrong temperature) — apply levels in order. Stop as soon as the post fits the grid.

```
Level 0  →  Border + grain alone
              Try this first. Often enough.

Level 1  →  Row-level identity
              Put the post in a row where the campaign colour carries the group.
              Border + grain + row cohesion does the work.

Level 2  →  Desaturation
              Reduce image saturation 30–60%. Pull it toward neutral dark.
              Keep the border and grain.

Level 3  →  Monochrome + accent typography (last resort)
              Desaturate fully to monochrome. Add minimal type in #EA1821 or white.
              Only add text if the image genuinely cannot stand alone.
              Avoid text if you can.
```

**The split rule:** If a single post or project cannot fit the visual identity at any rescue level without looking forced → split that project into 3 posts. A full row of related content gives you row-level identity to compensate, plus border + grain + filter ties it together.

---

## Named Treatments

Use these for specific content types on top of the universal base.

### Treatment A — Dark Frame + Label
*For colourful client work that can't be changed. Brings it into the brand world.*

- Universal base (border + grain)
- Eyebrow label: Montserrat 700, ALL CAPS, white, 1.5px letter-spacing, 10–12px
- Red accent line: 2px solid #EA1821, horizontal, separating label from image
- Logomark: bottom-right, 8% canvas width, white version only
- No overlay on the image — let the content breathe inside the frame

### Treatment B — Dark Overlay + Typography Hero
*For strong visuals that need editorial framing or context.*

- Universal base (border + grain)
- Dark overlay on image: 45–60% opacity #000000
- Playfair Display headline: 900 weight, white, tight tracking, 2–4 words
- Optional: small Montserrat label above the headline, ALL CAPS, #EA1821

### Treatment C — Studio Card Split
*For hero shots that need context — makes the post feel like a studio deliverable.*

- Universal base (border + grain)
- Image occupies 55–65% of the post (top or left)
- Solid #111111 panel occupies remaining 35–45%
- In the panel: Montserrat eyebrow label (ALL CAPS, tracked) + Playfair headline + optional one-line descriptor in Montserrat 300
- Red accent line (#EA1821, 2px) between eyebrow and headline

### Treatment D — Full Dark Composition
*For new planned content — gives maximum brand control.*

- Full brand palette background (choose: #000000, #0A0A0A, #180161, #4F1787)
- Image composited in — treated as a design element, not a document
- Typography as part of the composition, not an overlay
- Universal base grain applied to the whole composition
- Used for rows planned from scratch, not retrofitted existing content

---

## The Nairoreel Filter

A reusable post-production layer applied to thumbnails and post images to pull them together visually. Applied at the design stage — not as an afterthought.

**Components:**
| Layer | Setting |
|---|---|
| Film grain | Monochromatic noise, 15% opacity |
| Colour grade — blacks | Deepen: lift shadows down, crush blacks slightly |
| Colour grade — saturation | Reduce by 15–20% globally |
| Colour grade — temperature | Slight cool shift (toward blue-grey, not cyan) |
| Border | 6px solid #000000 inset |

**Strength levels:**

| Strength | When to use | Grain | Saturation cut | Grade intensity |
|---|---|---|---|---|
| Low | Post is already close to identity | 10% | 10% | Subtle |
| Medium | Standard application — most posts | 15% | 20% | Moderate |
| High | Rescue mode — image fights the grid | 20% | 35–50% | Strong, may push toward Level 2 desaturation |

**The filter is not optional.** Every post gets at least Low strength.
High strength + full desaturation = Level 2 of the colour rescue stack.

---

## Decision Flow

```
New post or thumbnail to design?
        ↓
Is the source image close to the brand palette?
   YES → Apply universal base (border + grain, filter Low). Done.
   NO  ↓
Can row-level identity carry it? (Level 1)
   YES → Place in matching row, apply base. Done.
   NO  ↓
Does desaturation (Level 2) bring it into the grid?
   YES → Desaturate 30–60%, apply base. Done.
   NO  ↓
Can you choose a different scene or thumbnail from the same project?
   YES → Use the better scene. Start over.
   NO  ↓
Can this project be split into 3 posts for a full row?
   YES → Split. Plan the row. Apply row identity + base.
   NO  ↓
Apply Level 3: monochrome + minimal accent type.
```

---

## What You Must Never Do

1. Post a raw export to the grid without border + grain applied
2. Use a font other than Playfair Display or Montserrat
3. Add text to a post where the image can stand alone
4. Place the logomark anywhere other than bottom-right
5. Use a colour not in the brand palette for any design element
6. Post an event flyer or client deliverable directly — frame it (Treatment A) or move it to stories
