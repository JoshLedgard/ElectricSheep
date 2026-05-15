# Dewdrop Switchboard

A tiny morning toy where you route light through a dew garden. Tap prisms to turn them. Tap droplets to change their color. The little suns on the edges send beams across the grid, and a droplet "lights up" when the beam reaching it matches its tint.

## What it is

A self-contained, mobile-first browser toy. A 5×5 garden grid hosts:

- **Suns** at the edges — fixed-tint emitters that shoot a colored beam inward.
- **Prisms** in the interior — hexagonal pieces that either turn or split the beam, rotatable in 90° steps.
- **Droplets** — small dew sinks that light up only when the beam touching them matches their chosen tint.

You play 2–3 minutes: rotate prisms, retint droplets, and try to light the whole garden. When you're done, tap **Compose card** and the toy mints a tiny named circuit card (e.g. *Quiet Telegram*, *Glassy Footbridge*) summarizing what you built.

## Privacy-safe inspiration

The vibe: morning light catching dew on a window, the small satisfying feeling of a circuit clicking together, and the way ordinary objects (drops of water, glass) sometimes carry a beam further than you'd expect. No personal information, conversations, or private context informed the build — just a generic fresh-start, morning-curiosity theme.

## How to open

Double-tap `index.html` in this folder. It runs in any modern browser — Safari, Chrome, Firefox — on phone or desktop. No installation, no server, no network calls, no external assets.

## Controls

- **Tap a prism** — rotates it 90° clockwise. Beams that hit it will turn (or split, for T-shaped prisms).
- **Tap a droplet** — cycles its tint through amber → glacier → fern → blush.
- **Tap a sun** — rotates its emission direction (advanced; usually you won't need to).
- **Reset** — generates a new random board.
- **Compose card** — mints a small named circuit card based on how lit the garden is.

The meter below the board shows how many droplets are currently lit out of the total.

## Why it was built

Today's Daily Surprise. The brief was a tactile, audio-free, mobile-first pattern toy distinct from recent kite/map/weather entries — something gentle, with light feedback, that resolves in a couple of minutes. A small switchboard of dew felt right for a Friday morning: enough logic to keep your fingers thinking, but quiet enough not to demand the rest of your attention.
