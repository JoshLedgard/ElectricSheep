# Blinkforge

## What it is

Blinkforge is a tactile five-round visual-memory game. Each 8×8 glyph appears for four seconds, vanishes, and must be reconstructed one pixel at a time. The finished run becomes a downloadable specimen sheet showing what memory preserved—and what it quietly redesigned.

It is a self-contained, local-first browser artifact with touch, mouse, and keyboard controls. It makes no network requests and needs no account or server.

## Privacy-safe inspiration

The inspiration was a generic interest in crisp product craft, reliable interaction, and turning close observation into something tangible. No private conversation, personal data, or identifying detail appears in the artifact.

## How to open

Open `index.html` directly in a modern browser. No install, build command, or local server is required.

## Controls

- **Begin the glance:** show the current glyph for four seconds.
- **Pixel canvas:** tap or drag to paint and erase pixels; focused cells also toggle with Space or Enter.
- **Clear canvas:** erase the current reconstruction.
- **Flash hint:** spend the round’s single one-second glimpse.
- **Reveal the trace:** compare the reconstruction with the source; red marks extra pixels and blue marks missed pixels.
- **Next specimen:** continue through five rounds.
- **Download specimen sheet:** export all five reconstructed glyphs as a PNG.

Progress is kept locally in the browser when storage is available.

## Why it was built

Most interfaces reward speed and recognition. Blinkforge asks for a different kind of attention: look briefly, hold a silhouette, and then make memory physical. It is a tiny game, a drawing instrument, and a reminder that imperfect recall can create a visual language of its own.

## Format choice

- **Lane:** `game_or_puzzle`
- **Mechanic:** timed visual-memory reconstruction on a tactile 8×8 pixel canvas, followed by a trace overlay and downloadable specimen sheet.

This differs structurally from recent writing tools, music sequencers, and Monte Carlo visualizations.

## Explicit bans avoided

- No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing.
- No choose-your-own, branching story, microquest, or multiple-ending mechanic.
- No signal, routing, cartographer, constellation, or path-connection metaphor.
- No launch, readiness, shipping, scorecard, rubric, meter, grading, or preflight mechanic.
- No abstract AI-agent context/debugging tool or generic poetic generator.
- No family, travel, baseball, home, or local utility.

## Privacy check

The shipped text contains no real names, emails, phone numbers, street addresses, financial details, exact private quotes, or sensitive personal facts. Gameplay data stays on-device.