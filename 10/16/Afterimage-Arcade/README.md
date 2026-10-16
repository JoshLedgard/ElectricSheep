# Afterimage Arcade

## What it is

A five-round neon memory game. A pattern of glowing tiles flashes on the board, fades into a coloured afterimage, and goes dark. Then you rebuild it from memory by tapping tiles. Every tap tells you straight away whether it was right (it lights up) or a stray (red ✕, shake). When the round ends, the board shows what you got: matched tiles stay lit, missed tiles appear as dashed gold "ghosts", stray taps stay marked, and a small replay of the original flash sits beside them.

The five rounds, each adding a new twist:

1. **Warm Glow** (4×4): no twist. Remember it and tap it back.
2. **Mirror Cabinet** (5×5): rebuild it flipped left-to-right. The board flips once as a cue.
3. **Decoy Neon** (5×5): pink stars and cyan rings both flash, but only the stars count.
4. **Quarter Turn** (5×5): rebuild it rotated 90° clockwise. The board spins once as a cue.
5. **Double Exposure** (6×6): two quick flashes, cyan then lime. Rebuild both layered together.

Each round allows three stray taps and earns 0–3 stars (3 = perfect, 2 = complete with strays, 1 = at least half found). The final "cabinet ticket" shows your best stars for each round and gives you a rank.

## Inspiration

The faint coloured ghost you see after staring at a bright light and then looking away, plus classic arcade "watch then repeat" memory cabinets. This is generic, privacy-safe inspiration: no personal data, private messages or real-world details went into it.

## How to open

Open `index.html` in any modern browser, on desktop or phone. It's one self-contained file with inline CSS and JS. It needs no network, packages, server or build step.

## Controls

- **Touch / mouse:** tap **Flash pattern**, watch, then tap tiles. **Reveal now** ends the round early. After a round, choose **Next round** or **Retry round** (retry gives a fresh pattern, and only your best score is kept). **Play again** on the final ticket restarts with new patterns.
- **Keyboard:** `F` flashes, arrow keys (plus `Home`/`End`) move around the board, `Space` or `Enter` taps a tile, `G` reveals now, `N` goes to the next round or plays again, `R` retries, and `M` toggles sound.
- Tiles and buttons are at least 44px on a 390px-wide phone, and the page never scrolls sideways. Screen readers hear each result ("Correct, 3 of 6" / "Stray tap"). With reduced motion turned on, the flip and spin cues and the shake are switched off.

## Why built

Memory games are most satisfying when they show exactly where your memory slipped. The "reveal the difference" board turns a miss into a small "oh, *that* one" moment. Then the twists (mirror, decoys, rotation, double exposure) keep each round asking for a different kind of mental work, not just a bigger grid.

## Format choice

**Lane:** `game_or_puzzle`

**Mechanic:** briefly view a tiled pattern, then rebuild it by tapping tiles from memory, then reveal the difference. There are five designed rounds with escalating visual twists, instant per-tap correct/incorrect feedback, a star score for each round, retry, and full replay.

## Explicit bans avoided

No field guide, zine or atlas framing; no branching story; no signal, cartographer, constellation or routing metaphor; no launch or readiness simulator; no scorecard or rubric tool (the stars are simply game points); no abstract AI preflight; no generic generator. The patterns are hand-designed for each round, not generated content.

## Privacy

No network requests, external assets, cookies, storage, accounts or analytics. Nothing is saved between visits. It contains no real names, emails, addresses, money or chat details.
