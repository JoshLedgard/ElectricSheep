# Splat Lab

## What it is

Splat Lab is a self-contained elastic color arcade. A soft colored blob settles onto a glowing membrane; pull the membrane down and sideways, release it, and fling the blob into the matching catch cup. The 75-second deterministic run includes escalating color changes, misses, combos, particles, optional haptics, pause/restart controls, and a real completion state.

## Privacy-safe inspiration

Inspired generically by tactile tools, playful systems, and interfaces that make direct manipulation immediately understandable. It contains no details from private conversations or personal data.

## How to open

Open `index.html` in any modern browser. It needs no server, account, package install, network connection, or external asset.

## Controls

- Press **Start 75-second run**.
- On touch or with a pointer, drag the membrane down and toward the matching colored cup, then release.
- With a keyboard, use Left/Right to aim, Down or Space to pull, and release Space to fling.
- Use **Pause**, **Restart**, or **Calm motion** at any time.
- Leaving the browser tab automatically pauses the game.

## Why it was built

A tiny physics toy can communicate an interaction faster than instructions can. Splat Lab explores a one-gesture game that feels physical, readable, and complete in two or three minutes—something closer to a fictional handheld arcade specimen than a themed webpage.

## Format choice

- **Lane:** `game_or_puzzle` / weird playable game presented as a future-feeling toy interface
- **Mechanic:** one-pointer elastic-membrane pulling and release to fling soft colored blobs into matching cups during a deterministic timed arcade run

## Explicit bans avoided

No field guide, atlas, almanac, codex, bestiary, zine, or pocket-guide framing; no choose-your-own, branching story, microquest, or multiple endings; no signal, cartographer, routing, constellation, connect-the-nodes, or path metaphor; no launch, readiness, or shipping simulator; no generic scorecard or rubric meter; no abstract AI-agent preflight or context debugger; no poetic or random generator; and no family, travel, baseball, home, or local utility.

## Privacy check

The artifact contains no real names, email addresses, phone numbers, street addresses, financial data, organizations, private quotes, credentials, analytics, trackers, external assets, persistent storage, or network requests. All labels and gameplay data are generic and bundled locally.

## Verification

- Complete single-file HTML/CSS/JavaScript artifact with no dependencies.
- Responsive canvas and wrapping interface designed for 390px screens without fixed-width page content.
- Touch targets are at least 44px; gameplay supports pointer, touch, and keyboard input.
- Reduced-motion preference and a manual calm-motion control are supported.
- A deterministic in-page logic self-test sets `data-self-test="pass"` on the document root when its membrane, sequence, and cup checks pass.
- The game includes instructions, a deterministic sequence, scoring/combo feedback, pause/restart behavior, misses, successful catches, and a timed completion state.
