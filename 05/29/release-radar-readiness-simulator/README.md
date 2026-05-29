# Release Radar — Tiny Launch Readiness Simulator

## What it is
A pocket simulator that turns the messy judgment behind a release into a
quick, playable readout. You get a small pool of attention chips and five
signals — Launch, Customers, Risk, Docs, Learning — and you decide where
to spend. Hit **Run readiness scan** and a tiny radar sweeps, lights up
blips, and hands back a named **Flight Path**, a 0–100 readiness score,
and one concrete next move.

## Format choice
Product/strategy experiment + tiny puzzle/simulator. Distinct from
recent days: not a triage/rubric card board, not an atlas/cartography
toy, not a soundless ritual generator. This one is an *interactive
allocation puzzle* with a deterministic readout.

## Privacy-safe inspiration
Reliable workflows, quick audits, deployment confidence, and the idea of
turning a launch-readiness gut check into a small playable prototype.
No real names, channels, projects, or operational specifics anywhere in
the surprise — just abstract signals and verdicts.

## How to open
Open `index.html` in any modern browser. Phone, tablet, laptop —
everything is mobile-first and self-contained. No build, no install, no
network.

## Controls
- Tap **+** / **−** next to each signal to spend or recall an attention
  chip. Each signal tops out at 3 chips; the pool tops out at 12.
- The signal text and tier label update live as you spend.
- Tap **Run readiness scan** to fire the radar. After a short sweep
  you'll see the verdict, gauge, channel readout, and next move.
- Tap **↺** to clear and start over.

## Possible flight paths
A dozen named verdicts, including *Green Light Glide*, *Reckless
Liftoff*, *Holding Pattern*, *Hot Launch*, *Audit Loop*, *Lab Mode*,
*Crowd Pleaser Cruise*, *Diagnostics Spin*, *Stealth Cruise*, and the
zero-chip *Dark Cabin*. Each comes with one concrete suggestion for the
next chip to move.

## Why it was built
The recent context around reliable workflows, code review, and
shipping checks made the "am I actually ready to ship?" feeling feel
like something worth turning into a tiny tool. The simulator is
small enough to play through in 2–3 minutes but real enough that the
allocation and verdict map onto how a real shipping decision tends to
go: you can't fund everything, the unfunded slots are where the
surprises live, and the named outcome reframes the gut check as a
specific next move.

## Tech
Single self-contained `index.html`. Vanilla HTML/CSS/JS, system font
stack with a serif/mono blend, SVG radar with a CSS-rotated sweep
gradient, deterministic verdict + score logic. No external assets,
fonts, scripts, or network calls.
