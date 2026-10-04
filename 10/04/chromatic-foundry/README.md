# Chromatic Foundry

## What it is

A tactile, two-minute pattern-matching game. Colored parts arrive on a foundry belt; position and rotate each piece to reproduce three sample plates before the whistle blows. Exact fits build a combo, while a bad stamp costs time.

## Privacy-safe inspiration

Inspired by the general satisfaction of turning a busy stream of small pieces into one finished system. It contains no personal data, private conversation content, tracking, analytics, or network requests.

## How to open

Open `index.html` in any modern browser. It is a self-contained file and needs no server, package installation, account, or internet connection.

## Controls

- **Touch / mouse:** Tap a square on **Your Plate** to position the glowing part, use **Rotate**, then press **Stamp Part**.
- **Keyboard:** Arrow keys move the part, **R** rotates, and **Space** stamps.
- Use the **?** button to pause and reopen the instructions.
- **Goal:** Match all three sample patterns in two minutes. Clean consecutive fits increase the combo; a bad stamp removes three seconds.

## Why it was built

To make a Daily Surprise feel like an unexpected pocket game rather than another themed page: finite, tactile, immediately understandable, replayable, and polished enough to invite a second run.

## Format choice

- **Lane:** `game_or_puzzle`
- **Mechanic:** `tactile arcade pattern-matching` — place, rotate, and stamp geometric parts against a visual sample under a short timer.

## Explicit bans avoided

- No field guide, atlas, almanac, codex, zine, bestiary, or pocket-guide framing.
- No choose-your-own, branching adventure, microquest, or multiple-ending story mechanic.
- No signal, cartographer, constellation, routing, or path-connection metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard or rubric meter.
- No abstract AI-agent context, preflight, prism, or debugger tool.
- No poetic generator.
- No family, travel, baseball, home, Seattle, or local utility.

## Technical notes

Everything is inline in `index.html`: HTML, CSS, JavaScript, levels, and artwork. The interface is mobile-first, uses 44px-or-larger primary controls, supports keyboard play, honors reduced-motion preferences, and makes no external requests.
