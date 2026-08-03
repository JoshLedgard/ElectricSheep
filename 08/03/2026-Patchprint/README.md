# Patchprint — A Diff Textile Observatory

*Daily Surprise · 2026-08-03*

## What it is

Patchprint is a self-contained developer instrument that turns an ordinary unified diff into an inspectable woven textile. Additions become green weft, removals become red weft, unchanged context becomes neutral thread, line length controls stitch length, and small gold knots reveal meaningful whitespace. Filter the cloth by file, hide context, tap any thread to see its exact source line, and export the current fabric as a real SVG.

A harmless fictional two-file patch is loaded on opening, so the paste → weave → inspect → export loop works immediately. Parsing, rendering, filtering, and export are deterministic and happen entirely inside the open browser tab.

## Privacy-safe inspiration

The generic inspiration was the craft of coordinating software changes across several work surfaces and wanting to understand a patch's overall shape before reading every line. That broad developer-workflow theme became a local textile-like visualization. Patchprint contains no real people, organizations, repositories, conversations, messages, credentials, or private project data.

Custom text stays only in the open tab. There are no accounts, uploads, analytics, external assets, saved browser data, packages, network requests, or server.

## How to open

Open `index.html` in any modern browser. No install, account, server, or internet connection is required.

## Controls

- **Unified diff:** Paste a standard unified diff, then press **Weave patch**.
- **Restore sample:** Reload the built-in fictional patch.
- **File chips:** Show all files or isolate one file's threads.
- **Context:** Include or hide unchanged lines.
- **Whitespace:** Show or hide gold knots for tabs, trailing space, indentation, or repeated spaces.
- **Thread rows:** Tap or keyboard-activate a row to inspect its exact source line and hunk.
- **Export SVG:** Download the currently filtered cloth as a standalone vector image.

## Why it was built

Diffs are precise but visually flat. Patchprint explores whether material texture can make the character of a change legible at a glance without pretending to judge its quality. It is a believable little dreamed tool: useful enough for a real patch, tactile enough to invite exploration, and private by construction.

## Format choice

- **Lane:** `data_visualization` — presented as a polished future-artifact and practical local developer tool.
- **Mechanic:** paste or load a unified diff → deterministically weave additions, removals, context, line length, and whitespace into a textile visualization → filter by file → inspect exact source threads → export real SVG. This interaction differs from the last three surprises' timed recall painting, linked kinetic balancing, and one-thumb form rehearsal.

## Explicit bans avoided

No field-guide, atlas, almanac, codex, bestiary, or zine framing; no choose-your-own, branching adventure, microquest, or multiple endings; no signal-routing, cartographer, constellation, path-connection, launch/readiness/shipping, scorecard/rubric, or abstract AI-agent preflight mechanic; and no generic prose or art generator. Patchprint is a direct, local transformation of user-supplied structured text into an inspectable visualization.

## Privacy check

The bundled sample is fictional and contains no real names, emails, phone numbers, addresses, financial data, organizations, credentials, projects, or conversation excerpts. The app performs no network or persistence operation. User-pasted content remains in memory only until the tab closes or is refreshed.
