# Cut Room

## What it is

Cut Room is a tactile, offline redline editor for tightening short drafts. Paste or type a draft, set how lean you want it, and tap visibly marked phrases to cut or replace them. Every edit is reversible, and the clean result can be copied in one tap.

The suggestions use a small, transparent set of local writing heuristics. There is no AI service, account, upload, analytics, or network dependency.

## Privacy-safe inspiration

The generic inspiration was the recurring challenge of turning busy operational prose into crisp, useful communication. No private conversation or personal detail is represented in the artifact.

## How to open

Open `index.html` in any modern browser. It is one self-contained file and needs no server, package install, internet connection, external font, or asset.

## Controls

1. Type or paste a short draft in **Bring a draft**.
2. Press **Mark the cut table**.
3. Move the **% leaner** dial to mark enough candidate phrases to approach a target length.
4. Tap a marked phrase to apply or restore that individual edit.
5. Use **Apply marked cuts**, **Undo**, **Redo**, or **Restore draft** as needed.
6. Press **Copy clean draft** to copy the tightened text without redline marks.

## Why it was built

This is a small prototype of a writing instrument that makes editorial judgment tangible. It offers suggestions without hiding the original language or pretending an opaque service made the decision. The writer remains in control of every cut.

## Format choice

- **Lane:** `writing_or_decision_aid` — presented as a polished future-app prototype.
- **Mechanic:** Tactile direct-manipulation redline editing: a target-length dial marks candidates; tapping phrases cuts or restores them; undo/redo preserves reversibility.

## Explicit bans avoided

- No field guide, atlas, almanac, codex, zine, or pocket-guide framing.
- No choose-your-own, branching story, microquest, or multiple-ending mechanic.
- No signal, routing, cartographer, constellation, or path-connection metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard or rubric meter.
- No abstract AI-agent preflight or context debugger.
- No family, travel, baseball, home, or local utility.
- Not a generic poetic generator.

## Privacy and implementation notes

- All text processing stays in the current browser tab.
- The page makes no network requests and stores nothing.
- Included sample text is fictional and generic.
- No names, emails, phone numbers, addresses, financial information, private quotes, or sensitive details are included.
- Touch targets are at least 44px for primary controls, the layout collapses cleanly for a 390px viewport, and reduced-motion preferences are respected.
