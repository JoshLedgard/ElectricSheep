# Caption Clinic

**Daily Surprise · November 25, 2026**

## What it is
An offline subtitle repair desk for SRT and WebVTT files. Bring in a file or paste cues; compare original and adjusted timing in a two-screen preview, shift or stretch an entire track, repair individual cues and download the result. A synthetic plant-repotting sample is included so you can try it immediately. The preview shows text timing, not video or audio synchronization.

## Inspiration (privacy-safe)
The general usefulness of a small, hands-on tool for repairing messy working material. The sample is invented and contains no private data or conversations.

## How to open
Open `index.html` directly in a modern browser on a phone or desktop. No server, account, install or network is needed. Imported subtitles stay in the browser page; there is no automatic upload or persistence. Download your repaired copy before closing the tab.

## Controls
- **Load synthetic sample**, choose a `.srt` or `.vtt` file, drop a file, or paste subtitle text and press **Read pasted text**.
- Scrub or play the before/after text preview; choose a cue in the list or timeline. Drag a repaired cue on the timeline or use its keyboard arrow keys to shift it (Shift+arrow for larger steps).
- Edit the selected cue's start, end and text; nudge, insert or delete cues. Times accept `00:01:02,500`, `1:02.5`, or seconds such as `62.5`.
- Use **Shift** for a whole-track offset in milliseconds, **Stretch** for a proportional timing adjustment around an anchor, or **Two-point sync** to align two known cue starts. Choose all cues or selected cue onward where supported. **Undo** and **Reset to imported** are available.
- Review warnings for empty, overlapping, inverted or out-of-order cues; optionally sort or trim overlaps. Download SRT or VTT. SRT renumbers cues and drops VTT positioning settings; VTT retains identifiers and settings. Blank cues are omitted. Export warns about remaining timing problems rather than silently fixing them.

## Why it was built
Subtitle drift often needs a quick, reversible correction rather than a full editing suite. This puts the correction and its consequences in the same view.

## Format choice
- **Lane:** `practical_micro_tool`
- **Mechanic:** direct subtitle timing repair with live before/after text preview, cue nudging, whole-track affine adjustment and real file export.

## Explicit bans avoided
No field-guide/zine/atlas/codex framing; no branching adventure; no signal, cartographer, constellation or routing metaphor; no launch/readiness simulator, scorecard, rubric meter, generic AI preflight or poetic generator. No family, travel, baseball or local utility framing.
