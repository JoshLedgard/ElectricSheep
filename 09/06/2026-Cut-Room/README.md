# Cut Room

## What it is

Cut Room is a private, offline editorial instrument for making prose sharper by subtraction. Paste an email, memo, post, or paragraph; it separates the draft into sentence strips. Tap strips to move them onto or off the cutting floor while the revised draft and word reduction update live. Copy the result when it reads better—not merely when a number turns green.

It is intentionally non-AI: fast, predictable, and useful for text that should never leave the browser tab.

## Privacy-safe inspiration

Inspired by a generic theme from recent work: useful interfaces can make judgment more tactile without trying to replace it. No private conversations, names, or project details are included.

## How to open

Open `index.html` in any modern browser. No server, package installation, account, external asset, or network connection is required.

## Controls

1. Paste a draft or choose **Use example**.
2. Set a cut target, then choose **Enter the cut room**. `Command/Ctrl + Enter` also works from the editor.
3. Tap, click, or keyboard-activate any sentence strip to cut it; activate it again to restore it.
4. Watch the revised draft update live and choose **Copy draft** when finished.
5. Choose **New draft** to return to the editor without reloading.

All controls are ordinary keyboard-accessible HTML elements, focus is moved into the cutting board on entry, and status messages are announced through a live region.

## Why it was built

As a small dreamed tool that is useful on first contact: less a themed webpage, more a real editorial product prototype. It turns revision into a concrete act while keeping authorship and judgment with the writer.

## Format choice

- **Lane:** `writing_or_decision_aid`
- **Mechanic:** `sentence-strip subtraction with live reconstructed draft`

This deliberately differs from the recent timed pull-and-release physics game mechanic discovered during independent review.

## Explicit bans avoided

- No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing.
- No choose-your-own, branching story, microquest, or multiple-ending structure.
- No signal routing, cartography, constellations, or node/path connection metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard or rubric meter; the reduction target is an optional editing constraint, not a quality grade.
- No abstract AI-agent context or preflight tool.
- No generic or poetic generator.
- No family, travel, baseball, home, or local utility.

## Privacy

Draft text is processed only in page memory. Cut Room has no network requests, analytics, storage, external dependencies, or data collection. The included example is fictional and generic.

## Technical notes

The build is one responsive HTML file with inline CSS and JavaScript. It uses semantic buttons and labels, 44px-or-larger interactive controls, live status announcements, visible focus treatment, a 12,000-character input bound, abbreviation/decimal-aware sentence splitting, verified clipboard fallback, reduced-motion handling, and layouts designed not to overflow a 390px viewport.
