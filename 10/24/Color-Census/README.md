# Color Census

Daily Surprise · October 24, 2026

## What it is
A small offline image instrument that turns the colors in a picture into an area-proportional band and ranked palette. Import a local image, change the number of color groups, inspect pixels, and export CSS variables. A synthetic sample illustration is ready on open. The palette is an approximation from sampled pixels; median-cut grouping is recalculated when the group count changes. Transparency is composited over white for analysis.

## Privacy-safe inspiration
The general pleasure of turning visual material into a tactile, inspectable interface. The sample illustration is fictional and drawn in the browser; no personal context or image assets are included.

## How to open
Open `index.html` directly in a modern browser, including offline from `file://`. No account, server, package installation, or network connection is needed. Imported images remain in this browser and are not uploaded. Large images are resized for analysis; the original file is untouched.

## Controls
Use **Open an image** to choose a local picture or **Load sample** to reset. Change **Color groups** to recompute the distribution. Tap/click the picture to inspect a pixel; focus the picture and use arrow keys to step pixel by pixel. **Copy** copies a color code where clipboard permission allows it. **Download CSS palette** saves `color-census.css` with area-ranked variables.

## Why it was built
Sometimes a picture feels like it has a dominant color that its obvious highlights conceal. This shows how much space each color actually claims, and turns that impression into useful CSS without leaving the device.

## Format choice
- **Lane:** `data_visualization`
- **Mechanic:** local image import → deterministic median-cut sampled-pixel grouping → area-proportional color bars, keyboard/touch pixel probing, and CSS export.

## Explicit bans avoided
No field-guide/zine/atlas framing, choose-your-own or branching story, signal/cartographer/constellation routing, launch/readiness simulator, scorecard/rubric meter, abstract agent preflight, or generic poetic generator. This is a real local image exploration tool, not a narrative or a graded checklist.
