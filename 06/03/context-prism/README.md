# Context Prism — Tiny Brief-to-Artifact Lens

A pocket instrument for translating messy project context into a buildable
artifact brief. Pick a source, tune four focus dials, lock the constraints
that matter, and read the one-page brief you could hand to yourself, a
coworker, or an agent.

## What it is

A single HTML page with three inputs and one output:

1. **Source** — what kind of fuzz you started with (Docs import, Support
   critique, Agent task, Experiment idea).
2. **Focus dials** — Clarity, Proof, Risk appetite, Delight, each 0–10.
3. **Constraints & signals** — chips like *mobile-first*, *no new infra*,
   *async-friendly*, *privacy-safe* that pin the artifact in place.

Tap **Pass through the prism** and you get a deterministic brief: an
**Intent** sentence, **Non-negotiables**, **Acceptance signals**, **Risks
to watch**, and a **First build slice** sized small / sketch / medium /
wide based on your dial budget. A *lens clarity* score (0–100) and a
shape badge (crisp / usable / wide aperture / unfocused / soft focus /
rough cut) summarize whether the inputs cohere.

Copy the brief as plain text or markdown. Reset wipes everything.

## Privacy-safe inspiration

The week kept circling on the same shape of problem: lots of scattered
source material — notes, tickets, agent transcripts, hunches — and the
need to compress them into something concrete enough to actually build.
The dial set (clarity / proof / risk / delight) is a generic stand-in
for the trade-offs that always come up in that compression step. No
private chats, ticket text, or identifying details are referenced or
encoded anywhere in the artifact.

## How to open

Open `index.html` in any modern browser. No build, no install, no
network calls. Works the same online or offline, on a phone or laptop.

## Controls

- **Source cards.** One-of-four. Each picks a different intent template
  and source-specific proof / risk / first-slice library.
- **Focus dials.** Four 0–10 sliders. The sum is shown as a *focus
  budget* with a shape (sketch-mode / lean / balanced / rich /
  overpacked). The dominant dial steers the brief title; clarity caps
  how many non-negotiables appear; proof caps acceptance signals;
  (10 − risk) caps risks; delight unlocks the third slice step.
- **Constraint chips.** Twelve toggles. Each chip contributes one
  non-negotiable, one acceptance signal, and one risk to its category.
  Lens clarity rewards 3–6 chips and punishes zero or too many.
- **Quick presets.** Quick sketch, Proof-heavy, Delight-forward,
  Surprise me. Surprise me cycles a deterministic seed so successive
  taps give different shapes.
- **Pass through the prism / Reset / Copy brief / Copy as markdown.**

## Why it was built

Scoob's daily surprise. The lane: a small, useful, slightly playful
product tool — not a poetic generator. The aim is something that feels
like an actual instrument on your home screen rather than a piece of
art: tap a few controls, get a brief you can paste straight into a
notes app, an issue tracker, or an agent prompt.

## Format choice

Single self-contained `index.html`. Vanilla JS, no frameworks, no
external assets, no fonts, no network. Mobile-first layout capped at
540px wide with 44px touch targets and tested mentally at 360px. Dark
theme tuned to match the rest of Electric Sheep, with a six-color prism
strip as the only ornament. Score and outputs are fully deterministic
from the inputs, so the same configuration always yields the same brief.

## Privacy check

- No real names, emails, phone numbers, addresses, or financial data.
- No paraphrases of private conversations, tickets, or documents.
- No tokens, credentials, or operational secrets.
- All copy is generic about *kinds* of project work, never specific
  projects.
- No network requests, telemetry, analytics, or external resource loads.
- LocalStorage and cookies are not touched.

Pass.
