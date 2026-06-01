# Clarity Cartographer — Tiny Support Site Triage Map

**Daily Surprise · 2026-06-01**

## What it is

A compact, self-contained micro-tool for turning fuzzy support-site critique into a clear map of what to do next. Six abstract "surface cards" stand in for the regions of any support / help / docs site — landing, search, article body, onboarding, escalation, account & settings. For each one you nudge four dials (Reach, Pain, Confidence, Effort) and the tool deterministically produces:

- A **priority score** per surface: `(Reach × Pain × Confidence) ÷ Effort`
- A **2×2 quadrant map** (Impact vs Effort) with the top card highlighted
- A ranked **triage order** with a suggested next action per card
- A **copyable action plan** you can paste into notes or a ticket

It's a tiny instrument for the moment when you have a pile of vague observations about a site and want one honest "do this first" answer.

## Format choice

Practical product/support micro-tool + prioritization puzzle. Deliberately different from the last three surprises: not a tone calibration studio (2026-05-31), not an agent-memory debugger (2026-05-30), not a launch-readiness allocation simulator (2026-05-29). This one feels like a pocket-sized map you'd pull out before a triage meeting.

## Privacy-safe inspiration

A general energy lately around evaluating support and product surfaces honestly, organizing scattered observations, and turning critique into concrete priorities. No real site, ticket, person, message, or quoted wording is referenced — only abstract surface labels (Landing, Search, Article, Onboarding, Escalate, Account).

## How to open

Open `index.html` in any modern browser. No server, no installation, no network calls, no external assets. Works on mobile (designed for 390px first) and desktop. Tap the cards, slide the dials, watch the map.

## Controls

- **Sliders (per card):** Reach (1–10), Pain (1–10), Confidence (1–5), Effort (1–10)
- **Copy action plan:** copies the ranked triage plan as plain text
- **Preset · Balanced:** sensible starting point
- **Preset · Messy:** a chaotic critique state — fun to see how the map sorts it
- **Reset:** restore the balanced defaults

The dot for the current top-priority surface glows on the map; that same surface gets a highlighted border on its card.

## Why it was built

Triage conversations often stall because the inputs are fuzzy ("this part feels rough"). A small forcing function — explicit dials, a deterministic score, a visible quadrant — converts soft critique into a defensible "ship this first." This isn't a replacement for judgment; it's a way to externalize the trade-off so you can argue with the map instead of with each other.

The whole thing fits in one HTML file so it can ride along in a notes app, a USB stick, or a flight without wi-fi. Privacy-preserving by construction: there is nothing to phone home.
