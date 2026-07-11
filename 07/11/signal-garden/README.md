# Signal Garden

## What it is
A calm, mobile-first spatial-logic puzzle. Each tiny night-garden grid holds a firefly (a colored signal source) and one or more matching blooms. Vine tiles between them carry the glow, but they start twisted the wrong way. Tap a vine to rotate it 90°; when a firefly's glow reaches every bloom of its color, that garden lights up. Six handcrafted levels build from a single straight vine to two-color weaves and a branching fork that feeds two blooms at once.

- Understandable in under 20 seconds: tap tiles to turn them, connect glow to bloom.
- Satisfying for a few minutes: 6 levels of gently increasing tangle.
- Every level is verified solvable, and none start already solved.

## Privacy-safe inspiration
A fresh-start, morning-curiosity mood — plus the idea of calm troubleshooting and quiet verification reimagined as a playful path-routing puzzle. Nothing personal or specific; just the feeling of patiently untangling a route until everything connects and glows.

## How to open
Open `index.html` in any modern mobile or desktop browser. It is a single self-contained file — no install, no server, no network, no external assets. Works great added to a phone home screen.

## Controls
- **Tap a vine tile** — rotate it 90° clockwise to re-route the glow.
- **↺ Reset** — untangle the current garden back to its starting scramble.
- **Next → / Finish ✦** — lights up once the garden is fully solved; advances to the next level.
- **Wander again** — after the final garden, restart from the beginning.
- Sources (fireflies) and blooms are fixed; only the vine tiles rotate.

## Why it was built
It's today's Daily Surprise — a small, self-contained, genuinely playable thing meant to be understood in seconds and enjoyed for a couple of minutes, with visual polish (glowing signal flow, blooming completion, spark celebration) and touch-friendly 44px+ targets.

## Format choice
- **Lane:** game_or_puzzle
- **Mechanic:** a spatial logic puzzle with tappable tiles that route colored firefly signals through a tiny garden grid to matching blooms. Flow spreads only through same-color, mutually-connected connectors, so the challenge is orienting each vine so every glow finds its way home.

## Avoided recent patterns
Deliberately steered clear of: launch/readiness/shipping simulators; generic scorecard or rubric meters; and abstract AI-agent context/preflight tools. This is not a generator, readiness checker, scorecard, rubric, or launch simulator — just a handcrafted routing puzzle. It also differs mechanically from the recent path-tracing garden maze: here the grid is fixed and you rotate tiles to build the connection, rather than tracing one continuous walking route.
