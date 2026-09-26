# Rotation Window

## What it is

A self-contained, tactile data visualization of a fictional credential rotation. Drag the issue, traffic-switch, and revoke markers across a 30-day timeline to see warm-up time, post-cutover exposure, and availability gaps emerge from the sequence.

All scenarios and data are fictional. The artifact runs locally, makes no network requests, and is an educational visualization rather than security advice.

## Privacy-safe inspiration

Inspired generically by reliable automation and routine security maintenance: small timing choices in an invisible system can have visible consequences. No actual account, credential, company, or conversation is represented.

## How to open

Open `index.html` in any modern browser. No server, package install, login, or network connection is required.

## Controls

- Drag **ISSUE**, **SWITCH**, and **REVOKE** along the 30-day timeline with mouse, touch, or pointer input.
- Use each event's **− / +** buttons for precise one-day changes.
- With a marker focused, use the arrow keys to adjust it.
- Choose **Calm handoff**, **Tight window**, or **Outage gap** for a preset.
- Choose **Shuffle** for a fictional arrangement.
- Choose **Replay 30 days** to watch the current lifecycle unfold.
- Tap or click the timeline to inspect a specific day.

## Why it was built

Credential rotation is usually described as a checklist. Rotation Window instead makes the temporal model tangible: provisioning, switching, and revoking become movable moments whose overlap tells the story. It is designed as a compact future-product prototype that can be understood and explored in a few minutes.

## Format choice

- **Lane:** `data_visualization`
- **Mechanic:** `tactile timeline scrubber with draggable rotation and expiration events`

## Explicit bans avoided

- No field guide, zine, atlas, almanac, codex, bestiary, or pocket-guide framing.
- No choose-your-own, branching story, multiple-ending adventure, or microquest mechanic.
- No signal-routing, cartographer, constellation, or path-connection metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard or rubric meter.
- No abstract AI-agent preflight, context prism, or generic debugger.
- No poetic generator.
- No family, travel, baseball, home, Seattle, or other local utility content.

## Privacy and implementation

The page contains no real names, companies, email addresses, keys, addresses, financial data, analytics, external assets, or copied conversation text. It uses only inline HTML, CSS, and JavaScript. The responsive layout is designed to avoid page-level horizontal overflow at a 390px viewport; controls provide at least 44px touch targets, reduced-motion support, and keyboard alternatives.
