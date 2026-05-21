# Pocket Weather Chorus — 21 May 2026

A tiny soundless weather-orchestra composer that fits in your pocket. Choose
weather voices (drizzle, sunbeam, windbell, cloud, ember), arrange them on a
small two-row stave, tune the mood and intensity, then "sing" a tiny
deterministic forecast poem.

## What it is

- A single, self-contained HTML page
- Animated SVG glyphs (no audio APIs, no real sound)
- Five weather voices to choose from
- A 5×2 stave with up to 10 tiles
- Two sliders: **Mood** (still grey → gold high) and **Intensity** (a hush →
  full sky)
- Deterministic poem + named card per arrangement (same state → same forecast)

## Privacy-safe inspiration

The brief used only generic themes: *fresh start*, *morning curiosity*,
*playful systems*, *calm exploration*, *tiny creative ritual*. No names,
quotes, contacts, finance, or private details are referenced. All language is
weather/season imagery.

## How to open

1. Open `index.html` in any modern browser (Safari, Chrome, Firefox).
2. Works fully offline — no server, no install, no fonts or assets downloaded.
3. Best viewed on a phone (mobile-first at 390 px), but the layout breathes
   gracefully wider.

## Controls

- **Voice palette** (top row): tap a voice to select it. The selected voice
  glows gold.
- **Stave** (5×2 cells): tap any cell to place the selected voice there. Tap
  again with the same voice to clear it; tap with a different voice to swap.
- **Mood slider**: shifts the background tint and chooses softer or brighter
  imagery in the poem.
- **Intensity slider**: sets the small ribbon-volume above each tile and shapes
  the poem's tone.
- **Sing the forecast**: composes a 3-line poem and gives it a small name and
  serial number.
- **Shuffle**: scatters a small random arrangement to play with.
- **Clear**: empties the stave.

## Why it was built

A daily creative-coding ritual: one small, polished, self-contained browser
artifact per day. This one explores how weather words become a tiny
performance — voices placed in space, tuned, and sung as text. The point is
not utility but a two-or-three-minute pause: arrange, listen with your eyes,
mint a card, move on.

## Notes

- Deterministic: a given stave + mood + intensity always produces the same
  forecast. Move one tile and the poem changes.
- Accessibility: 44 px+ touch targets, `prefers-reduced-motion` honored,
  keyboard support on stave cells.
- No network, no storage, no analytics.
