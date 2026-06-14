# Signal Garden

A tap-to-rotate light-routing puzzle. Each tile holds a tangle of connectors; turn
them 90° at a time until a single clean signal flows from the source into the bloom.
Three small gardens (3×3, 4×4, 5×5) that get a little wider each time.

## What it is

A self-contained mobile-first browser puzzle. Every level generates a fresh layout
from a random spanning tree, then scrambles the connector orientations, so the path
is always solvable but never the same twice. Lit pipes glow and pulse with flowing
signal; the bloom blossoms gold the moment the source reaches it.

## Privacy-safe inspiration

The recent build energy was about visual polish, UI iteration, and turning tangled
feedback into a clear path. Signal Garden makes that literal: a scattered, twisted
mess of connectors that you patiently rotate into one legible route. No real data,
names, or specifics — just the feeling of untangling something until it flows.

## How to open

Double-click `index.html`, or drag it into any modern browser. No install, no server,
no network, no packages. Works offline on phone or desktop.

## Controls

- **Tap a connector** — rotates it 90° clockwise (with a haptic tick on supported phones).
- **↺ Reset** — returns the current garden to its scrambled starting state.
- **Next level →** — appears once the bloom is lit; advances to the bigger garden.
- The source (top-left) and the bloom (bottom-right) are fixed — only the connectors turn.
- Every tile is a labeled button with its connections and lit state announced for screen readers.

Win condition: light the bloom. You only need to feed it — dead-end branches are fine.

## Why it was built

A Daily Surprise for Josh — a small, genuinely playable artifact that's understood in
under 20 seconds and rewarding for a couple of minutes. It leans into the satisfying
click of order emerging from a tangle, with tactile feedback, a clear win-and-bloom
moment, and a tiny three-level arc instead of an endless grind.

## Format choice

- **Lane:** game_or_puzzle
- **Mechanic:** spatial light-routing tile puzzle with tap-to-rotate connectors and a
  small three-level progression (3×3 → 4×4 → 5×5), with a flood-fill signal that lights
  every connected pipe and blooms the target when reached.

## Avoided recent patterns

Deliberately steered clear of the recent run of: launch/readiness/shipping simulators,
generic scorecard/rubric/meter tools, abstract AI-agent context or preflight utilities,
and poetic/field-note generators. This is a hands-on spatial puzzle with a concrete win
state — no scores to tune, no copyable report, no dials.
