# Cue Light

## What it is
A small offline teleprompter for rehearsing a short talk or announcement. Paste words into the editor, set the reading pace and type size, then start the scroll. Use focus view to give the script more space or mirror it for a physical teleprompter rig.

## Privacy-safe inspiration
Inspired by the general need to turn a draft into something you can actually say aloud. The included sample is fictional and contains no personal context.

## How to open
Open `index.html` directly in a modern browser. No server, account, installation, or network connection is required.

## Controls
- Edit the script, or **Load demo** to restore the fictional sample. **Clear** removes it from the page.
- Adjust **Pace** and **Type size** with sliders. **Start/Pause**, **Restart**, and ±10% move through the script.
- **Mirror** flips the preview; **Focus view** enlarges it. Swipe vertically or use a mouse wheel inside the preview to reposition.
- Outside the editor: Space starts/pauses, left/right arrows jump, Home restarts.

## Why it was built
A tool for crossing the gap between copy on a screen and words spoken at a human pace, without an account or a tracking service.

## Format choice
- **Lane:** `practical_micro_tool`
- **Mechanic:** adjustable, touch-scrubbable teleprompter with mirror and focus modes; no diffing, grading, or branching.

## Explicit bans avoided
No field guide, atlas, zine, almanac, codex, branching adventure, signal-routing/cartography/constellation metaphor, launch/readiness/shipping simulator, scorecard/rubric meter, AI-agent preflight, poetic generator, or family/travel/baseball/local utility. Unlike recent copy-comparison tools, this is a rehearsal instrument rather than a before/after diff.

## Privacy check
The page has no network calls or external dependencies. It doesn't use local storage. Script text remains in the current browser tab and is not exported automatically. Demo text contains no personal details.

## Verification
Self-test is exposed as `window.__cueLightTest()` for text-injection and basic state checks. Functional and mobile checks are conducted separately before `READY` is written.
