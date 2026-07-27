# Feelwright — An Interaction Feedback Composer

*Daily Surprise · 2026-07-27*

## What it is

Feelwright is a tiny, self-contained instrument for composing how a control *feels* when it responds to a press.

You tap a rhythm on a large performance pad. Each tap becomes a beat, and how long you hold the tap becomes that beat's pulse strength. The rhythm lands on a horizontal sequencer where every beat is a card spaced by real elapsed time — so you can see the shape of what you played. Pick any beat and sculpt it: pulse strength, visual bloom, release time, and click tone (Tick, Thud, Glass, Edge, Hush). A fictional interface button previews the whole thing — visual dip, glow bloom, and synthesised click, in time.

Then it exports something you can actually use: a readable JSON recipe, a drop-in CSS keyframe pair (`@keyframes …-press` and `…-bloom`, with a `prefers-reduced-motion` escape hatch), and a dependency-free Web Audio + DOM function. Copy to clipboard, or download one file or all three.

It ships with a demo pattern already loaded — a soft double-tap followed by a bright confirm — so the entire loop is legible in the first five seconds.

Two to three minutes end to end. Everything is deterministic: the numbers come only from your taps and your sliders. Nothing is generated, predicted, or scored.

## Privacy-safe inspiration

A general, privacy-safe interest in how distinct elements can be paired so they read as one coherent, memorable experience. Feelwright applies that idea to interaction feedback: a movement, a glow, and a sound are three separate channels, and the tool is about making them agree with each other rather than compete. No personal context, plans, places, people, or conversations are referenced or embedded anywhere in the artifact.

## How to open

Open `index.html` in any modern browser — double-click it, or drag it onto a browser window. Works on phone and desktop. There is nothing to install, no build step, no server, and no network connection required. A single file with no external assets.

Best experienced on a touchscreen with the sound on.

## Controls

**01 Record**
- **Performance pad** — tap it to start recording; tap repeatedly to lay down beats. Hold each tap longer for a stronger beat. Works with touch, mouse, pen, and keyboard (Space/Enter while the pad is focused).
- Recording ends after two seconds of quiet, at twelve beats, or when you press **Stop**.
- **Tighten timing** — rounds every beat to the nearest 50 ms.
- **Load demo** — restores the built-in pattern and plays it.
- **Undo record** — swaps back to the pattern you had before the last recording.

**02 Sculpt**
- Tap a beat card to select and audition it.
- **Pulse strength** — how deep the press dips, and how loud the beat reads.
- **Visual bloom** — the glow that spreads out of the control after the dip.
- **Release** — how long the control takes to settle back to rest (60–420 ms).
- **Click tone** — Tick, Thud, Glass, Edge, or Hush.
- **−20 ms / +20 ms** — nudge the beat's position in time (clamped so beats can't cross).
- **Apply to all beats**, **Audition beat**, **Delete beat**.

**03 Preview**
- Tap the fictional **Mark complete** button, or press **Play feel**, to run the whole recipe.
- **Sound** toggle (on by default). **Haptics** toggle appears only when the browser reports `navigator.vibrate` support.

**04 Export**
- **Name** — used for filenames and generated CSS class names.
- **JSON / CSS / JS** tabs.
- **Copy**, **Download**, **All three**.

## Why it was built

Motion, glow, and sound in an interface are usually specified in three different places by three different people, and they end up disagreeing — the animation is snappy, the sound is soft, the glow lingers a beat too long. The only reliable way to notice that is to feel all three at once.

Feelwright compresses that into one screen. The pad captures rhythm the way you'd actually tap it rather than the way you'd type it into a config file, the sequencer makes the timing visible, and the preview puts all three channels on the same object at the same instant. The export exists so the result doesn't stay trapped in a demo — it comes out as real CSS and real JavaScript.

It's also a small argument that a design tool can be an *instrument* — something you perform into — rather than a form you fill out.

## Format choice

- **Lane:** `practical_micro_tool`, presented as a polished future-artifact / believable product-design app.
- **Mechanic:** Record a short rhythm by tapping a large performance pad → shape each beat on a tactile horizontal sequencer (pulse strength, visual bloom, release, click tone) → preview it live on a fictional interface button → export a useful, self-contained JSON / CSS / Web Audio recipe. A strong built-in demo makes the full interaction immediately understandable. Fully deterministic and local; no generation of any kind.

This differs from the three preceding surprises: it is not word-joint typesetting (startup typography tool), not timeline darkroom controls (AI-memory prototype), and not frame drawing (calm creative rotoscope). The input modality — timed performance capture — and the output artifact — an interaction-feedback recipe — are both new to the series.

## Explicit bans avoided

- No field guide, atlas, almanac, codex, zine, or pocket-guide framing.
- No choose-your-own, branching story, microquest, or multiple endings.
- No signal, cartographer, constellation, routing, or path-connection metaphor.
- No launch, readiness, or shipping simulator.
- No scorecard, rubric, meter, or grade — nothing here is evaluated or scored.
- No abstract AI-agent context, preflight, or debugger framing.
- No generic generator — every value comes from a direct human action.
- No family or travel planning, no baseball, no local utility.

## Privacy / technical notes

**Privacy**
- Zero network requests. No fetch, no XHR, no beacons, no analytics, no external fonts, images, or scripts. All CSS, JavaScript, and artwork are inline in the single HTML file.
- No `localStorage`, `sessionStorage`, cookies, or uploads. Your pattern and the recipe name live in page memory only and vanish when the tab closes — export first if you want to keep them.
- No real names, addresses, emails, phone numbers, amounts, organisations, products, accounts, plans, or quoted conversation. The only labels are harmless invented ones: `sample-press`, `sample surface`, `Mark complete`.

**Technical**
- Single file, no dependencies, no build step, no server.
- Mobile-first, readable at 390 px with no horizontal overflow. All interactive targets are at least 44 px tall. Nothing is hover-only.
- Pointer Events with touch, mouse, pen, and keyboard paths; `touch-action` set to avoid scroll/gesture conflicts on the pad and sliders.
- Web Audio is constructed lazily on the first user gesture and resumed if suspended, per browser autoplay rules. If `AudioContext` is unavailable the tool degrades to visuals only and says so in the header chip.
- The noise buffer for the Hush tone is generated from a fixed seed, so the tool sounds identical on every load.
- Vibration is offered **only** when `navigator.vibrate` exists, and the UI states plainly that many devices ignore it. No hardware capability is claimed beyond what browsers actually expose — in particular, pulse strength is derived from **press duration**, not from finger pressure, and the interface says so.
- `prefers-reduced-motion` is honoured in three places: the page's own CSS, the live preview (shallower dip, shortened release, no ripples or halos), and the exported CSS, which ships its own reduced-motion block.
- Accessibility: semantic buttons, `aria-pressed` / `aria-selected` / `aria-label` on controls, a `role="status"` live region for feedback, visible `:focus-visible` rings, and a keyboard-playable pad.
- Clipboard uses the async Clipboard API with a `document.execCommand` fallback; downloads use `Blob` + object URLs, revoked after use.

**Honest framing**

This is a local design and prototyping instrument. It is not measurement, analytics, prediction, optimisation, or user research, it produces no scores or grades, and it does not depict or simulate any real product, company, or system. The preview surface and its button are invented, and pressing them submits nothing anywhere.
