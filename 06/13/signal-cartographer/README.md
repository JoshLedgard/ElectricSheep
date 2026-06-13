# Signal Cartographer

## What it is
A tiny, self-contained spatial puzzle. You trace a single route across a small grid
from **Start** to **Finish**, picking up every **signal** tile while routing around the
**noise** tiles. Three handcrafted levels, gentle visual feedback, and a quick win
animation. The whole thing is one `index.html` — no install, no network, no accounts.

Plays in about 2–3 minutes.

## Privacy-safe inspiration
A generic morning-curiosity theme: taking a field of noisy inputs and mapping it into
one clear, useful route. No personal data, no private details — just the idea of turning
scatter into a single legible path.

## How to open
Double-click `index.html`, or drag it into any modern browser (mobile or desktop).
That's it — everything runs locally in the page.

## Controls
- **Touch / mouse:** press the glowing Start tile and drag across neighboring cells to
  extend your route. Drag back onto your own trail to undo a step.
- **Tap-by-tap:** instead of dragging, tap adjacent cells one at a time.
- **Keyboard:** Arrow keys extend the route, **Backspace** undoes a step, **R** resets the
  level, **Enter** advances to the next level once solved.
- **Buttons:** **Reset** clears the current route; **Next** appears when the level is solved.

Win a level by reaching the Finish tile with every signal collected.

## Why it was built
A small daily surprise for Josh — a finished little puzzle that rewards a couple of
focused minutes and leaves a satisfying "one clean route" feeling. It's deliberately
bounded: small grids, handcrafted and solvability-checked levels, and a single reliable
artifact rather than anything open-ended.

## Format choice
- **Lane:** game_or_puzzle
- **Mechanic:** spatial path-drawing puzzle on a small touch-friendly grid — connect Start
  to Finish while collecting signal tiles and avoiding noise tiles, across three
  handcrafted levels with gentle visual feedback. Mobile-first, 44px+ touch targets, and
  unified touch / mouse / keyboard input with reset support.

## Avoided recent patterns
- Not a launch / readiness / shipping simulator
- Not a scorecard / rubric / meter
- Not an AI-agent preflight or context debugger
- Not a poetic / generative text toy
