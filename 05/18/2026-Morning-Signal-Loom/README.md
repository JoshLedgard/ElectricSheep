# Morning Signal Loom

A mobile-first interactive weaving toy. Tap colored thread spools to weave a small signal ribbon one row at a time; press **Compose Signal** to mint a tiny morning dispatch with a generated name and short message.

## What it is

A self-contained browser artifact (`index.html`, no server, no packages, no network calls). The loom holds up to 8 woven rows. Each spool — Dawn, Mist, Lichen, Slate, Ember, Plum — has its own color, glyph mark, and tonal flavor. The dispatch text is composed deterministically from the sequence of spools you wove, so the same loom always mints the same dispatch.

## Privacy-safe inspiration

Generic themes only: **fresh start**, **morning curiosity**, **playful systems**. The page contains no private context, no real names, no addresses, no quoted conversations, no secrets. Every signal you mint stays on your device — nothing is transmitted or stored elsewhere.

## How to open

Double-click `index.html` (or open it in any browser). It works offline and is designed to fit a phone screen (≥390px) without horizontal scroll. Best on mobile, fine on desktop.

## Controls

- **Spool buttons** — tap to weave a new row of that color (44px+ touch targets).
- **Shuffle** — replace the loom with a randomized 4–6 row weave.
- **Reset** — clear the loom and start fresh.
- **Compose Signal** — generate a small "Morning Dispatch" card from the current weave: a stamped serial number, a poetic title, a 3-line body, and a glyph "tone string" of the row marks. Compose again after weaving more rows to mint a new dispatch.

## Accessibility

- `prefers-reduced-motion` is honored (no weave-in or reset animations).
- Buttons have visible focus rings and ARIA labels.
- Color choices are warm-paper / dark with sufficient contrast for body copy.

## Why it was built

Today's Daily Surprise. The previous toys have leaned on sky stamps, tide pools, and light circuits — this one shifts to a fabric/loom metaphor so the format feels new while staying in the same family of small, satisfying, name-something-tiny experiences.
