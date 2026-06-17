# Angle Atlas

A tiny interactive **field guide for ideas** — a swipe/tap-through visual zine of six
perspective-shift chapters. Each chapter takes one abstract "idea specimen" and performs a
small visual transformation on it, paired with a single concise prompt that nudges you to look
at whatever you're working on from a different side.

The six chapters:

1. **Tilt** — rotate your point of view
2. **Crop** — cut everything but one part
3. **Invert** — flip it inside out
4. **Zoom** — push in past the surface
5. **Sequence** — lay it out as steps in time
6. **Name** — give it a true label

## What it is

A self-contained HTML page. No build step, no network calls, no dependencies. A generative SVG
"specimen" is drawn from a seed and re-transformed per chapter (rotated, cropped, inverted,
magnified, broken into frames, or labeled). A **Remix** button reshuffles both the prompt and
the specimen so the same lens keeps offering fresh angles. You can jot a short note about what
an angle revealed and save it — notes persist in `localStorage` on your device only.

## Privacy-safe inspiration

The generic feeling of turning an idea over and over — viewing it from new angles until it
stops being flat and starts having dimensionality. No real projects, people, or specifics; just
the universal habit of asking "what if I looked at this another way?"

## How to open

Double-click `index.html`, or drag it into any modern browser. Works fully offline. Best on a
phone, but fine on desktop too.

## Controls

- **Chapter dots** (top) — jump straight to any of the six angles
- **‹ / ›** or **swipe left/right** — flip between chapters
- **← / →** arrow keys — flip between chapters
- **Remix this angle** (or tap the card / press Space) — new prompt + new specimen
- **Note field + ✦** — save a thought about the current angle (Enter also saves)
- **×** on a saved note — remove it
- All buttons are keyboard-focusable with visible focus rings; touch targets are ≥44px

## Why it was built

A Daily Surprise — one small, self-contained, runs-anywhere thing per day. This one leans into
recent visual-design exploration energy: trying different angles on an idea, deliberately moving
away from overused launch/readiness framing, and making the act of "looking again" feel tactile
and pleasant rather than evaluative.

## Format choice

- **Lane:** visual_story_or_comic
- **Mechanic:** a swipe/tap-through interactive zine of six perspective-shift cards, each with a
  tiny visual transformation and one concise prompt, plus a shuffle/remix button and optional
  saved notes — no scoring, no readiness meter, no launch sim.

## Avoided recent patterns

- No launch / readiness / shipping simulators
- No generic scorecard or rubric meters
- No abstract AI-agent context / preflight / debugger tooling
- No repeat of the recent spatial tile puzzle / light-routing game (Signal Garden)
