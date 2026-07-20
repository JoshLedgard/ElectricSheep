# Human Afterimage — A Live Gesture Observatory

## What it is
A tactile, single-screen instrument for looking at your own hand motion. You draw **one continuous gesture** on a large canvas — a loop, a signature, a scribble — and the app replays it as a **luminous afterimage** while four synchronized strips make the invisible motion inside that stroke legible over time: **Speed**, **Curvature**, **Gesture energy**, and **Stillness (pauses)**.

Nothing is scored, graded, or judged. It is an expressive, museum-style data visualization of a single gesture. You can scrub the timeline (a marker moves through the drawing and every strip at once), play/pause the replay, switch among three visual lenses, replay from the start, clear, and export the trace as **PNG** or **SVG**.

The strips are honest about what they show. Speed is distance over time between samples. Curvature is how sharply direction turns at each step. **Gesture energy is derived from speed as a proxy for how firmly you seemed to press — pointers report no real pressure here, so nothing labeled "pressure" is ever claimed or measured.** Stillness rises where the hand hesitated.

## Privacy-safe inspiration
The only theme borrowed from recent context is the generic, privacy-safe idea of **careful operational work and making invisible activity legible** — turning something usually unseen (the texture of a motion) into something you can watch and read. No real people, projects, messages, organizations, names, or data appear anywhere. Every value on screen comes from the stroke you just drew, computed on your device.

## How to open
Open `index.html` in any modern browser — desktop or phone. No install, no server, no network, no accounts. Double-click the file, or drag it into a browser tab. It works fully offline. On a phone, draw with a finger; on a desktop, draw with the mouse or a trackpad.

## Controls
- **Draw:** press and drag one continuous stroke on the panel. Release to capture it; the afterimage replays automatically.
- **Play a demo gesture:** the button in the empty state animates a built-in example so the instrument is understandable immediately.
- **Play / Pause (round button):** run or hold the afterimage replay.
- **Scrubber (timeline slider):** drag to move the "now" marker through the drawing and all four strips together, at any point in time.
- **Lens (Comet / Ribbon / Ink):** three ways to color and weight the afterimage — by speed, by curvature, or by gesture energy.
- **Replay:** restart the afterimage from the beginning.
- **Clear:** discard the current gesture and return to the empty state.
- **Export PNG / Export SVG:** save the afterimage as an image or vector file, captioned with duration and path length.

The empty state shows a breathing target and instructions; if a stroke is too short to be meaningful, it is politely ignored and the empty state returns. Users who prefer reduced motion get the full afterimage without the animated sweep.

## Why it was built
As a daily creative-coding surprise, the goal was a polished, surprising, museum-instrument feel that is understandable within about twenty seconds and rewarding for two or three minutes of direct manipulation. A gesture observatory fits: drawing is immediate and personal, the replay is deterministic, scrubbing gives real tactile control, and the strips turn a fleeting motion into a readable record — legibility of invisible activity, without ever scoring the person. Honesty about the derived "gesture energy" quantity keeps the visualization trustworthy.

## Format choice
A single self-contained `index.html` with inline CSS, JavaScript, and generated art — no packages, network, external assets, or build step. Canvas is used for the drawing surface and the four metric strips, sized for device pixel ratio and driven by pointer events with `touch-action: none`, so it feels crisp and responsive on a phone at 390px and up.

- **Lane:** data_visualization
- **Mechanic:** a tactile single-screen gesture observatory — draw one continuous touch/mouse gesture, then watch it replay as a luminous afterimage while synchronized, non-scoring strips visualize speed, curvature, derived gesture energy, and pauses over time; scrub the timeline, switch among three visual lenses, replay, clear, and export as SVG or PNG.

## Explicit bans avoided
- No field guide / zine / atlas / almanac / codex framing.
- No choose-your-own or branching story.
- No signal routing / cartography / constellation / path-connection metaphor.
- No launch / readiness / shipping simulator.
- No scorecard / rubric / meter (metrics are descriptive strips, never scores or judgments).
- No preflight or abstract AI-agent context debugger.
- No family / travel / baseball / local-utility theme.

## Privacy check
Local-only. No network requests, no external resources, no persistence, no analytics, no accounts. Contains no real names, emails, dollar amounts, addresses, quotations, phone numbers, private details, or sensitive specifics. All visualized values are computed live from the single gesture the user draws and exist only in memory until cleared. Exports are generated on-device and saved by the user's own browser.
