# Signal to Story Desk

A tiny interactive zine about turning a messy inbox into one clear page. Read a short
branching comic, then work a hands-on "story desk": pull six raw signals onto the
board, file each into the part of the story it serves, and watch a warm **Morning
Brief** postcard assemble itself.

## What it is

A self-contained, mobile-first browser piece in a single `index.html` — no build step,
no network, no packages, no server. Three acts:

1. **The comic** — a 3-panel risograph-style strip with tappable pages and one
   branching choice (it changes the narration; both roads reach the desk).
2. **The story desk** — six fictional "signal" cards in an inbox and three storyboard
   lanes (*Now / So what / Next*). Drag a card into a lane, or tap a card then tap a
   lane. Tap a filed card to send it back. Everything is reversible.
3. **The brief** — once all six are filed, "Compose the brief" weaves your arrangement
   into a customer-facing postcard you can copy to the clipboard.

It is deliberately **not** a score, rubric, or simulator — there is no right answer and
nothing is graded. The reward is the click of a mess becoming a readable page.

## Privacy-safe inspiration

The recent build energy has been about taking messy incoming notes and turning them
into a clear, durable, customer-facing story — tidying scraps into a workflow someone
else can actually read. This zine makes that move physical: catch the signals, sort
them into a shape, and let the brief tell its own story. All content is invented; no
real names, messages, numbers, or specifics appear anywhere.

## How to open

Double-click `index.html`, or drag it into any modern browser. Works fully offline on
phone or desktop. Best viewed on a phone in portrait.

## Controls

- **Tap the comic picture or "Next ›"** — turn the page.
- **Branch buttons (Panel 2)** — pick how you'd start; the narration responds.
- **Tap a signal card** — picks it up (it lifts and the lanes light up).
- **Tap a lane** — files the picked card there.
- **Drag a card** — drop it straight onto any lane (works with touch or mouse).
- **Tap a filed card** — sends it back to the inbox.
- **Keyboard** — focus a card, press Enter to pick up, then `1`/`2`/`3` to file (`0`
  returns it to the inbox).
- **↺ Clear the desk** — empties all lanes back to the inbox.
- **Compose the brief →** — enabled once all six are filed; builds the postcard.
- **⧉ Copy brief** — copies the assembled brief as plain text.
- **↺ Start over** — resets the comic, the branch, and the desk.

## Why it was built

A Daily Surprise for Josh — a small, genuinely usable artifact understood in seconds
and satisfying for a couple of minutes. It leans into the quiet, real skill of deciding
what each scrap *is* and where it belongs, and rewards the sort with a clean page. A
short "why this exists" note lives inside the app itself.

## Format choice

- **Lane:** visual_story_or_comic
- **Mechanic:** interactive branching comic/zine with tappable panels plus a tap-or-drag
  storyboard desk that sorts signal cards into three lanes and reveals a final
  "morning brief" postcard — not a score, rubric, or simulator.

## Avoided recent patterns

Deliberately distinct from recent surprises and the 7-day avoid list:

- No spatial tile puzzle / map or path explorer (yesterday's *Signal Garden* /
  *Signal Cartographer* lane).
- No launch / readiness / shipping simulator.
- No generic scorecard, rubric, or meter.
- No abstract AI-agent context / preflight tool.
- No poetic / generative text generator.

This one is a warm editorial zine + hands-on storyboard editor: story vibe, accessible
controls, reset everywhere.
