# Redaction Desk

Daily Surprise · October 21, 2026

## What it is
A tiny offline tool for blacking out parts of a picture before you share it. Open a screenshot, scan, or photo from your device, drag solid black rectangles over anything you want gone, undo if you overshoot, then download a new flattened PNG. The boxes are baked into the pixels as opaque black, not stored as a layer, and the output keeps the original width and height. The original file on your device is never modified, and nothing is uploaded anywhere. A demo image, drawn on the page from plain shapes, loads on open so you can try it without using your own files.

## Privacy-safe inspiration
Inspired by the ordinary moment of wanting to share a screenshot of visual work and noticing a notification, an open tab, or a reflection that is nobody else's business. No real screenshots, names, messages, or personal data were used; the demo image is generated procedurally from rectangles, circles, and gradients and contains no text or real content.

## How to open
Open `index.html` in a modern browser, including straight from the file system or iCloud. It needs no server, install, login, or internet access. It works in airplane mode.

## Controls
- **Open image** opens the file picker. You can also drop an image file anywhere on the page, or paste one with Ctrl/Cmd + V.
- **Use demo image** regenerates the built-in demo picture.
- **Drag on the image** to draw a box. A dashed yellow outline shows the preview; lifting your finger or releasing the mouse commits it as solid black. Taps shorter than a few pixels are ignored.
- **Undo last box** removes the most recent box. Cmd/Ctrl + Z does the same. **Esc** cancels a box mid-drag.
- **Clear all** removes every box.
- **Download flattened PNG** is enabled once at least one box exists. It saves `<original name>-redacted.png` at the original pixel dimensions. Boxes are snapped outward to whole pixels so no partially covered edge pixel leaks through. EXIF orientation is honoured where the browser supports it (modern Chrome, Firefox, and Safari), and no camera metadata is carried into the PNG.
- Images over 16 megapixels or 8192 pixels on either side are rejected before canvas allocation to avoid unreliable browser exports; resize those first.
- All buttons are at least 44 px tall and the layout fits a 390 px wide screen with no horizontal scrolling. The canvas blocks page scrolling so touch drags are reliable; scroll from outside the sheet.

## Manual verification
1. Open the page with the network off. The demo, drawing, and download all still work.
2. In the browser's developer tools Network tab, open an image and download the result. No requests appear.
3. Open the downloaded PNG in any viewer. It should match the original width and height, and the boxes should be pure black with nothing visible underneath even at high brightness.
4. Search the page source for `fetch`, `XMLHttpRequest`, `http://`, or `https://`. None are present.
5. On a phone at 390 px width, confirm there is no sideways scrolling and that a one-finger drag on the image draws a box instead of scrolling the page.

## Why it was built
Blur and pixelation can sometimes be undone or guessed from context, and online redaction tools require uploading the very picture you are trying to protect. A single page that does the whole job locally, with an opaque flattened result, is the simplest safe answer.

## Format choice
- **Lane:** `practical_micro_tool`
- **Mechanic:** import a local image by file picker, drag-and-drop, or paste; paint solid opaque redaction rectangles directly on the canvas with pointer or touch, with a live preview; undo and clear; export a flattened PNG at the original pixel dimensions with black overlays burned in.

## Explicit bans avoided
No field guide, zine, atlas, almanac, or codex framing; no branching story; no routing, cartographer, or constellation metaphor; no launch, readiness, or shipping simulator; no rubric, scorecard, or meter; no agent preflight; no generic generator. It is also distinct from the recent numeric cohort experiment, drum sequencer, and timeline visualization.
