# Trace Theatre

Daily Surprise · October 28, 2026

## What it is
A self-contained execution-trace timeline. Paste or import a JSON array of timed steps, inspect parallel work and idle gaps, scrub or play through time, tap a step for its details, and download the visible timeline as an SVG. A fictional workflow loads immediately. Times are milliseconds; parallel step durations are counted separately from wall-clock time.

## Privacy-safe inspiration
Inspired by a general interest in seeing hidden processes as tangible timelines. The example is fictional and contains no personal or business trace data.

## How to open
Open `index.html` directly in a current browser, including offline via `file://`. No server, install, account, analytics, or network connection is needed. Imported data stays in the tab; it is not stored or uploaded.

## Controls
**Load example** restores the sample. Edit the JSON or **Open JSON file**, then **Draw timeline**. The parser accepts `{"spans":[{"name":"Fetch","lane":"Worker A","start":0,"duration":400,"note":"Optional description"}]}`; times are nonnegative milliseconds. Up to 80 spans and 16 lanes are supported, with an end time at most 1,000,000 ms. Use the slider or **Play** to move the cursor; active steps appear in text below the graphic. Tap or keyboard-activate a step button to see its timing and description and jump the cursor to its midpoint. **Download SVG** saves the current picture, including the cursor. Error messages identify invalid JSON and invalid or out-of-range required fields; extra fields are ignored. On small screens the timeline scales down; use the step buttons for readable details.

## Why it was built
A small instrument can make concurrency, latency, and waiting understandable without requiring a tracing service or access to real systems.

## Format choice
- **Lane:** `data_visualization`
- **Mechanic:** local JSON trace import → chronological parallel-span waterfall with scrub/play cursor → step inspection and SVG export. Not the memorization game, drum grid, or frame drawing of the three preceding surprises.

## Explicit bans avoided
Not a field guide, zine, atlas, almanac, codex, branching adventure, signal-routing/cartographer/constellation puzzle, launch/readiness simulator, scorecard/rubric meter, abstract agent preflight, or generic generator. No real names, addresses, emails, phone numbers, financial details, personal messages, or private traces appear in the shipped sample.
