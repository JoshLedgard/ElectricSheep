# Tailspin Lab

## What it is
An offline, interactive queueing experiment. Adjust traffic, burstiness, worker count, and service time; compare a deterministic baseline with an experiment. Scrub across the timeline to inspect waiting requests, worker occupancy, and rolling latency. The plots reveal why an acceptable average can coexist with a painful tail.

## Privacy-safe inspiration
Inspired by a general interest in inspectable, useful web artifacts and the practical challenge of understanding systems under bursty load. All traffic is fictional and generated locally; no personal, project, customer, or conversation data is included.

## How to open
Open `index.html` directly in a modern browser. No server, account, installation, internet connection, external library, or upload is needed.

## Controls
- Choose a sample traffic scenario or adjust arrival rate, burstiness, workers, and service time using sliders or adjacent step buttons.
- Tap **Pin experiment as baseline** to compare future adjustments against the current configuration. **Reset** restores the starting comparison.
- Drag the time slider, tap/drag either time chart, or play through the run to inspect a specific moment. Reduced-motion settings use larger animation steps.
- Read the queue, completion-latency, and distribution plots together; the p50, p95, mean, and peak are illustrative statistics from the same fictional simulation.

## Why it was built
A tiny hands-on instrument makes burst-driven tail latency easier to feel and explain than a static performance dashboard. The model is illustrative rather than a forecast of a real service; inspect the on-page assumptions before applying any analogy to a production system.

## Format choice
- **Lane:** `data_visualization`
- **Mechanic:** `touch-driven queue simulation with baseline overlay and time scrubbing`

## Explicit bans avoided
No field-guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing; no choose-your-own or branching story; no signal/cartographer/constellation/path-routing metaphor; no launch/readiness/shipping simulator, scorecard, rubric meter, abstract agent preflight, or generic generator. Unlike the preceding screenshot annotation tool, flicker perception game, and sentence-strip editor, this is a quantitative, manipulable visualization.

## Privacy
There are no network requests, trackers, imported assets, personal identifiers, customer records, or sensitive source material. Scenarios are synthetic and all computation remains in the browser.
