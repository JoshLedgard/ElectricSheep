# Screenshot Tailor — A Local-Only Visual Explainer

## What it is
Screenshot Tailor is a small, believable screenshot-finishing app that runs entirely in one browser tab. Start with its synthetic demo—or import, paste, or drop your own image—then crop and position it, add a focus spotlight, paint truly opaque redaction blocks, place numbered callouts with short captions, choose a presentation frame, and export the finished composition as a real PNG.

The demo is ready immediately, so the full annotate → explain → export loop takes only a few minutes. It is a direct-manipulation workbench, not an image generator or an online service.

## Privacy-safe inspiration
The generic inspiration was an interest in polishing product interfaces and communicating visual changes clearly. That broad theme became a private screenshot workbench. It contains no references to real people, organizations, products, projects, domains, tickets, messages, conversations, or datasets.

Imported images remain only in the currently open browser tab. There are no network requests, uploads, analytics, accounts, external assets, or browser storage. Exported redactions are painted into the PNG as solid opaque pixels rather than being left as removable HTML overlays. As with any redaction workflow, inspect the exported image before sharing it.

## How to open
Open `index.html` in any modern browser. It works directly from `file://`; no server, install, package, build step, or internet connection is required.

## Controls
- **Start tailoring** dismisses the short first-run explanation and reveals the built-in synthetic demo.
- **Import image** opens a local image picker. On supporting desktop browsers, you can also paste an image or drop one onto the canvas.
- **Move** selects the neutral interaction mode; use the crop-and-fit controls to zoom and pan precisely.
- **Spotlight** lets you tap the point that should stay bright while the rest of the image dims. Adjust its radius and dim strength below.
- **Redact** lets you drag an opaque rectangle over an area. Pick among four solid redaction colors.
- **Callout** drops a numbered marker. Type a concise caption for the selected marker.
- **Fit whole / Fill frame**, **Zoom**, **Pan X**, and **Pan Y** control the source-image crop.
- Presentation controls switch the surrounding background and frame treatment.
- **Remove last** undoes the most recently added annotation; **Clear spotlight** removes only the spotlight; **Reset demo** restores the built-in example.
- **Export composed PNG** downloads a 1600×1200 image with the crop, frame, spotlight, opaque redactions, callouts, and captions baked in.

## Why it was built
Screenshots often need one more pass before they communicate well: remove distraction, protect a private detail, point at the important control, and give the viewer a numbered reading order. Screenshot Tailor explores how much of that useful workflow can fit into a polished, private, self-contained browser artifact.

## Format choice
- **Lane:** `practical_micro_tool` — presented as a real-feeling product prototype / fake app.
- **Mechanic:** direct-manipulation canvas workbench: import or use a synthetic screenshot, crop and frame it, place a spotlight, drag opaque redactions, add numbered captioned callouts, and export a composed PNG.

This lane and mechanic are structurally different from the previous three surprises’ agent-memory darkroom, four-frame rotoscope, and gesture-visualization interactions.

## Explicit bans avoided
No field guide, zine, atlas, almanac, codex, or bestiary framing; no choose-your-own adventure, branching story, microquest, or multiple endings; no signal-routing, cartography, constellation, or path-connection metaphor; no launch, readiness, shipping, or preflight simulator; no scorecard, rubric, grade, or meter; no abstract AI-agent context debugger; and no generic prose or art generator.
