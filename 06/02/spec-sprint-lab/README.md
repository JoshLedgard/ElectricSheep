# Spec Sprint Lab — Tiny Acceptance-Criteria Game

**Date:** 2026-06-02
**Title:** Spec Sprint Lab — Tiny Acceptance-Criteria Game

## What it is

A self-contained, mobile-first browser toy that turns the messy work of "what does done look like?" into a tactile two-minute game. You pick one of five fictional projects, sort ten candidate requirement chips into three lanes — **Must prove**, **Nice signal**, **Risk watch** — keep an eye on a 10-point scope budget, then run a deterministic "ship check" that scores clarity, verifiability, risk coverage, and scope discipline. Output: a copyable acceptance checklist plus a short judge note explaining whether the spec is sharp enough to stop an autonomous agent loop.

## Format choice

Tiny game / puzzle crossed with a product-strategy / evaluation tool. It differs from the last three surprises:

- It is **not** the support-site triage priority map (Jun 1, Clarity Cartographer).
- It is **not** the AI prompt-output studio (May 31, Reply Forge).
- It is **not** the agent memory debugger (May 30, Signal Garden).

This one is a playful training simulator for writing crisp acceptance criteria — the artifact you'd hand to a loop and walk away from.

## Privacy-safe inspiration

Generic theme only: a fresh-start, morning-curiosity, playful-systems mood. The five projects in the game are made-up fictional names (Atlas Builder, Loop Tamer, Inbox Sieve, Ledger Lens, Pulse Walker) and the chip text is generic product-spec phrasing. No real names, emails, phone numbers, addresses, financial data, private domain or repo names, or paraphrases from any specific conversation appear in the artifact.

## How to open

Double-click `index.html`, or drop it on any modern browser. Works offline, no install, no network, no dependencies.

## Controls

- **Step 01 — Pick a project.** Tap one of the five project cards. Switching projects clears your current chip assignments (with a confirm).
- **Step 02 — Sort the chips.** Each chip has four lane buttons:
  - **M** — Must prove (verifiable acceptance criteria)
  - **N** — Nice signal (proxy / qualitative indicators)
  - **R** — Risk watch (failure modes to monitor)
  - **X** — Skip (explicitly leave out)
  Tap a lane to assign. Tap the same lane again to un-assign. The lane counters at the top and the scope-budget bar update live.
- **Step 03 — Run the ship check.** Tap the primary button. A scored dial appears with a verdict (Ship-grade / Defendable / Drafty / Speculative), a four-line breakdown, a tailored judge note, and your acceptance checklist.
- **Copy buttons** — One for just the checklist, one for the full report (verdict + breakdown + judge note + checklist). Falls back gracefully if the clipboard API is blocked.
- **Reset** — Clears assignments for the current project.

## Why it was built

The brief was to make something playfully practical that fits Josh's mood today: a fresh-start, morning-curiosity, playful-systems theme, in a lane the last three surprises haven't touched. Acceptance criteria are the seam where vague intent becomes something an autonomous loop can actually finish — and getting them wrong is one of the quietest ways for an agent to burn cycles. A tiny chip-sorting game makes that craft feel light: pick what's verifiable, pick what's a proxy, pick what could break, leave the polish off. The deterministic scoring keeps every run honest, and the copyable checklist is something you could actually paste into a real spec.

## Privacy check

- No real names, emails, phone numbers, addresses, or financial data.
- No private domain names, repo names, internal product names, or coworkers.
- All five "projects" are fictional generic concepts; all chip text is generic product-spec phrasing.
- No close paraphrases of any conversation content.
- Runs entirely offline. No network calls, no analytics, no external assets, no fonts, no images.
