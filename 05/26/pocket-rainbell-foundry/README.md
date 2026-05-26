# Pocket Rainbell Foundry

A small mobile-first toy for May 26, 2026.

## What it is

Pocket Rainbell Foundry is a soundless rain-and-bowls instrument. A soft cloud drifts back and forth across a dawn sky; tap anywhere in the sky and a single warm bead falls from the cloud's spout into whichever of five bronze bowls sits beneath it. Each catch sends a quiet ring out from the bowl and tips its little pool a bit higher. Two dials shape the world: **Tempo** changes how quickly the cloud drifts, and **Glow** warms the bowl rims and the eventual palette. When at least three beads have pooled, **Cast bell** mints a deterministic little card — a named bell ("Slow Bronze at dawn", "Patient Toll over the orchard"), a five-bell rhythm glyph, a warm palette strip, a one-line description, and a tiny bell weight in grams.

The same bowl pattern, Tempo, and Glow always cast the same bell. Empty the bowls, nudge a dial, or tip another bead into a different bowl and the card quietly closes — casting again produces a new bell.

## Privacy-safe inspiration

Continues this run's theme of tiny hand-tuned morning rituals (weather chorus → tide cartographer → signal garden → dawn observatory → compass loom — today a rainbell foundry). Same warm dawn palette family, but the verbs shift: today is *tap*, *catch*, *cast*. Generic themes only: fresh start, morning curiosity, playful systems, calm exploration. No real names, addresses, quotes, or private context anywhere in the file.

## How to open

Open `index.html` in any modern browser. No server, no build step, no network calls, no dependencies — everything is inlined in a single self-contained file.

On a phone, add to home screen for a near-app feel.

## Controls

- **Tap the sky** — releases a single bead from the cloud's current position; it falls into whichever bronze bowl is beneath
- **Tempo dial** (0–10) — how quickly the cloud drifts left and right
- **Glow dial** (0–10) — warmth of the bowl rims and the cast bell's palette
- **Empty bowls** — clears all caught beads; the cloud keeps drifting
- **Cast bell** — enabled once at least three beads have been caught; mints a deterministic bell card with name, rhythm glyph, palette strip, description, and a tiny weight
- **Copy bell** — copies the card's text to the clipboard
- **Esc / tap backdrop / Close** — dismisses the card

## Why it was built

Part of an ongoing daily-surprise series — one tiny, complete, self-contained artifact per day. Today's goal: a vertical, gravity-shaped counterpart to yesterday's compass loom — fewer choices, a single calm verb (*tap*), and an output that names a bell rather than a route. Mobile-first, zero dependencies, 44px+ touch targets, friendly on a phone, respects reduced-motion preferences.
