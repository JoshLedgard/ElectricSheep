# Cadence Press

## What it is

Cadence Press is a private, in-browser writing instrument for turning a dense memo or paragraph into editable sentence strips. It renders a live rhythm print from sentence length and punctuation, lets you reorder and reshape the prose, tag each sentence by its job, and export the revised text.

It is not a grader: the margin notes are plain-language structural prompts, with no score, rubric, or AI-generated judgment.

## Privacy-safe inspiration

Inspired by the general challenge of turning dense operational and product thinking into crisp, readable communication. The included sample is fictional and generic. No personal context or private conversation appears in the artifact.

## How to open

Open `index.html` in any modern browser. It is one self-contained file and needs no server, package installation, account, or internet connection.

## Controls

1. Type or paste text into the composing area, then choose **Set in strips**; or choose **Load sample memo**.
2. Tap a sentence strip to select and edit it.
3. Use the strip controls to move, split, join, delete, or tag a sentence as headline, evidence, decision, or plain text.
4. Tap bars in the rhythm print to jump to the matching strip.
5. Review the non-numeric margin notes, then copy clean text, copy a tagged outline, or save a `.txt` file.
6. **Clear table** resets the workspace; **Forget saved draft** removes the browser-local draft.

## Why it was built

To explore a more tactile way to revise prose: sentences behave like physical type, while the live print makes cadence visible without pretending that good writing can be reduced to a grade. It is a small, real-feeling product prototype rather than a themed page.

## Format choice

- **Lane:** `writing_or_decision_aid`
- **Mechanic:** `direct-manipulation sentence strips with live rhythm visualization`

## Explicit bans avoided

- No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing.
- No choose-your-own, branching adventure, microquest, or multiple-ending story mechanic.
- No signal, cartographer, constellation, routing, or path-connection metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard or rubric meter.
- No abstract AI-agent context, preflight, prism, or debugger.
- No poetic generator.
- No family, travel, baseball, home, Seattle, or local utility.

## Privacy and technical notes

- All analysis and editing happen locally in the browser.
- There are no external APIs, network requests, analytics, trackers, external fonts, or CDN assets.
- Draft persistence uses browser `localStorage` and is explicitly described in the interface; the draft can be forgotten at any time.
- The interface is mobile-first, has touch-sized controls, prevents horizontal overflow, and honors reduced-motion preferences.
