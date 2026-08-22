# Scroll Seismograph — A Gesture Motion Recorder

*Daily Surprise · 2026-08-22*

## What it is

Scroll Seismograph is a self-contained interaction lab that turns a short scroll performance into a visible motion trace. Scroll, swipe, or drag through the specimen track and the instrument records position, velocity, acceleration, direction changes, and frame gaps as a temporal seismogram.

A built-in fictional demo trace makes the interface ready immediately. Record Take A and Take B, compare their shapes, replay either take against a ghost marker, and export the current visualization as a genuine local SVG.

This is an exploratory browser instrument, not a hardware-latency measurement or accessibility-compliance test. Browser event timing and rendering behavior vary by device.

Everything runs in the current browser tab. There are no external assets, network requests, analytics, accounts, persistence, uploads, camera, or microphone.

## Privacy-safe inspiration

The broad inspiration was the generic rhythm of reviewing changing work, noticing where motion becomes rough, and improving handoffs. That theme became a fictional gesture recorder without using or referring to any real person, organization, product, project, customer, account, message, conversation, or source data.

## How to open

Open `index.html` directly in any modern browser. No server, installation, package, account, or internet connection is required.

## Controls

- **Touch, drag, or use the mouse wheel** inside the specimen track to create a gesture trace.
- Choose **Take A** or **Take B** before recording to preserve two performances for comparison.
- Use **Replay** to animate the chosen trace with its ghost position.
- Toggle the comparison view to inspect both takes together.
- Open or reload the page to restore the deterministic built-in demo takes.
- Select **Export SVG** to download a vector snapshot of the current seismogram.
- Use **Clear take** to reset the active slot.

## Why it was built

Small interaction details are often discussed as adjectives—smooth, heavy, nervous, abrupt—when their shape is easier to understand by seeing it. Scroll Seismograph makes that shape tangible without turning it into a grade. It is a compact example of a browser prototype that can capture a real gesture, replay it, compare alternatives, and produce a useful artifact locally.

## Format choice

- **Lane:** `data_visualization` — presented as a polished future artifact and real-feeling local interaction lab.
- **Mechanic:** live touch, pointer, and wheel gesture capture rendered as velocity, acceleration, and frame-gap time series; deterministic two-take replay and comparison; genuine SVG export.

This differs from the previous three surprises’ vanishing teleprompter rehearsal, particle-physics sand instrument, and direct phone-canvas target manipulation. It deliberately avoids the recently dominant map/explorer and card-board interaction patterns.

## Explicit bans avoided

- No field-guide, pocket-guide, zine, atlas, almanac, codex, or bestiary framing.
- No choose-your-own, branching-story, microquest, or multiple-ending mechanic.
- No signal-routing, cartographer, constellation, path-connection, or node-linking metaphor.
- No visual story or comic lane.
- No launch, readiness, shipping, or preflight simulator.
- No scorecard or rubric meter.
- No abstract AI-agent context or generic debugger concept.
- No poetic generator.
- No family/travel planner, baseball toy, or local-home utility.

## Privacy

The included specimen and demo data are invented and neutral. Recording is limited to gesture timing and movement inside the page and remains in memory in the current tab. Nothing is uploaded or persisted.
