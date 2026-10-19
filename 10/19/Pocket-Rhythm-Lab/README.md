# Pocket Rhythm Lab

**Daily Surprise · October 19, 2026**

## What it is

A small, polished pocket drum machine. Four synthesized voices (kick, snare, hat, bell) run across a 16-step timeline. Tap any cell to place or remove a hit, hear the loop immediately, shape it with tempo and swing, and export the result as a real WAV file rendered entirely inside the page.

Nothing is sampled or downloaded. Every sound is built on the fly with the Web Audio API: a pitch-dropping sine for the kick, filtered noise plus a short tone for the snare, bright filtered noise for the hat, and a four-partial additive bell that picks a pentatonic note based on which step it lands on.

## Privacy-safe inspiration

The idea came from a general interest in tiny interfaces made for exactly one job. A drum machine is a classic example: a grid, a few knobs, a play button. The goal was to make that grid feel genuinely good in the hand on a phone, with no sign-in, no assets, and no network. All preset rhythms are fictional, invented for this page.

## How to open

Open `index.html` in any modern browser. It works offline from the file system. Sound starts only after you press Play or tap a cell, because browsers require a user gesture before audio can begin.

## Controls

- **Play / Pause** — starts and stops the loop. The large button pulses on each beat.
- **Presets** — three distinct rhythms: *Four Floor* (122 BPM, straight), *Dusty Shuffle* (90 BPM, heavy swing), *Bell Garden* (72 BPM, sparse and melodic).
- **Randomize** — writes a musically sensible sparse groove: kick on the downbeat, snare on the backbeat, one of several hat templates, two to four bell hits on off-beats.
- **Clear** — empties all four tracks.
- **Tempo** — 60 to 180 BPM.
- **Swing** — 0 to 60 percent; delays the odd sixteenths, with 60 percent close to a triplet feel.
- **Cells** — tap to toggle. Tapping a cell on while paused previews that hit. Cells on beats 1, 5, 9, 13 are shaded for orientation.
- **Mute** — per-voice mute buttons; muted voices are also left out of exports.
- **Beat cursor and playhead** — a dot strip above the grid and a highlighted cell in every track show the current step. A beat (1–4) and step (1–16) readout sits above the grid. Pause silences scheduled hits and tails.
- **Export WAV** — choose 1, 2, 4, or 8 bars, then export. The pattern is rendered through an `OfflineAudioContext` to 16-bit stereo PCM at 44.1 kHz, encoded to WAV in JavaScript, and downloaded as a local file. Errors (unsupported browser, empty pattern) appear in the status line.
- **Keyboard** — Tab to a cell, then arrow keys move around the grid, Space or Enter toggles.

Your pattern, tempo, swing, and mutes are saved to this browser's local storage so the lab reopens where you left it.

## Why it was built

Most browser rhythm toys are either generic generators or demos with placeholder controls. This one tries to be an actual instrument: tight scheduling with a lookahead clock, swing that feels right, tactile cells sized for thumbs, visible transport state, screen-reader labels on every control, and a working export path so a groove can leave the page as audio.

## Format choice

- **Lane:** `calm_creative_ritual`
- **Mechanic:** four-voice tap-to-program rhythm sequencer with live synth playback and WAV export

## Accessibility and mobile notes

- Every cell, mute, preset, and transport button is a real labeled `<button>` with `aria-pressed` state.
- Touch targets are at least 44 px. At 390 px wide, each voice shows four steps per line across four lines; from 430 px it shows eight per line, and from 900 px all 16 on one line. The full timeline stays visible without horizontal scrolling.
- Status messages use a polite live region.
- Reduced-motion users get no pulse or hit animations; the playhead still moves because it conveys state.
- Text contrast stays above WCAG AA on the dark panels.

## Explicit bans avoided

- No field guide, zine, atlas, almanac, or codex framing.
- No branching or choose-your-own structure; no routing, constellation, or signal metaphor.
- No launch, readiness, or shipping simulator; no scorecard, rubric meter, or abstract AI preflight.
- Not a generic generator: randomize follows musical rules and the main interaction is hand-programming cells.
- Unlike recent surprises (an observation-date scrubber, a teleprompter, visual memory tiles), this is a rhythmic audio instrument.
- No real names, emails, addresses, dollar amounts, or private conversation details. No trackers, fonts, scripts, or assets fetched from anywhere.
