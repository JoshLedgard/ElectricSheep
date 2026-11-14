# Revision Lens

**Daily Surprise · November 14, 2026**

## What it is
A small, offline draft-comparison tool. Paste an earlier and a revised version of any text and Revision Lens highlights removed and inserted words inline where feasible (struck through and underlined). Step through each change, switch between Inline / Before / After views, fold long unchanged passages, and copy a concise plain-text change summary ("3. Line 5: replaced “five” → “ten”").

Under the hood it runs a real Myers O(ND) shortest-edit diff over word, punctuation, and whitespace tokens — not a paragraph-level compare — with a boundary-shift cleanup so changes read naturally. Very different large drafts fall back to line-by-line matching and refine changed blocks word by word where possible; exceptionally large changed blocks are shown as whole-block replacements.

## Inspiration (privacy-safe)
A general curiosity about making edits legible: when a paragraph has been revised, what actually moved? No personal documents, conversations, or private data were used; the three sample pairs (a short story opening, fictional app release notes, a museum label for an invented object) are synthetic.

## How to open
Open `index.html` in any modern browser, including offline straight from this folder. No install, account, server, or network is needed. Nothing you paste is uploaded or saved: no network requests, no storage, and a Content-Security-Policy blocks outbound connections.

## Controls
- **Draft A / Draft B**: editable text areas; the comparison updates live as you type (paused above 150,000 characters, where you press **Compare**).
- **Load a sample…**: three editable synthetic sample pairs. **⇄ Swap** flips before/after. **Clear** empties both, with **Undo**.
- **Ignore case** / **Ignore spacing**: treat capitalization or runs of spaces as equal. Line and paragraph breaks still count.
- **◀ Prev / Next ▶**: step through changes (wraps around). You can also click a highlighted change or any row in the **Change list**.
- **Inline / Before / After**: view modes. ‸ marks where text was removed or added in the one-sided views.
- **Fold unchanged**: collapses long unchanged stretches to “⋯ N unchanged words · show ⋯”.
- **Copy summary**: copies the change summary to the clipboard. The same text is shown in **Summary preview** for manual copying.
- Keyboard: `N`/`J` next, `P`/`K` previous, `1` `2` `3` switch view, `Ctrl`/`⌘`+`Enter` compare from inside a draft.
- States: empty, one draft missing, no differences, large input (live updating paused), coarse fallback notice, and a hard limit of 1,000,000 characters per side.

## Why it was built
Revision history is usually shown as all-or-nothing: two blobs, or one paragraph highlighted. Seeing word-level edits in place, and being able to walk through them one at a time, makes it much easier to review a rewrite, explain what changed, or check that an edit didn't drop something by accident. The aim was a tool you could actually keep using after the first two minutes.

## Format choice
- **Lane:** `practical_micro_tool`
- **Mechanic:** paste two text drafts → word-level inline insertion/deletion diff → navigate changes (buttons, keys, list, click) → copy a concise change summary.

## Explicit bans avoided
Not a field guide, zine, or atlas; not a branching adventure; not a routing or constellation puzzle; not a launch/readiness simulator; not a rubric or scorecard; not an AI preflight/context tool; not a generic generator; not a family, travel, baseball, or local utility. Different lane and mechanic from the recent histogram-with-sliders visualization and the tap-and-confirm evidence detective. No real names, emails, addresses, financial amounts, messages, or personal details are included.
