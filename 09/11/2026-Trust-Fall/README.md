# TRUST FALL — The AI Interface Inspection Game

## What it is

A compact, four-case inspection game set inside a retro-future product quality lab. Each case presents a realistic fictional AI interface. Tap the visible parts where trust breaks: unsupported certainty, hidden consent, excessive permissions, unreproducible evidence, or an action whose blast radius is disguised.

There are twelve failures to find, immediate explanations, optional clues, keyboard-accessible targets, a tiny Web Audio sound layer, and a final pocket checklist. Everything runs locally in one HTML file.

## Privacy-safe inspiration

Recent work suggested a broad, non-personal theme: dense product and operational details become useful when people can inspect the decision hidden inside them. The game uses only fictional products and synthetic examples; it contains no personal context or external data.

## How to open

Open `index.html` in any modern browser. No server, account, network request, package install, or build step is required.

## Controls

- Tap or click suspicious visible interface elements.
- Keyboard: use **Tab** to move between inspectable elements and **Enter/Space** to inspect.
- **Reveal a clue** focuses the next unresolved area.
- **Next case** unlocks after all three failures in a case are found.
- The **♪** button toggles locally generated sounds.
- **Inspect again** resets all four cases.

## Why it was built

AI trust is often treated as policy text or a checklist. TRUST FALL makes it physical: you inspect the actual button, label, claim, permission, or footnote where a product asks for more trust than it has earned. It is a tiny playable prototype for making responsible product judgment concrete.

## Format choice

- **Lane:** `game_or_puzzle`
- **Mechanic:** Timed spot-the-problem inspection across four linear, realistic fake AI interfaces; tap visible UI trust failures to expose concise product critiques. It is not a branching story.

## Explicit bans avoided

- No field guide, zine, atlas, almanac, codex, bestiary, or pocket-guide framing.
- No choose-your-own, branching adventure, microquest, or multiple-ending mechanic.
- No signal, cartography, constellation, routing, path, or connect-the-nodes metaphor.
- No launch, readiness, shipping, or preflight simulator.
- No generic scorecard or rubric meter.
- No abstract AI-agent context debugger.
- No family, travel, baseball, home, Seattle, or local utility.

## Implementation and accessibility

Self-contained HTML/CSS/JavaScript; no external assets or analytics. The layout is designed for a 390px viewport without horizontal overflow, with 44px-or-larger primary controls, visible keyboard focus, live-region feedback, no hover-only requirements, and reduced-motion support. Audio begins only after interaction and can be disabled.
