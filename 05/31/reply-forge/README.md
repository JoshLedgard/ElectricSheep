# Reply Forge — AI Reply Prompt Studio

**Daily Surprise · 2026-05-31**

## What it is
A small, single-file prompt builder for replies you keep redrafting. You paste the
source context, pick a scenario (acknowledge, decide, decline, ask, deliver, hold
a line), nudge five tone dials (warmth, directness, formality, urgency, brevity),
and tap which moves the reply must make (open, mirror, decision, reason, ask,
next step, timeframe, thanks). Tap **Forge prompt** and you get:

- a **prompt strategy** for the target reply,
- a complete **AI prompt** you can paste into Claude, ChatGPT, or another AI tool,
- a **tone read** with diagnostic badges (e.g. *cushion-heavy*, *edge-risk*,
  *urgent w/o deadline*, *decline w/o the no*),
- a **before-you-hit-send checklist** that reacts to your dial settings,
- and two copy buttons — generated prompt only, or the full calibration brief.

Six **reusable presets** are included: *Warm Acknowledge*, *Crisp Decline*,
*Curious Probe*, *Brief Confirm*, *Empathetic Delay*, *Firm Line*. When your
manual settings match a preset exactly, that preset card lights up — a small
feedback loop for learning your own calibrations.

## Privacy-safe inspiration
The general feeling of: that pause before sending a careful reply, when you're
trying to find the dial position between *too warm and apologetic* and *too
clipped and cold*. No real correspondence, names, or content were used. The app
runs locally; if you paste private source context, it stays in your browser until
you copy the generated prompt wherever you choose.

## How to open
Double-click `index.html`, or drag it into any modern browser. Everything runs
locally — no network calls, no installs, no server. Works equally well on a
phone (mobile-first layout, 44px touch targets) or a desktop browser.

## Controls
1. **Pick a scenario** — six common reply situations.
2. **Start from a preset** *(optional)* — six calibrated starting points.
3. **Calibrate the dials** — Warmth, Directness, Formality, Urgency, Brevity.
   Each is a 0–100 slider with named ends (e.g. *cool ↔ warm*).
4. **Paste source context** — the message/thread/situation the AI should answer
   from.
5. **Required moves** — toggle chips for the structural beats the reply must
   include.
6. **Forge prompt** — generates a complete paste-ready prompt + tone read +
   checklist. **Reset** restores the default state.
7. **Copy prompt** or **Copy calibration brief** for use in an AI tool.

The prompt adapts to your settings — for example, high *Directness* tells the AI
not to bury the point, high *Urgency* asks for a concrete deadline or reason, and
high *Brevity* pushes for a concise final reply.

## Why it was revised
The first version produced a fill-in skeleton. This revision turns the same
calibration studio into a practical bridge to AI tools: paste source context once,
calibrate the dials, then copy a prompt that instructs Claude/ChatGPT to produce
the complete ready-to-send answer while preserving facts and avoiding invented
commitments.

## Format choice & how it differs from recent surprises
- **Format:** writing / prompt-construction micro-tool with a playful calibration
  loop (dials + presets + source context + diagnostic badges).
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
no storage — one HTML file.
