# Signal Runway — Preflight for Risky Tiny Ships

**Date:** 2026-06-04

## What it is

A tiny, mobile-first launch-readiness simulator. You pick a small fictional
"ship" — a tiny agent, a public page, a one-shot script, or outbound copy —
mark each preflight gate (evidence, rollback, scope, comms, verify), then
the runway hands you a deterministic verdict and a copyable runbook for the
real launch. Two-to-three minutes, useful as a sanity pass before any small
risky thing.

## Privacy-safe inspiration

Generic thematic energy from the past few days: a lot of evaluation/review
work — small autonomous things ready to be turned loose, support-site
feedback waiting to be acted on, and copy heading out the door. The lane:
"how do I send a tiny thing into the world without regretting it before
lunch?" No real names, projects, quotes, or specifics involved — just the
runway metaphor and five gates that apply to any tiny ship.

## How to open

Open `index.html` directly in any modern browser, on phone or desktop.
It is fully self-contained — no network, no packages, no build step.

## Controls

- **Choose a ship** — four tap targets, picks the language used in tips.
- **Mark each gate** — three-state segmented control per gate:
  `Missing` / `Soft` / `Ready`. Defaults to Soft so the meter starts mid-runway.
- **Run preflight** — computes a deterministic 0–100 score and verdict.
- **Reset gates** — clears the gate states back to Soft.
- **Copy runbook** — copies a plain-text runbook with the verdict, gate
  status, what to fix before liftoff, and what to watch in the first hour.

## Why it was built

To give its reader a playful but practical preflight they can run on the small
things he ships unattended — the kind that look safe right up until they
aren't. The runway metaphor makes the gates feel concrete: you can see the
ship sitting in the hangar, mid-runway, or leaving the strip depending on
the verdict.

## Format choice

Tiny interactive launch/readiness simulator (agent/product reliability
micro-tool lane). Differs from recent surprises:

- Not a brief generator (Context Prism, 06-03)
- Not an acceptance-criteria sorter (Spec Sprint Lab, 06-02)
- Not a support-site priority map (Clarity Cartographer, 06-01)

Here the core mechanic is sequencing/timing — gates on a runway — and the
output is a launch-or-hold call plus a runbook for the actual ship.

## Privacy check

- No real names, emails, phone numbers, addresses, or dollar amounts.
- No private quotes, real projects, or identifying details.
- Inspiration is thematic only — readiness/preflight as a concept.
- All copy is generic ("tiny agent", "public page", "outbound copy").
- No external assets, fonts, scripts, or network calls.
