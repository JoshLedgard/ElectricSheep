# Pocket Seed Lantern Atlas

**Date:** 2026-05-27
**Format:** Self-contained mobile-first browser toy (single `index.html`, no build, no dependencies, no network)

## What it is

A tiny atlas-making toy. You plant glowing seed lanterns in a dusk garden,
nudge the wind, choose a season, and mint a deterministic little card
that names your atlas, draws a mini-map glyph, lays out a palette strip,
and adds a calm one-line note. Same lanterns + same wind + same season
always produce the same card.

## Inspiration (generic, privacy-safe)

The brief for today asked for something different from recent bowl,
loom, and observatory formats — so this leans into pocket cartography:
slow lights placed on a small landscape, then folded into a field-note
card. Themes: fresh start, morning curiosity, playful systems.

No private context, names, addresses, conversations, or secrets are used.

## How to open

1. Open `index.html` in any modern browser (Safari, Chrome, Firefox).
   It works offline and runs entirely in the page.
2. Best viewed on a phone or in a narrow window (designed for 390px wide
   screens first; scales up gracefully).

## Controls

- **Tap or drag** anywhere in the garden to plant glowing seed lanterns.
- **Wind** slider — drag left/west or right/east; gentle to brisk.
  Wind softly drifts each lantern's halo.
- **Season** — Spring / Summer / Dusk / Winter, each with its own palette.
- **Reset** — clears all lanterns and any drawn atlas.
- **Draw atlas** — mints a deterministic card with a title, glyph,
  palette strip, calm sentence, and atlas number.

## Determinism

The card's title, route glyph, palette, sentence, and atlas number are
derived from a hash of:

- season,
- wind value,
- and every lantern's rounded position + color index.

So the same arrangement always renders the same atlas card. Move one
lantern or change the wind and a different atlas appears.

## Why it was built

It is one entry in a daily series of small, self-contained creative
artifacts. Today's goal was a calm, satisfying 2-3 minute toy with a
mintable keepsake, distinct in format from the past several days'
surprises (no bowls, no loom, no observatory).
