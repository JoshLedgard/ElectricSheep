# Thought Tempo — An Inference Instrument

## What it is
A tactile fake-hardware instrument you play with your thumbs. Three large pads —
**Focus**, **Drift**, and **Spark** — set the intensity of three rhythmic voices.
A rotary **Tempo** dial changes how fast the pulses arrive, and **Run Pulse** plays a
short (~15–27 second) deterministic "thinking performance": animated bands sweep across
a glowing timeline under a moving playhead, with optional Web Audio tones. Every control
reshapes the rhythm and visual pattern in an immediately perceptible way. Includes
**Replay**, **Reset**, an opt-in **Sound** toggle, and three deterministic presets
(Steady / Weave / Flurry).

It is an instrument and toy — a tactile visualization of computational *tempo* — not an
assessment, benchmark, or measurement of anything.

## Privacy-safe inspiration
A recent, generic interest in configuring and comparing AI tools inspired a playful way
to *feel* the difference between fast and slow, sparse and dense computational rhythms.
Nothing here represents a real model, benchmark, account, conversation, or dataset — all
labels, voices, and patterns are entirely synthetic and fixed in the code.

## How to open
Open `index.html` in any modern browser (desktop or mobile) by double-clicking it or
dragging it into a browser window. No install, server, network connection, fonts, or
external assets are required — the whole instrument is a single self-contained file.

## Controls
- **Focus / Drift / Spark pads** — tap (or press Enter/Space when focused) to cycle each
  voice through intensity 0 → 1 → 2 → 3. Focus is a steady beat, Drift adds syncopation,
  Spark adds accents. Lit bars and a glowing dot show the current level.
- **Tempo dial** — drag up/down to speed up or slow down. When focused it also responds to
  Arrow keys (±2), Page Up/Down (±10), and Home/End (min/max). Range 70–120 bpm.
- **▶ Run Pulse** — plays the current pattern; press again to stop.
- **↺ Replay** — replays with the current settings.
- **⟲ Reset** — returns all controls to their defaults.
- **🔇 Sound** — audio is off by default; press to opt in. If Web Audio is unavailable the
  button shows N/A and the instrument keeps playing visually.
- **Presets** — Steady, Weave, and Flurry load fixed, reproducible control states.

The timeline always shows a live preview of the current pattern, so changes are visible
before you press Run.

## Accessibility & determinism
Mobile-first with no horizontal overflow at 390px; all interactive targets are at least
44px. Pads and transport are real buttons; the dial is a keyboard-operable ARIA slider;
status is announced via a polite live region. `prefers-reduced-motion` is respected
(decorative glow/scaling is suppressed). Given a fixed pad/tempo state the generated
rhythm is fully deterministic — the presets make the output reproducible for verification.

## Why it was built
Built as the Daily Surprise for 2026-07-15: a small, surprising, polished object that
turns an abstract idea — that different computations have different *rhythms* — into
something you can touch, twist, and hear in a couple of minutes, without any real data.

## Format choice
- **Lane:** data_visualization
- **Mechanic:** tactile audio-visual sequencer / fake hardware instrument

The instrument is a tactile sequencer: physical-feeling controls drive a deterministic
event pattern rendered as animated bands/pulses on a timeline, with optional synchronized
Web Audio tones — a hands-on visualization of rhythm rather than a chart to read.

## Explicit bans avoided
This build deliberately avoids every banned form:
- No field guide / atlas / almanac / codex / zine framing.
- No choose-your-own, branching story, microquest, or multiple endings.
- No signal / cartographer / constellation / routing / path-connection metaphor.
- No visual story or comic.
- No launch / readiness / shipping simulator.
- No scorecard / rubric / meter / grading (it is an instrument, not an assessment).
- No preflight / context debugger.
- No generic text generator.
- No family / travel / baseball / local-utility theme.
