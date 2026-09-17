# Edit X-Ray — See the Shape of a Revision

## What it is

Edit X-Ray is a local-first, tactile data visualization for comparing two short drafts. It turns a token-level diff into a document fingerprint: each bar is a word, bar height reflects word length, and color distinguishes words that were kept, added, removed, or replaced. A draggable inspection lens reveals the exact before/after pair at any position.

## Inspiration

Careful document work often depends on understanding the shape of a revision, not merely reading its final wording. Edit X-Ray explores a visual, privacy-safe way to see whether a rewrite was concentrated, scattered, additive, subtractive, or structural—without judging it.

## How to open

Open `index.html` in any modern browser. No server, account, package installation, or network connection is required.

## Controls

- Edit the **Before** and **After** passages.
- Tap **Scan revision** to rebuild the visualization.
- Drag the lens beneath the fingerprint to inspect each position.
- Tap any bar or annotated word to jump directly to it.
- Use **Load another example** to cycle through generic demos.

## Why it was built

Traditional redlines are precise but visually dense. This prototype adds a zoomed-out map plus a precise inspection layer, making it easier to understand the overall character of a rewrite while preserving the underlying words.

## Format choice

- **Lane:** `data_visualization`, expressed as a real-feeling local document tool.
- **Mechanic:** A token-level text diff becomes a compact word-height fingerprint with a draggable inspection lens and synchronized annotated tokens.

This lane and mechanic are structurally different from the recent pixel-memory game, tactile text-cutting tool, and evolving musical step sequencer.

## Explicit bans avoided

No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing; no choose-your-own, branching story, microquest, or multiple-ending mechanic; no signal routing, cartography, constellation, or connect-the-nodes metaphor; no launch/readiness/shipping simulator; no scorecard or rubric meter; no abstract AI-agent preflight/context debugger; no poetic generator; and no family, travel, baseball, home, Seattle, or local utility.

## Privacy

Everything runs locally in the browser. There are no external requests, analytics, storage, accounts, uploads, or telemetry. The included examples are generic and fictional.