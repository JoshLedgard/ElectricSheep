# Undo Ledger

## What it is

Undo Ledger is a self-contained prototype of a near-future accountability interface for autonomous software. It presents six fixed, fictional actions as an inspectable transaction history. Scrub the timeline, open before/after receipts, and safely rewind one shared draft; the interface then reconciles its dependent reminder and appends a new audit receipt.

## Privacy-safe inspiration

Inspired generically by agent reliability, clear handoffs, and the idea that consequential software actions should be inspectable and reversible. It contains no details or quotations from private conversations.

## How to open

Open `index.html` in any modern browser. It requires no server, package installation, account, network connection, or external asset.

## Controls

- Drag the timeline scrubber, tap a node, or tap an action row to inspect a transaction.
- Use Left/Right arrow keys to move through the ledger.
- Select transaction **05 · Shared draft with reviewers**.
- Press and hold **Hold to rewind** for 1.5 seconds. Space or Enter also works from the focused button.
- Watch the dependent reminder reconcile and the append-only receipt appear.
- Use **Reset** to replay the interaction; Escape also resets after a rewind.

## Why it was built

Most autonomous interfaces emphasize what an agent can do. Undo Ledger explores a different product primitive: a legible, dependency-aware receipt for what it already did, with one deliberately tactile path back. It is meant to feel like a convincing artifact from a future operating system rather than a themed webpage.

## Format choice

- **Lane:** `future_artifact_fake_app` — a real-feeling product prototype for autonomous-software accountability.
- **Mechanic:** scrub a visual transaction timeline, inspect fixed before/after diffs, then press-and-hold to rewind one action while the interface updates dependencies, statuses, and its audit trail.

## Explicit bans avoided

No field guide, zine, atlas, almanac, codex, bestiary, or pocket-guide framing; no choose-your-own, branching story, microquest, or multiple endings; no signal, cartographer, routing, constellation, connect-the-nodes, or path metaphor; no launch, readiness, or shipping simulator; no generic scorecard or rubric meter; no agent preflight, context prism, or generic debugger; no poetic or random generator; and no family, travel, baseball, home, or local content.

## Privacy check

The artifact uses only generic fictional labels and values. It contains no real names, organizations, email addresses, phone numbers, street addresses, financial data, private quotes, credentials, analytics, trackers, storage, external assets, or network requests.

## Verification

- Complete single-file HTML/CSS/JavaScript artifact with no dependencies.
- Six fixed action records, one reversible action, dependency reconciliation, replay, and an append-only audit receipt.
- Responsive grid and wrapping content designed to avoid horizontal overflow at 390px.
- Touch controls meet a 44px minimum; timeline rows, range input, pointer hold, and keyboard controls are supported.
- Reduced-motion preference is respected.
- A deterministic in-page test validates core scenario invariants and sets `data-self-test="pass"` on the document root.

## Creative brief

- **Title candidate:** Undo Ledger
- **Recent-context theme:** generic interest in reliable agents, inspectable work, and clear handoffs.
- **Quality requirements:** immediately understandable; convincing future interface; rich fixed transaction scenario; satisfying reversible interaction; polished mobile and keyboard support; entirely self-contained.
