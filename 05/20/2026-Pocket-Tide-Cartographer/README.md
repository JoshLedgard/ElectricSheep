# Pocket Tide Cartographer — May 20, 2026

## What it is
A pocket harbor-charting toy. Tap a quiet bay to drop small buoys (channel, port, hazard, anchor), tap each buoy to spin its current toward N / E / S / W (or back to still), nudge the tide slider from low water through flood to high, and then "Chart the Harbor" to mint a tiny named harbor card with a chart number, a drift report, mean depth, and a one-line motto.

It's a 2–3 minute, mobile-first interactive toy. Up to twelve buoys per chart. The composed harbor name, motto, depth, and chart № are deterministic — the same buoy layout + tide always produces the same little card — but every nudge of position, current direction, or tide level shifts the result, so small changes keep the chart feeling alive.

## Privacy-safe inspiration
Built around generic themes only: fresh start, morning curiosity, playful systems, calm exploration, tiny creative ritual. No real names, numbers, addresses, conversation details, or personal references. All language drawn from a neutral harbor / cartography vocabulary (buoys, tide, drift, anchorage).

## How to open
- Tap `index.html` (works in any browser, no install, no network).
- Best on a phone or tablet held in portrait.

## Controls
- **Palette row (top):** pick a buoy type — Channel (green), Port (red), Hazard (yellow), or Anchor (white).
- **Chart:** tap anywhere on water to drop a buoy. Each buoy is numbered in drop order. Land and shore are blocked.
- **Tap a buoy:** spins its current arrow through N → E → S → W → still and back.
- **Tide slider:** drags from Low through Mean to High; tints the water and shifts mean depth in the report.
- **Nudge:** if the chart is empty, sprinkles five starter buoys in safe water; otherwise jiggles every existing buoy a small amount.
- **Clear:** removes all buoys and the result card.
- **Chart the Harbor** (unlocks at 3+ buoys): generates a named harbor, a chart number, prevailing drift, mean depth, and a tiny motto sentence.

## Why it was built
A small daily surprise — one self-contained creative-coding toy per day. This one leans into the feeling of a slow, careful planning ritual: drop a few small marks in a quiet bay, watch the currents agree or disagree, set the tide, and walk away with a named little harbor — a tiny chart-room of a morning.

Self-contained, runs offline, no dependencies.
