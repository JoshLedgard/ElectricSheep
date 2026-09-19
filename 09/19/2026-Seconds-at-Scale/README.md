# Seconds at Scale

## What it is

A tactile, real-feeling data visualization for seeing how tiny moments of latency compound across repeated workflows. Adjust daily moments, delay per moment, and active people; the dashboard turns those assumptions into daily, monthly, and annual human waiting time. Presets provide useful starting points, and a comparison shows the attention returned by cutting delay in half.

## Privacy-safe inspiration

Inspired by the cadence of recurring systems and the product-design question of when a tiny inconvenience becomes meaningful at scale. It uses generic examples only and contains no personal or private context.

## How to open

Open `index.html` in a modern browser. It is a single self-contained file and requires no server, account, network connection, package install, or build step.

## Controls

- Choose an **AI assistant**, **Checkout**, or **Dashboard** preset, or start with **Custom**.
- Drag **Daily moments**, **Delay each**, and **Active people**.
- Watch the annual total update while the normalized curve shows the share accumulated from January through December.
- See estimated daily/monthly waiting and average concurrent waiting, assuming activity is spread evenly through each day.
- Compare the current model with a version that cuts delay in half.

## Why it was built

Milliseconds are abstract; accumulated human time is concrete. This turns a common product tradeoff into something that can be manipulated, seen, and discussed in under two minutes.

## Format choice

- **Lane:** `data_visualization`
- **Mechanic:** direct-manipulation parameter scrubbing with a live temporal accumulation curve and before/after comparison

## Explicit bans avoided

- No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing.
- No choose-your-own, branching story, microquest, or multiple-ending mechanic.
- No signal-routing, cartographer, constellation, path-connection, or connect-the-nodes metaphor.
- No launch, readiness, release, or shipping simulator.
- No generic scorecard or rubric meter.
- No abstract AI-agent context, preflight, prism, or debugger tool.
- No generic poetic generator.
- No music grid or step-sequencer mechanic.

## Privacy and implementation

All calculations and drawing happen locally in the browser. There are no external libraries, assets, analytics, trackers, forms, network requests, accounts, or stored personal data. The values are hypothetical assumptions, not telemetry. The interface uses touch-friendly controls, has no page-level horizontal overflow at narrow mobile widths, and respects reduced-motion preferences.
