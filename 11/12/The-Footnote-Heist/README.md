# The Footnote Heist

**Daily Surprise · November 12, 2026**

## What it is

The Footnote Heist is a small evidence-detective game. Each of eight made-up case files gives you two or three short **receipts** (the evidence) and an answer written to look like something an AI produced, split into three or four tappable sentences with neat little footnotes. In every answer, exactly one sentence has a footnote it didn't earn. It either says something no receipt supports or it contradicts one. Find it, stamp it, and see why each of the other sentences checks out.

Some cases come down to reading carefully (a service alert that overrides a timetable). Others make you combine two receipts (every tour passes through a gallery that small children can't enter), and some contain a decoy that looks suspicious but is actually supported (21 + 14 = 35 days).

## Inspiration (privacy-safe)

The idea comes from a general curiosity about when an AI answer can be trusted, and from the habit of checking a confident sentence against the source it cites. A tidy footnote doesn't prove anything, so the game turns that habit into a puzzle. No personal details, conversations or real-world data were used.

## How to open

Double-click `index.html`, or open it in any modern browser. It's one self-contained file with inline CSS and JS. It needs no server, network or dependencies, and it stores nothing.

## Controls

- **Touch / mouse:** tap a sentence to select it, then tap **Stamp it unsupported**. Tap **Next case** to continue.
- **Keyboard:** `1`–`4` select a sentence, `Enter` stamps it, `H` uses a hint, `N` goes to the next case. `↑`/`↓` move between sentences, and `Tab`/`Space` also work everywhere.
- **Hint (−50):** clears one sentence you know is supported.
- **Scoring:** 100 per catch, +25 for each extra case in a streak, −50 if you used a hint. Progress pips show hits and misses.
- **Shuffle & replay:** at the end, replay all cases in a new random order.

All controls are real buttons at least 44px tall, and nothing depends on hover. The layout fits a 390px-wide phone with no sideways scrolling.

## Why it was built

Checking claims against sources is a skill that's worth practicing, and doing it in short rounds with a clear answer is more fun than a lecture. Every case was written by hand so that the verdict follows from the receipts alone. There's exactly one culprit per case, and the reveal says which receipt backs each sentence (or why none does). All topics, places and names are fictional. Nothing here claims to be a real-world fact.

## Format choice

- **Lane:** `game_or_puzzle`
- **Mechanic:** tap-the-unsupported-claim evidence detective, with a turn-based select-then-confirm deduction. It is deliberately *not* a timing or arcade game: there's no clock, and you can't lose by being slow.

## Explicit bans avoided

This piece deliberately avoids the formats used in recent entries:

- **Not a field guide or zine.** It's an interactive puzzle with scored verdicts, not a browsable reference or a printed-style booklet.
- **Not choose-your-own branching.** Cases run in a straight line, and there are no story forks.
- **Not signal or cartographer routing.** There are no maps, paths, networks or routing puzzles.
- **Not a launch or readiness simulator.** There are no countdowns, go/no-go checks or system-readiness theater.
- **Not a scorecard or rubric meter.** You don't rate anything against criteria. Each case has a single right answer, and the score is just a running game tally.
- **Not an abstract agent preflight.** There are no agent checklists, tool-permission panels or pre-run audits. Just concrete fictional receipts and sentences.
