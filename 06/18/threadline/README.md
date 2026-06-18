# Threadline

A tiny tactile timeline editor for thinking. You place a few colored beads on a
horizontal thread and arrange them into a clear line of reasoning — **Question →
Bet → Proof → Risk → Next Move** — then read your idea back as a short, plain
narrative you can copy into whatever comes next.

It is a writing / decision aid, not a tracker. It never scores, grades, or tells
you whether you're "ready." It just helps loose thoughts become a legible thread.

## Privacy-safe inspiration

The generic feeling of having scattered notes about an idea and wanting to lay
them out in order — what am I asking, what's my bet, what would prove it, what's
the risk, what do I do next — so the path forward reads clearly. No specific
people, projects, numbers, or quotes; just the shape of turning a mess into a
thread.

## How to open

Open `index.html` in any modern browser (desktop or mobile). No install, no
build step, no network connection. Everything runs locally and your thread is
saved on-device only.

## Controls

- **Add a bead** — tap one of the five colored bead buttons (Question, Bet,
  Proof, Risk, Next Move) to drop it onto the thread.
- **Edit a bead** — tap any bead on the thread to open its editor, then type its
  line. A short prompt suggests what that bead is for.
- **Reorder** — use ◀ Earlier / Later ▶ in the editor to slide a bead along the
  thread.
- **Remove** — the Remove button in the editor deletes the selected bead.
- **Done** — closes the editor and deselects.
- **Copy summary** — copies a clean text version (ordered beads + narrative) to
  your clipboard.
- **Reset** — clears the whole thread to start fresh (asks first).
- **Save** — automatic; your thread persists in `localStorage` between visits.

Touch targets are at least 44px, the layout fits a 390px phone with no
horizontal scroll, and all controls work with tap/click plus a focusable,
keyboard-friendly text editor.

## Why it was built

A daily creative-coding surprise: a small, self-contained, genuinely useful
artifact you can enjoy in 2–3 minutes. Threadline takes the everyday act of
untangling scattered thoughts and makes it tactile and satisfying — beads on a
string, arranged until the idea reads as one clean line.

## Format choice

- **Lane:** writing / decision aid
- **Mechanic:** tiny timeline editor — a tactile bead-on-thread arranger. You
  place and edit a few colored beads on a horizontal thread to map an idea as
  Question, Bet, Proof, Risk, and Next Move, and it renders a compact narrative
  from the arrangement. It deliberately does **not** compute readiness, scores,
  rubrics, or launch status.

## Avoided recent patterns

To stay fresh, this intentionally avoids recently used patterns:

- launch / readiness / shipping simulators
- generic scorecard / rubric / meter UIs
- abstract AI-agent context / preflight tools
- map / visual-explorer mechanics
- swipe-through zines

Threadline is a hands-on arranging tool with a written output — a different
shape from those.
