# Pocket Dawn Observatory

A small mobile-first toy for May 24, 2026.

## What it is

Pocket Dawn Observatory is a tiny sky-cartography instrument. Drag the small glowing sun along an arc to set the horizon's mood, tap the sky to drop 3–7 quiet beacons, slide the **Phase** dial through pre-dawn → full-morning, then press **Observe** to mint a deterministic field note — a named observation ("Quiet Heron", "Folded Compass"), a single calm sentence, a five-swatch color band drawn from the current dawn, and the chord angle of your beacon arc.

The same beacons in the same positions with the same arc and phase always produce the same observation. Drag anything and the card quietly closes — re-observing produces a new card.

## Privacy-safe inspiration

Continues this run's theme of small, hand-tuned morning rituals: a weather chorus, a tide cartographer, a signal garden — today an observatory. Same warm palette family, different verbs (drag, tap, observe). Generic themes only: fresh start, morning curiosity, playful systems, calm exploration. No real names, addresses, quotes, or private context anywhere in the file.

## How to open

Open `index.html` in any modern browser. No server, no build step, no network calls, no dependencies — everything is inlined in a single self-contained file.

On a phone, add to home screen for a near-app feel.

## Controls

- **Drag the small sun** — sets the arc apex (the dawn horizon's tilt and height)
- **Tap the sky** — plant a beacon (up to 7; below the lower fade is ignored)
- **Phase** — slider, pre-dawn → first-light → horizon-warm → sun-up → full-morning; warms the gradient and color band
- **Surprise me** — shuffles beacons, sun position, and phase
- **Clear sky** — empties the field and resets defaults
- **Observe** — enabled once you have at least 3 beacons; mints a deterministic card with a named observation, one-line field note, color band, and arc angle
- **Copy observation** — copies the card text to the clipboard

## Why it was built

Part of an ongoing daily-surprise series — one tiny, complete, self-contained artifact per day. Today's goal: a slow, unhurried evening-of-the-morning toy where the verbs are *drag*, *tap*, *observe* rather than *play* or *win*. Mobile-first, zero dependencies, friendly on a phone, respects reduced-motion preferences.
