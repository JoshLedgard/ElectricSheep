# Tabquake

A one-button browser-physics game about the entirely reasonable decision to open one more tab. Time each drop, preserve the overlap, and build an increasingly improbable stack before three misses end the session.

## What it is

A complete, self-contained HTML5 stacking game. Tabs sweep across a miniature browser window; dropping one keeps only the part overlapping the stack beneath it. Perfect drops build a streak, narrow tabs accelerate the pressure, and the best run stays locally on the device.

## Privacy-safe inspiration

Recent work carried a broad theme of many operational threads and the value of bounded focus. Tabquake turns that generic feeling into a physical joke without using or exposing any personal, project, or conversation details.

## How to open

Open `index.html` in any modern browser. No server, install, account, network connection, or external asset is required.

## Controls

- Tap **Open one more tab** to begin.
- Tap the game board or **Drop tab** to place the moving tab.
- Press **Space** as a keyboard alternative.
- Use **↻** to restart and **♪** to toggle synthesized sound.
- Three complete misses end a run. The local best is stored only in browser `localStorage`.

## Why it was built

To make a tiny, polished game that feels structurally unlike recent decision aids and data visualizations: one obvious action, increasingly tense timing, immediate physical consequences, and a satisfying two-minute arc.

## Format choice

- **Lane:** `game_or_puzzle`
- **Mechanic:** `one-button timing and overlap-stacking physics`

The lane appeared at the oldest edge of the last-three window, but it was selected because the other recommended lanes were more recent or on a weekly cooldown. Its arcade stacking mechanic is deliberately different from the prior future-interface/reverse-CAPTCHA interaction.

## Explicit bans avoided

- No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing.
- No choose-your-own, branching story, microquest, or multiple-ending mechanic.
- No signal, routing, cartographer, constellation, or connect-the-nodes metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard, rubric meter, or grading interface.
- No AI-agent preflight, context debugger, or generic generator.
- No family, travel, baseball, home, Seattle, or local utility framing.

## Privacy and accessibility

The artifact has no analytics, trackers, network requests, personal data, or external dependencies. Sample tab labels are fictional and generic. Controls meet touch-size targets, gameplay works with touch/click/keyboard, status changes have an ARIA live region, and reduced-motion preferences disable CSS transitions.
