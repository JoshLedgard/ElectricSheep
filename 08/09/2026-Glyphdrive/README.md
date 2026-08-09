# Glyphdrive — A Kinetic Type Performance Instrument

*Daily Surprise · 2026-08-09*

## What it is

Glyphdrive is a self-contained creative-coding instrument that makes typography playable. Type a short phrase, then push, flick, orbit, and pulse its letterforms directly on a touch canvas. The gesture recorder captures the performance as a compact local event timeline, replays the movement, and exports the current frame as a real PNG still.

A harmless phrase is loaded at opening, with several fictional presets ready for immediate play. It is an instrument rather than a generator: every visible motion comes from the user's gesture and the local spring physics.

## Privacy-safe inspiration

The generic inspiration was a broad interest in reliable interactions and responsive creative tooling. That theme became a tactile browser instrument, without carrying over any people, organizations, projects, conversations, or private details.

Everything stays in the current browser tab. Glyphdrive has no account, network request, upload, analytics, external asset, persistence, microphone, camera, package, or server.

## How to open

Open `index.html` in any modern browser. No installation, build step, package manager, or server is required.

## Controls

- Drag across the performance surface to push and spin nearby letters; speed changes the force.
- Tap a letter—or press **Space**—to pulse the phrase.
- Edit the phrase and choose **Load**, or select a preset phrase.
- Adjust **Spring**, **Drift**, and **Glow** in the physics rack.
- Choose **Record**, perform gestures, stop, then **Replay** the captured event timeline. The progress strip, event count, duration, and mode indicator show the take state.
- Choose **PNG** to download the current canvas as an image.
- Keyboard shortcuts: **R** records/stops and **P** replays/stops.

## Why it was built

Typography tools usually ask users to adjust values and inspect a result. Glyphdrive reverses that relationship: the letters are material and the user performs them. It is a small glimpse of a future creative app where motion design starts with touch rather than a timeline full of keyframes.

## Format choice

- **Lane:** `creative_coding_instrument` — presented as a polished future artifact / fake app.
- **Mechanic:** direct touch-and-pointer performance of kinetic letter physics, with genuine gesture event recording, deterministic replay, live timeline feedback, and PNG still export. This differs structurally from the recent microcopy constraint lab, folding game, and spoken-draft rehearsal desk.

## Explicit bans avoided

Glyphdrive is not a field guide, zine, atlas, almanac, codex, bestiary, or pocket guide. It has no choose-your-own structure, branching story, microquest, endings, signal routing, cartography, constellations, or path-connection metaphor. It is not a visual story/comic, launch/readiness/shipping/preflight simulator, scorecard, rubric meter, grading tool, abstract AI context/prism/debugger, or generic generator. It does not use family, travel, baseball, local, or private data.

## Privacy and accessibility verification

- Shipped text was checked for real names, organizations, emails, phone numbers, addresses, financial information, credentials, exact conversation quotes, and identifying project details; none are included.
- User phrases and recorded gesture events remain in memory only for the current tab. Nothing is transmitted or persistently stored.
- The interface includes a mobile viewport, pointer events for touch/mouse/pen, 44px-or-larger controls, keyboard shortcuts and focus states, responsive layout without 390px horizontal overflow, and reduced-motion handling.
- Self-contained HTML/CSS/JavaScript; no external dependencies or network calls.
