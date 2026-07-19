# Draftlight — A Manuscript Light Table

## What it is
Draftlight is a tactile, local-only manuscript light table for prose. You paste any
piece of writing and it lays the text on a glowing "glass," slicing it into movable
**sentence strips** — one strip per sentence. Beneath the strips it renders the
manuscript's **sentence-length rhythm as a skyline** (each bar is one sentence; taller
bars are longer sentences) and surfaces three neutral, descriptive observations:

- **Repeated openings** — sentences that begin with the same word (or word pair).
- **Nearby echoes** — meaningful content words that recur within a couple of neighboring sentences.
- **Long / dense stretches** — sentences that run notably long.

You can **focus** any pattern (spotlighting matching strips while dimming the rest),
**reorder** strips with large ▲▼ touch controls, **edit** any sentence in place,
**remove** strips, then **copy** the revised draft back out or **reset** to the original.

It is a direct-manipulation editor/instrument, not a score, grade, or generator.
Every observation is phrased as something to *look at*, never something that is *wrong*.
There are deliberately **no ratings, grades, benchmarks, or advice**.

## Privacy-safe inspiration
A generic interest in turning busy operational text and recurring workflows into clearer,
calmer artifacts — the feeling of wanting a messy running log to become one page a calm
person would actually want to read. The built-in sample is entirely invented and generic;
it mentions no real people, companies, projects, tickets, or messages.

## How to open
Open `index.html` in any modern browser — desktop or mobile. No install, no server,
no build step, no network connection. Just double-click the file (or drag it into a
browser tab). Everything runs inside that one tab.

## Controls
- **Slice into strips** — split the pasted prose into sentence strips and light the table.
- **Load sample** — drop in the built-in synthetic manuscript to see everything working.
- **Clear** — empty the input and return to the dark-glass empty state.
- **Rhythm skyline** — tap (or keyboard Enter/Space on) any bar to spotlight that sentence's strip.
- **Focus toggles** — Repeated openings / Nearby echoes / Long ∙ dense: turn one or more on to
  highlight matching strips and dim the rest. Turn them all off to see everything evenly.
- **▲ / ▼** — move a strip up or down (large 44px touch targets, keyboard focusable).
- **✎ Edit** — edit a sentence's text inline; **Save** or **Cancel**.
- **✕** — remove a strip.
- **Copy revised draft** — copy the current strip order (with your edits) to the clipboard.
- **Reset order & edits** — restore the original sentences and order from the last slice.

Accessibility: viewport-fit mobile-first layout, no horizontal overflow at 390px, all
interactive controls are ≥44px, everything is keyboard operable, and a
`prefers-reduced-motion` block disables motion and smooth scrolling.

## Why it was built
Operational writing tends to accumulate — stand-up notes, status logs, recurring updates —
and it drifts toward sameness: the same sentence openings, the same words echoing a line
later, the occasional runaway sentence that swallows a whole paragraph. Most tools that
"help" respond by grading you. Draftlight refuses to. It just turns the invisible shape of
your prose into something you can see and physically rearrange on a lit workbench, so the
revision is yours to make. It's meant to be understandable in about 20 seconds and genuinely
useful for a couple of minutes of real editing.

## Format choice
- **Lane:** writing_or_decision_aid
- **Mechanic:** a tactile, local-only manuscript light table. The user pastes prose; the app
  slices it into movable sentence strips, renders sentence-length rhythm as a visual skyline,
  highlights repeated sentence openings / nearby repeated words / long dense stretches without
  grading them, lets the user focus or dim patterns, reorder strips with large touch controls,
  edit text, remove strips, and copy the revised draft. A useful direct-manipulation editor
  and instrument — not a score or a generator.

Chosen because the brief calls for something *useful* and *instrument-like*: an illuminated
editorial workbench that manipulates the user's own words directly, rewards 2–3 minutes of
hands-on editing, and produces a real artifact (the revised draft) rather than a verdict.

## Explicit bans avoided
No field guide / zine / atlas / almanac / codex framing. No choose-your-own, branching story,
microquest, or endings. No signal / cartographer / constellation / routing / path-connection
metaphor. No visual story or comic. No launch / readiness / shipping simulator. No scorecard,
rubric, grade, benchmark, preflight, or abstract AI-agent context debugger. No generic
generator. Analysis is descriptive and observational, never evaluative.

## Privacy & data
Entirely self-contained: inline HTML/CSS/JS only, no external assets, packages, fonts, network
requests, servers, storage, cookies, or telemetry. Your text lives only in this tab's memory
and is never written to disk or transmitted; it disappears when you close the tab. User text is
rendered with `textContent` / text nodes only — no user-supplied HTML is ever injected.
