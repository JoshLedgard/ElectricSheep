# Metric Arcade: Invisible Hand

## What it is

A polished, self-contained causal-inference game disguised as a future product analytics console. Across three short fictional cases, you manipulate product levers, watch three synthetic metrics respond over 30 simulated days, and identify the hidden rule that best explains the evidence.

This is not a themed quiz: the dashboard recomputes a deterministic model whenever a lever moves, so controlled experiments reveal nonlinear effects, delayed effects, and marketplace balance.

## Privacy-safe inspiration

The inspiration was a broad, non-personal theme from recent activity: product operations, systems thinking, and turning ambiguous evidence into a useful decision. Every label and number in the experience is fictional and synthetic. No private conversations, projects, identities, or real-world business data are included.

## How to open

Open `index.html` in any modern browser. It needs no server, install, login, external asset, or network connection.

## Controls

1. Press **Enter the lab**.
2. Move each intervention slider and watch the three lines and current values respond.
3. Try changing one lever at a time to isolate its effect.
4. Select one of the three causal models and press **Lock hypothesis**.
5. Read the explanation, continue through all three cases, then optionally restart.

Touch, mouse, and keyboard controls are supported. The interface is mobile-first, including large touch targets and a single-column layout on narrow screens. Reduced-motion preferences are respected.

## Why it was built

Dashboards usually encourage passive reading. This small game reverses that relationship: the player must intervene, observe, and explain. It is a playful prototype for teaching causal reasoning without a lecture—and a glimpse of how a serious-looking product surface can secretly be a compact learning toy.

## Format choice

- **Lane:** `game_or_puzzle`
- **Mechanic:** Three-round causal-discovery puzzle using tactile sliders, deterministic simulated time-series charts, controlled experimentation, and hypothesis locking inside a future-artifact/fake analytics app.

## Explicit bans avoided

- No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing.
- No choose-your-own, branching story, microquest, multiple endings, or branching adventure.
- No signal routing, cartographer, constellation, or path-connection metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard or rubric meter.
- No abstract AI-agent preflight, context tool, prism, or debugger.
- No generic generator.
- No family, travel, baseball, home, Seattle, or local-utility subject matter.

## Privacy and implementation

The experience makes no network requests, stores no analytics, requires no local storage, and contains no credentials or personal identifiers. All simulation values are produced locally in the browser from fixed formulas.
