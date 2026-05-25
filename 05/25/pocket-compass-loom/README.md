# Pocket Compass Loom

A small mobile-first toy for May 25, 2026.

## What it is

Pocket Compass Loom is a tactile little weaving instrument shaped like a compass. Drag three glowing knots around a ringed dawn loom, pick one of four warm threads (ember, ochre, rose, dust), and tap pairs of knots to weave threads between them. When you press **Chart route**, the loom mints a deterministic itinerary card: a named route ("Patient Bend", "Quiet Triad", "Folded Compass"), a single calm sentence, a miniature glyph that replays your weave, and a compass bearing derived from the centroid and longest thread of the figure you made.

The same knot positions and threads always produce the same chart. Drag a knot, swap a thread color, or unweave a strand and the card quietly closes — re-charting produces a new route.

## Privacy-safe inspiration

Continues this run's theme of small, hand-tuned morning rituals (weather chorus, tide cartographer, signal garden, dawn observatory — today a compass loom). Same warm dawn palette family, but different verbs: today is *drag*, *weave*, *chart*. Generic themes only: fresh start, morning curiosity, playful systems, calm exploration. No real names, addresses, quotes, or private context anywhere in the file.

## How to open

Open `index.html` in any modern browser. No server, no build step, no network calls, no dependencies — everything is inlined in a single self-contained file.

On a phone, add to home screen for a near-app feel.

## Controls

- **Drag a knot** — slide it anywhere within the loom's ring band
- **Tap a knot, then tap another** — weaves a thread of the active color between them; tapping the same pair again with the same color unweaves it, with a different color recolors it
- **Thread palette** (ember / ochre / rose / dust) — choose the strand color for the next weave
- **Reshuffle** — drops three fresh knots and clears all threads
- **Unweave** — clears all threads but leaves the knots in place
- **Chart route** — enabled once at least one thread exists; mints a deterministic itinerary card with name, one-line route, mini glyph, and compass bearing
- **Copy itinerary** — copies the card's text to the clipboard
- **Esc / tap backdrop / Close** — dismisses the card

## Why it was built

Part of an ongoing daily-surprise series — one tiny, complete, self-contained artifact per day. Today's goal: a slow, deliberate weaving toy whose verbs are *drag*, *weave*, *chart* — a quiet counterpart to yesterday's observatory. Mobile-first, zero dependencies, 44px touch targets, friendly on a phone, respects reduced-motion preferences.
