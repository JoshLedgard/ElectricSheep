# Tiny Decision Zine

## Title
Tiny Decision Zine — a pocket "choose-your-line" micro-zine for turning one ambiguous tangle into a clear next move.

## What it is
A mobile-first, tap-through zine/editor. You flip through six illustrated panels, write a single sentence on each page, and tap a few branching "choice chips" that flavor the story. At the end it folds everything into one printable/shareable **Decision Note** — six crisp lines: the decision, why now, the leaning, the smallest test, the handoff, and one thing to watch.

It is a tiny editor wrapped in a comic/zine, not a simulator, checklist, scorecard, or dashboard. There are no meters, scores, or pass/fail readouts — just panels, sentences, and a folded note at the end.

## Privacy-safe inspiration
Built from generic, non-identifying themes: recurring automations that quietly come back, crisp handoffs so anyone can pick work up next, and turning fuzzy/ambiguous work into a small, clear next action. No names, clients, conversations, or private details are referenced or required.

## How to open
Open `index.html` in any modern browser (desktop or phone). No server, install, build step, or network connection is needed — everything (illustrations, fonts, logic) is self-contained in the single file. Best viewed on a phone; works fine on desktop too.

## Controls
- **Choice chips** (44px+) — tap to pick a branch on the "why now", "two doors", and "handoff" pages; the choice flavors the final note.
- **One-line text field** — type one sentence per page (capped at 140 chars with a live counter).
- **Next page → / ← Back** — move through the zine; Next stays disabled until the page has a sentence (and a chip where required).
- **Fold the zine →** — composes the final Decision Note.
- **Copy note** / **⧉ Copy** — copy the plain-text note to the clipboard.
- **⬇ Download** — save the note as `decision-note.txt`.
- **🖨 Print** — open the browser print dialog (note is print-styled).
- **↺ New zine / Start over** — clear everything and begin fresh.
- Progress is saved on-device (localStorage), so a reload resumes where you left off.

## Why it was built
A daily surprise for Josh: a calm, tactile 2–3 minute ritual for the everyday move of taking something vague that keeps circling and folding it into one honest, sharable next step — in the shape of a little hand-made zine rather than yet another tool with meters.

## Format choice
- **Lane:** writing_or_decision_aid
- **Mechanic:** mobile-first choose-your-own micro-zine / tiny editor — tap through illustrated panels, capture one sentence per page, with branching choice chips, ending in a printable/shareable decision note (copy / download / print / reset, local-state persisted).

## Avoided recent patterns
Deliberately steers clear of: launch/readiness/shipping simulators, generic scorecard/rubric meters, abstract AI-agent preflight/context tools, card-sort/board layouts, route/packet puzzles, and spatial drag-to-map dashboards. Structurally this is a zine/editor with prose output, not a game, puzzle, data-viz, or dashboard.

## Privacy check
Reviewed and clear: no real names, emails, phone numbers, addresses, dollar amounts, exact/private quotes, client details, secrets, or sensitive conversation specifics. All sample placeholder text is generic and invented. No network calls, no external assets, no analytics — fully offline and self-contained.
