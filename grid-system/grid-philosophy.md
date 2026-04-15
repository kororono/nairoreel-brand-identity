# Instagram Grid System

## Core Principle

The grid is the portfolio. Every visitor lands on a 3-column grid that tells them
immediately: this is a studio, not a person with a camera.

**Rule:** No post goes live without a design layer — colour treatment, typography,
or graphic element applied over or alongside the raw image/render.

---

## Grid Structure

- 3 columns × N rows
- Cell gap: 3px (IG default)
- Each post: 1:1 square (1080×1080px at 72dpi for IG, 300dpi for print use)

---

## Row Campaigns

A "campaign" is a row of 3 posts designed to read as a unit when viewed on the grid.
Each campaign has:
- A shared **colour theme** (background + accent)
- A shared **content type** (e.g. BTS, finished renders, process)
- Consistent **typography treatment** across all 3 cells

### Campaign Templates (Starter Set)

| Campaign Name     | BG        | Accent    | Content Type        |
|-------------------|-----------|-----------|---------------------|
| Dark Red          | `#0D0D0D` | `#EA1821` | Hero renders / promos |
| Midnight          | `#0A0016` | `#180161` | Deep cinematic work |
| Neutral Dark      | `#111111` | —         | Process / behind scenes |
| Orange Burst      | `#0D0D0D` | `#FB773C` | Motion / energy content |

---

## Post Anatomy

Every post should have these zones considered:

```
┌─────────────────────┐
│  [EYEBROW LABEL]    │  ← Montserrat 700 ALL CAPS, 10px, Red
│                     │
│  MAIN VISUAL        │  ← 3D render / footage still / graphic
│                     │
│  [HEADLINE TEXT]    │  ← Playfair Display 700–900
│  [Sub / Meta]       │  ← Montserrat 400–600
│                     │
│           [LOGO]    │  ← Bottom right or bottom left
└─────────────────────┘
```

Elements are optional but at minimum: visual + one text element.

---

## Grid Planning Process

1. Decide next 3 posts = one row
2. Choose campaign theme for that row
3. Sketch layout in `grid-system/` as a simple text table or sketch
4. Design in Nano Bannana using that campaign's colour tokens
5. Export to `outputs/posts/`

---

## Content Cadence (Reference)

Pulled from platform-context.md in the script skill — adapt as needed:

| Frequency    | Content Type                        |
|--------------|-------------------------------------|
| 3×/week      | Reels (short-form, algorithm-driven)|
| 2×/week      | Posts (portfolio, process, promos)  |
| Daily        | Stories (engagement, BTS, polls)    |

---

## Decisions To Make

- [ ] Confirm row campaign themes (3–4 total)
- [ ] Decide logo placement rule (corner vs centred vs bottom bar)
- [ ] Decide if alternate posts use full-bleed image vs dark surface treatment
- [ ] Set pinned post strategy (top 3 posts on grid)
- [ ] Confirm aspect ratio for Reels covers (portrait crop shown on grid)
