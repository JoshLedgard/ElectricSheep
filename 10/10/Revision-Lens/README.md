# Revision Lens

## What it is
A small offline tool for writers and editors. Paste two versions of a text, side by side, and Revision Lens shows a word-level visual diff: removed words are struck through in red, added words are underlined in green, and nearby edits are grouped into numbered changes. Each change has a clickable chip that jumps to and highlights that passage. A "loupe" card shows the change with its surrounding context, before and after. There is also a paragraph-by-paragraph overview and a plain-text changelog you can copy.

## Privacy-safe inspiration
Careful revision as hands-on inspection: holding two drafts under a magnifying glass and checking, one change at a time, exactly what moved. Both built-in sample draft pairs are invented: a short proposal for calmer software updates, and instructions for repotting a succulent.

## How to open
Open `index.html` directly in any modern browser. You don't need a server, an install, an account, or a network connection.

## Controls
- **Before / After** text boxes: paste or type the two versions. Live word and paragraph counts show under each label.
- **Compare**, or <kbd>Ctrl</kbd>/<kbd>⌘</kbd>+<kbd>Enter</kbd> inside a text box: runs the diff.
- **Load example**: fills both boxes with an invented draft pair and compares them. Press it again to switch between the two examples.
- **Swap ⇄**: exchanges Before and After, and compares again if results are showing.
- **Reset**: clears both boxes and the results.
- **‹ Prev / Next ›**, or <kbd>[</kbd> / <kbd>]</kbd> (also <kbd>p</kbd> / <kbd>n</kbd>) when the cursor isn't in a text box: steps through the changes. The bar stays pinned at the top while you scroll.
- **Inline / Side by side**: shows one merged view, or the two versions in separate columns (stacked on phones). A ‸ mark shows where text was added or removed on the other side.
- **Change chips**: numbered and colour-coded by type. Click one to scroll to its passage, highlight it, and open it in the loupe. You can filter the chips to All, Replaced, Added or Removed. Clicking a highlighted passage in the text also selects it.
- **Paragraph overview**: each revised paragraph is labelled unchanged, edited, rewritten or new, with its +/− word counts. Original paragraphs that were dropped completely are listed as removed. Click a row to jump to it.
- **Copy changelog**: copies the plain-text summary (totals, paragraph list, numbered changes). If the clipboard isn't available, it falls back to `execCommand`.

## Why it was built
Most diff tools work line by line and are made for code. Prose needs a word-level view with readable groupings, plus a summary you can paste into a note to a co-author. Everything is deterministic and literal. The counts and labels come straight from the diff, and the tool never claims to know what an edit *means*.

How it works: text is split into words (keeping contractions, hyphenated words and decimal numbers together), single punctuation marks, and paragraph breaks (blank lines). The two versions are compared with Myers' O((N+M)D) algorithm for the longest common subsequence, after first trimming the shared beginning and end. A small cleanup step then merges tiny coincidental matches (at most 3 tokens, never a paragraph break, and weighted so a word that was kept is never swallowed by punctuation edits) into the larger edits around them, so a rewritten sentence reads as one change. Differences in spacing and line wrapping are ignored. Capitalisation and punctuation count. For very different large texts the diff falls back to showing one block replacement, and says so.

## Format choice
- **Lane:** `writing_or_decision_aid`
- **Mechanic:** `paste two text versions → word-level LCS visual diff with grouped changes, clickable change chips that jump to and highlight the passage, context loupe, paragraph-level overview, and a copyable deterministic plain-text changelog`

This is deliberately different in structure from yesterday's Inkfold paper-pattern puzzle. It is a working text tool, not a game or a puzzle.

## Explicit bans avoided
No scores, rubric meters, readiness checks, or "quality" ratings: the numbers are literal word counts only. No branching story. No field guide, zine, atlas, almanac, or codex. No signal, routing, cartographer, or constellation metaphor. No poetic or generic generator. No AI or semantic claims. No family, travel, baseball, or local references. No ink-and-paper pattern puzzle.

## Privacy
All processing happens in the page's memory. There are no network requests (a strict Content-Security-Policy blocks them), no external fonts or assets, no analytics, and no localStorage or cookies. Pasted text disappears when you reset or close the tab. Pasted text is always HTML-escaped before display. The sample texts contain no real names, emails, money amounts, or private conversations.
