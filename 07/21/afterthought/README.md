# Afterthought — A Time-Delayed Scratchpad

## What it is
Afterthought is a small, believable "field unit" for one habit: writing a single short thought
down, sealing it away, and letting it come back to you later — after you've had room to react
calmly instead of in the moment.

You type one short note (up to 180 characters), choose when it should return (from a 60-second
**Demo** all the way to **Next week**), and press **Fold & seal**. A paper slip folds itself and a
wax seal stamps down. The sealed slip drops into *the vault* with a live countdown. When its time
comes, the wafer turns green and a **Break the seal** button appears — tap it and the slip unfolds
so you can read what past-you wanted future-you to see.

Everything is local. Slips live only in this browser's `localStorage`; nothing is ever sent
anywhere. There are no scores, no grading, no card sorting, and no generated prose — just your own
words, held for a chosen amount of time.

## Privacy-safe inspiration
The generic, privacy-safe theme behind it: handling a recurring stream of incoming work calmly, and
deliberately creating a little space before reacting. No real person, employer, project, account,
support request, or conversation is referenced anywhere — all placeholder text is obviously
fictional and generic.

## How to open
Double-click `index.html`, or drag it into any modern browser. It works straight from `file://` with
no server, no install, and no network connection. It is mobile-first and touch-friendly.

**Fastest way to feel the whole loop:** pick the **Demo · 60 seconds** delay, seal a slip, and wait
about a minute — the countdown, the ready state, and the reveal all happen inside 2–3 minutes.

## Controls
- **Note to later** — a paper slip textarea; type one short thought (180-character limit, with a live counter).
- **Bring it back in…** — choose a revisit delay: Demo (60s), 1 hour, 8 hours, tomorrow, a few days, or next week.
- **Fold & seal** — enabled once you've written something and picked a delay; runs the fold + wax-seal animation and stores the slip.
- **The vault** — your sealed slips, newest first, each with a live countdown bar and sealed-at timestamp.
- **Break the seal** — appears on a slip once its countdown reaches zero; unfolds and reveals the text.
- **✕ (per slip)** — delete a single sealed slip (with confirmation).
- **⤓ Export** — download all slips as a local JSON file.
- **Clear all** — remove every slip (with confirmation).
- **Reduced motion** — if your system prefers reduced motion, the fold/stamp animations are minimized automatically.

The countdown is resilient: each slip stores an absolute "reveal at" time, so closing the tab,
reloading, or coming back later all recompute correctly — the clock is never faked from a running timer.

## Why it was built
It's a daily creative-coding surprise: a complete, polished micro-interaction that feels like a real
future device rather than a form. The goal was a satisfying, physical-feeling seal/reveal sequence
paired with genuinely useful behavior — a private place to park a reaction and revisit it when you
have space — all in a single self-contained file with no dependencies.

## Format choice
- **Lane:** practical_micro_tool (presented as a believable future artifact / fake device UI).
- **Mechanic:** a local-only time-capsule scratchpad with a physical-feeling fold/seal interaction
  and a real countdown. You type one short thought, choose a revisit delay, seal it with an animated
  wax stamp, and later reveal it. A clearly labeled 60-second **Demo** mode lets the whole loop be
  experienced in 2–3 minutes. Uses `localStorage` only, with list/delete/export controls and no card
  sorting, scores, grading, or generated prose.

## Explicit bans avoided
- No field guide / zine / atlas / almanac / codex framing.
- No choose-your-own or branching story.
- No signal / routing / cartographer / constellation metaphor.
- No launch / readiness / shipping simulator.
- No scorecard / rubric / meter.
- No abstract AI-agent context / preflight / debugger.
- No generic content generator.
