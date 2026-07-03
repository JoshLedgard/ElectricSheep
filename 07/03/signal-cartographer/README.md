# Signal Cartographer

A tiny spatial puzzle for the phone. You're mapping signal routes across a night sky:
tap two nodes to lay a **bridge** between them and light the network outward from the
source. The catch — **bridges may never cross**, and you get exactly one bridge fewer
than there are nodes. Chart a clean route that lights every node and the constellation
comes alive.

## What it is

- A path-drawing puzzle on a small constellation map (SVG).
- Signal starts at the ringed node (◎) and lights outward along the bridges you build.
- **Goal:** connect every node into one network so they all light up.
- **Rule:** no two bridges may cross ("signals would interfere").
- **Budget:** exactly (nodes − 1) bridges — enough for a clean tree, nothing to waste.
- 6 handmade maps of growing size (4 → 9 nodes) plus a date-seeded **Today's
  Constellation** that reshuffles for replay.
- Win feedback, hint, reset, and level navigation. Every map is guaranteed solvable.

## Privacy-safe inspiration

A generic morning curiosity about making complex paths legible — turning the discipline
of "verify before you connect" into a small, playful map puzzle. No names, projects, or
private details are referenced.

## How to open

Open `index.html` in any modern mobile or desktop browser. It is a single
self-contained file — no server, no install, no network, no external fonts or scripts.

## Controls

- **Tap a node**, then tap a second node → lays a bridge between them.
- **Tap the same two nodes again** → removes that bridge.
- **✦ Hint** — briefly ghosts one clean, non-crossing route (yours can differ).
- **↺ Reset** — clears the current map.
- **◀ Prev / Next ▶** — move between the handmade maps.
- **✷ Today's Constellation** — generate/reshuffle a fresh date-seeded map.
- All controls are 44px+, touch-friendly, and work without hover. The map is a
  responsive square SVG that fits small screens with no horizontal overflow.

## Why it was built

Made as Josh's Daily Surprise for 2026-07-03 — a two-to-three-minute puzzle that takes
the idea of "make a tangled route legible, and don't connect things that would
interfere" and renders it as a satisfying spatial game instead of a dashboard.

## Format choice

- **Lane:** game_or_puzzle
- **Mechanic:** spatial path-drawing puzzle on a tiny constellation map — connect signal
  nodes with a limited budget of non-crossing bridges to light a route, with an optional
  daily-seed constellation for replay.

## Avoided recent patterns

Deliberately **not** any of: launch/readiness/shipping simulators; generic
scorecard/rubric/meter tools; abstract AI-agent context, preflight, or context-debugger
tools. This is structurally a hand-built path puzzle — spatial input, a win state, and
handmade levels — not a meter, checklist, generator, or simulator.
