# Reply Forge — Tiny Tone Calibration Studio

**Daily Surprise · 2026-05-31**

## What it is
A small, single-file writing aid for replies you keep redrafting. You pick a
scenario (acknowledge, decide, decline, ask, deliver, hold a line), nudge five
tone dials (warmth, directness, formality, urgency, brevity), and tap which
moves the reply must make (open, mirror, decision, reason, ask, next step,
timeframe, thanks). Tap **Forge reply** and you get:

- a **structure recipe** for the reply,
- a **skeleton** with `[slots]` you can fill in,
- a **tone read** with diagnostic badges (e.g. *cushion-heavy*, *edge-risk*,
  *urgent w/o deadline*, *decline w/o the no*),
- a **before-you-hit-send checklist** that reacts to your dial settings,
- and two copy buttons — skeleton only, or the full brief as plain text.

Six **reusable presets** are included: *Warm Acknowledge*, *Crisp Decline*,
*Curious Probe*, *Brief Confirm*, *Empathetic Delay*, *Firm Line*. When your
manual settings match a preset exactly, that preset card lights up — a small
feedback loop for learning your own calibrations.

## Privacy-safe inspiration
The general feeling of: that pause before sending a careful reply, when you're
trying to find the dial position between *too warm and apologetic* and *too
clipped and cold*. No real correspondence, names, or content were used; the
sample text in the skeleton is generic ("Thanks for the note", `[one honest
reason]`, etc.).

## How to open
Double-click `index.html`, or drag it into any modern browser. Everything runs
locally — no network calls, no installs, no server. Works equally well on a
phone (mobile-first layout, 44px touch targets) or a desktop browser.

## Controls
1. **Pick a scenario** — six common reply situations.
2. **Start from a preset** *(optional)* — six calibrated starting points.
3. **Calibrate the dials** — Warmth, Directness, Formality, Urgency, Brevity.
   Each is a 0–100 slider with named ends (e.g. *cool ↔ warm*).
4. **Required moves** — toggle chips for the structural beats the reply must
   include.
5. **Forge reply** — generates structure + skeleton + tone read + checklist.
   **Reset** restores the default state.
6. **Copy skeleton** or **Copy full brief** to paste into your draft.

The skeleton output adapts to your settings — for example, high *Directness*
swaps "If it works, I'd suggest…" for "Next step:", and high *Brevity* runs
sentences inline instead of separating them with blank lines.

## Why it was built
Most "tone help" tools rewrite *for* you. Reply Forge does the opposite — it
makes the calibration explicit so you can do the rewrite yourself, faster and
with fewer second-guesses. It's meant for the two-minute moment between
reading a message and starting your reply: pick a scenario, nudge the dials,
get a recipe and a couple of honest warnings, then write the actual reply in
your own voice.

## Format choice & how it differs from recent surprises
- **Format:** writing / decision-aid micro-tool with a playful calibration
  loop (dials + presets + skeleton output + diagnostic badges).
- **vs. 2026-05-30 (AI/agent memory debugger):** that one was an
  inspect-and-diagnose tool for invisible system state; this one is a
  generate-and-calibrate tool for a human writing act.
- **vs. 2026-05-29 (launch readiness allocation simulator):** that one was a
  numeric-allocation simulator with resource trade-offs; this one is a
  qualitative tonal tool with no scoring of a "right" answer.
- **vs. 2026-05-28 (Mission Control Triage Cards):** that one was a
  multi-card triage/rubric board for ranking incoming items; this one focuses
  on the moment *after* an item has been triaged — composing the reply.

No third-party libraries, no fonts loaded from the network, no analytics,
no storage — one HTML file, ~22KB.
