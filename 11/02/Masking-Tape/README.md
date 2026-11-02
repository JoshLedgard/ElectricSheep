# Masking Tape

Daily Surprise · November 2, 2026

## What it is
An offline screenshot redactor. Import a local picture, draw opaque rectangles over anything you don't want to share, refine a selected rectangle with percentage coordinates, then download a flattened PNG. A made-up interface is loaded as a safe sample. Redactions replace pixels in the exported image; they are not editable layers in the PNG. Inspect the downloaded file before sharing it.

## Privacy-safe inspiration
Inspired by the broad need for credible product screenshots that can be shared without exposing private material. The sample is entirely fictional and contains no personal or business information.

## How to open
Open `index.html` directly in a current browser, including `file://` offline. No account, server, package, or network is needed. Imported pictures stay in the tab. Files over 15 MB are refused; images above 1600 pixels on the longest edge are scaled down in the editor and export. Your original file is untouched.

## Controls
- Drag a finger, mouse, or stylus on the image to draw a solid cover. Tap an existing cover to select it.
- Adjust the selected cover with Left, Top, Width, and Height percentages (0.1% increments help on narrow screens). Switch **Draw over a cover** on to start an overlapping block on top of one already drawn; switch it off to select again. Use **Undo** to reverse the last cover edit, **Remove selected**, or **Clear all** (with confirmation).
- **Open image** replaces the sample after confirmation if there are edits. **Restore sample** returns to the fictional practice image.
- **Download flattened PNG** draws the base image plus opaque dark blocks into one new PNG. The dotted editor selection is not exported. Check that every sensitive detail is fully covered before sharing.

## Why it was built
A tiny, genuinely useful screenshot workbench instead of another abstract status meter. It makes the privacy-safe version of a screenshot available in a few taps, without uploading the original.

## Format choice
- **Lane:** `practical_micro_tool`.
- **Mechanic:** local image import, drag-to-cover redaction rectangles, numeric geometry adjustments, and destructive-pixel flattened PNG export. Not freehand chemical painting, cohort-grid editing, or audio trimming.

## Explicit bans avoided
No field-guide/zine/atlas/codex framing, choose-your-own or branching story, signal-routing/cartographer/constellation metaphor, launch/readiness/shipping simulator, scorecard/rubric meter, abstract AI-agent preflight/context tool, generic generator, or family/travel/baseball/local utility.
