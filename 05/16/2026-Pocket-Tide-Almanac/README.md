# Pocket Tide Almanac

A tiny morning toy that lets you arrange a circular tide pool — shells, pebbles, kelp — then slides the moon to bring the tide in and out. When you're satisfied with the small world, tap **Compose entry** and the toy mints a one-paragraph almanac entry for the morning.

## What it is

A self-contained, mobile-first browser toy. A round tide pool sits at the center of the screen with:

- An animated water surface (gradient + concentric ripples + sine-band caustics) that subtly changes color and brightness with the tide level.
- A sand/rim with tiny tide notches drifting around the outside, and a small moon highlight on the water that travels with the slider.
- A palette of three things you can place — **shell**, **pebble**, **kelp** — plus an **Erase** tool.
- A **moon slider** running from new → full, which drives the water level (new and full are extremes, neaps sit in the middle) and the named "moon phase / tide" readouts.
- Three actions: **Clear**, **Scatter** (random arrangement), and **Compose entry**.

Play for 2–3 minutes: tap or drag inside the pool to place a few objects, swing the moon around, then compose. The almanac entry is a small typeset card with a poetic name (e.g. *A Quiet Saltwater Page*, *A Brass Footnote*), the current moon phase and tide, what's in the pool, and a soft closing line. There's a Copy button if you want to keep it.

## Privacy-safe inspiration

The vibe: the moment of crouching by a tidepool on a quiet morning and naming the things you see; the way an old almanac compresses weather and observation into a single line. No personal information, conversations, or private context informed the build — only the generic fresh-start / morning-curiosity theme.

## How to open

Double-tap `index.html` in this folder. It runs in any modern browser — Safari, Chrome, Firefox — on phone or desktop. No installation, no server, no network calls, no external assets.

## Controls

- **Palette (top row of buttons)** — pick what you're placing next: Shell, Pebble, Kelp, or Erase.
- **Tap or drag inside the pool** — places the selected object. Drag-placing is throttled so you don't accidentally carpet the pool.
- **Erase tool** — tap a placed object to remove it.
- **Moon slider** — sets the moon phase (and therefore tide). The readouts at the top of the pool update live.
- **Clear** — empties the pool.
- **Scatter** — randomly arranges 6–11 objects.
- **Compose entry** — generates a small named almanac entry below the pool.
- **Copy** (on the almanac card) — copies the entry to your clipboard as plain text.

## Why it was built

Today's Daily Surprise. The brief asked for a tactile micro-toy distinct from this week's grid circuit (Dewdrop Switchboard), kite simulator (Kite Signal Atelier), and map-stamping toy (Morning Compass Cartographer). A circular tide pool with an animated waterline and a tiny almanac generator felt right for a Saturday morning — physical and quiet, with a small written keepsake at the end if you want one.
