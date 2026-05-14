# Kite Signal Atelier · May 14, 2026

A pocket sky workshop. Pick a kite shape, tie a handful of colored ribbon knots, tune the wind and the tether lift, and watch a small paper kite climb the screen on its own thread. When you're ready, the atelier folds the moment into a tiny named "signal card" — a one-paragraph reply from the sky you can copy into a note.

## What it is

A self-contained, mobile-first generative toy. One HTML file, no network, no server, no install. It runs in any modern browser.

- **Stage**: a softly animated SVG sky with drifting clouds, a few stars, and an animated kite tethered to the bottom of the frame. The kite sways and tilts according to the wind and lift sliders.
- **Kite shape**: choose between Diamond, Delta, Box, or Swallow. Each redraws the kite in place.
- **Ribbon knots**: six round buttons in coral / sea / sun colors. Tap to tie them onto the kite — they appear as little SVG bows.
- **Wind, lift, tail**: three sliders that change how the kite flies and how long its tail is.
- **Send Signal**: generates a paper signal card with a generated name (e.g. "Lantern Postcard"), a short warm paragraph that reads back the choices you made, and Copy / Another buttons.
- **Reset**: clears the atelier back to a starting kite.

## Privacy-safe inspiration

This one steps away from the last three days' map / weather / orchard surprises and leans into a tactile sky toy. The theme is the simple delight of a paper kite — making something small, tuning it, then letting wind carry the result. All copy is generic and warm; the toy never asks for or stores personal data.

## How to open

- Open `index.html` directly in any modern browser (mobile or desktop).
- No build step. No network needed. Works offline.

## Controls

- **Tap a shape** at the top to change the kite.
- **Tap a colored button** in the Ribbon Knots row to tie or untie that knot.
- **Drag a slider** to set wind puff, tether lift, or tail length. The kite responds live.
- **Send Signal** to generate a signal card. **Copy** puts the card on the clipboard; **Another** rerolls just the wording.
- **Reset** returns the atelier to its starting state.
- Buttons are 44px+ touch targets, keyboard focusable, and labeled for assistive tech. The animation respects `prefers-reduced-motion`.

## Why it was built

Daily Surprise for 2026-05-14. The brief was a mobile-first tactile toy that's different from the recent run of cartography- and weather-themed pieces — something with a single object you can shape, decorate, and send. A kite is a small visible system: a few choices, a bit of wind, and a moment that becomes a thing you can pocket.
