# Signal Garden — Agent Memory Debugger

**Date:** 2026-05-30

## What it is

A self-contained, mobile-first browser prototype for debugging an imaginary
agent's context pipeline. You tune six abstract signals — Freshness, Trust,
Specificity, Recency, Actionability, and Noise — then tap **Compile context**
to watch which signals "take root" inside an eight-slot memory buffer. Some
bloom into the stack, some get crowded out, and noise wilts the good seeds
if you let it run too high.

The output is deterministic: the same dial settings always produce the same
stack, the same conflicts, and the same suggested next move. It's a tiny
inspectable model of an idea you can't otherwise see — *what an agent
actually keeps in its head.*

## Format choice

**AI / agent / memory prototype + tiny puzzle-explainer.** Differs from the
last three days deliberately:

- Not a launch-readiness allocation simulator (2026-05-29).
- Not a triage / rubric card board (2026-05-28).
- Not a poetic atlas / cartography toy (2026-05-27).

The closest neighbor is the readiness simulator, but Signal Garden is a
*debugger* with a buffer-visualization metaphor, not an allocation/score game.

## Privacy-safe inspiration

Thematic only. The day's recent-context pass surfaced generic themes around
reliable automation, lightweight triage, recovery paths, publishing
confidence, and turning messy context into small inspectable tools — so this
build turns "messy context into a small inspectable tool" *literally*. No
private session specifics, quotes, names, or operational details are
referenced anywhere in the artifact.

## How to open

Open `index.html` in any modern browser (Safari, Chrome, Firefox). No
network, no install, no server. Looks best on a phone in portrait, but
adapts to tablet and desktop.

## Controls

- **− / +** buttons on each of six signal cards (0–10).
  - **Freshness** — newness of input.
  - **Trust** — how much you stake on each source.
  - **Specificity** — precise artifacts vs. vague pointers.
  - **Recency** — how lately the context was touched.
  - **Actionability** — verbs you can act on this turn.
  - **Noise** — filler that crowds the good seeds.
- **Compile context →** runs the deterministic algorithm and re-renders the
  8-slot memory stack, diagnostics, and a one-line next move.
- **Shuffle** (diagonal arrows icon) — randomizes signals for quick
  what-if exploration. Biases noise toward the lower half so the result
  stays playable.
- **Reset** (circular arrow icon) — restores defaults and clears results.

## Why it was built

To make agent-context tuning feel small and tactile — six dials, one button,
one inspectable output. It's the kind of toy you'd reach for on a slow
morning to refresh the intuition: *what dies first when noise creeps up?
where does a stale-but-trusted source quietly damage a run?*

It's also a small love letter to debuggers as a genre. The visual register
(phosphor green on midnight teal, serif italics for verdicts, monospace for
readouts) borrows from instrument panels and CRT consoles without being a
nostalgic skin.

## Privacy check

- No real names referenced (the masthead reads only "Scoob field tool" as
  generic thematic framing).
- No emails, phone numbers, addresses, dollar amounts, or credentials.
- No quotes from real conversations or operational specifics.
- Token vocabulary in the memory stack is fully invented (e.g.
  `user-prompt`, `this-turn`, `flag:value`, `gold-doc`).
- No network requests at runtime; no external resources loaded.
- No analytics, no fingerprinting, no storage.

Passed.
