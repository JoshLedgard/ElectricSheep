# Loop Desk

A pocket flipbook: draw a six-frame, 16×16 pixel loop with onion skin, watch it play live, and download it as a sprite sheet PNG.

## Inspiration

Paper flipbooks in the corner of a school notebook, and the tiny walk-cycle sprite sheets from old handheld games. Six frames are enough to tell a very short visual story: a squash, a hop, a sparkle at the top, a landing.

## Open

Open `index.html` in any modern browser, on desktop or phone. It's one self-contained file with no network requests, no build step, and no dependencies.

## Controls

- **Draw:** tap or drag on the grid. Tools are Pen, Erase, Fill, Undo, and Onion skin. Pick colours from the 12-swatch palette.
- **Frames:** tap a thumbnail (1–6) to edit that frame. Onion skin ghosts the previous frame (it wraps around, so frame 1 shows frame 6). **Copy previous** duplicates the prior frame so you can nudge a few pixels.
- **Live loop:** Start/Stop playback. The Speed slider runs from 1 to 15 fps.
- **Sprite sheet:** choose a pixel size (1×–16×), then **Download PNG**. If the download is blocked, **Show image** displays the sheet so you can long-press or right-click to save it.
- **Reset…** asks for confirmation, then gives a blank desk or reloads the demo. Undo still restores your previous loop.
- **Keyboard:** `B`/`E`/`F` switch tools, `1`–`6` jump to a frame, `,`/`.` go to the previous/next frame, `C` copies the previous frame, `O` toggles onion skin, `Z` or Ctrl/⌘+Z undoes, `P` starts/stops. On the focused grid, arrow keys move the cursor, Space/Enter paints, and Shift+arrows paint while moving.

## Why

Making something move is magic, and most animation tools bury that magic under timelines and layers. Loop Desk keeps only what you need: a small grid, six frames, a ghost of the last frame, and an instant loop. A hopping blob is preloaded so the first thing you do is remix, not stare at a blank canvas.

## Format choice

**Lane:** `visual_story_or_comic`

**Mechanic:** frame-by-frame pixel drawing with onion skin and a looping playback preview; export six frames as a horizontal PNG sprite sheet. No narrative choices or branching.

## Explicit bans avoided

No field-guide, atlas, almanac, codex, bestiary, pocket-guide or zine framing; no choose-your-own adventure, branching story or microquest; no signal-routing, cartographer, constellation or connect-the-nodes metaphor; no launch/readiness/shipping simulator, generic scorecard/rubric meter, abstract AI-agent preflight tool, or generic generator. This is a drawing instrument, not a guided narrative.

## Privacy and accessibility

No network calls, external assets, accounts, cookies, or analytics. The only persistence is the loop saved in this browser's `localStorage`; it fails gracefully if storage is blocked. Reset asks for confirmation and undo covers resets. Touch controls and keyboard controls are available; playback starts stopped for reduced-motion users. No personal data or private source material is included.
