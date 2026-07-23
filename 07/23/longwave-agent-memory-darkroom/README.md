# Longwave — An Agent Memory Darkroom

## What it is

Longwave is a tactile, deterministic thought instrument for exploring a simple agent-memory design idea: exact wording, durable gist, and uncertain residue can behave differently as time passes.

Start with one of three harmless fictional episodes—or type a short note that stays only in the open browser tab. Adjust **rehearsal interval**, **semantic compression**, and **interference**, then play or scrub the timeline. The darkroom emulsion and six-frame contact sheet visibly separate crisp words, meaning-carrying fragments, and residue. At any point, copy a plain-text memory-design receipt or download the contact sheet as SVG.

Longwave is illustrative. It is not neuroscience, a scientific model, a benchmark, a score, a prediction of any real AI system, or evidence about real memory behavior. The same text and control settings always produce the same result.

## Privacy-safe inspiration

The broad, generic inspiration was an interest in preserving the essential character of information while systems transform it, and in making hidden workflow behavior tangible. That theme became a fictional darkroom where wording, gist, and uncertainty develop on separate visual layers.

The built-in episodes are entirely synthetic. They contain no real people, employers, products, projects, accounts, messages, conversations, or datasets. Custom text is processed only in memory inside the open tab: it is never stored, transmitted, uploaded, or analyzed elsewhere.

## How to open

Open `index.html` in any modern browser. No server, installation, package, account, network connection, external font, or external asset is required.

## Controls

- **Another sample** cycles through three fictional built-in episodes.
- **Use my note** opens a local-only 240-character input; enter at least a few words, then choose **Develop this note**.
- **Rehearsal interval** changes how long exact wording remains crisp in the illustration.
- **Semantic compression** trades exact wording for longer-lived gist fragments.
- **Interference** increases how quickly fragments become uncertain residue.
- **Play / pause** runs the time-lapse from epoch 0 to 100.
- **Timeline** scrubs directly to any epoch.
- **Contact-sheet frame** jumps to that frame's epoch.
- **Copy receipt** copies a compact, non-scoring explanation of the current controls and result.
- **Download SVG contact sheet** saves a local visual artifact of the six illustrated epochs.

## Why it was built

Agent memory is often discussed as an invisible abstraction. Longwave turns three design tensions—rehearsal, compression, and interference—into something physical-feeling and inspectable without pretending to measure a real model. It is intended as a two-to-three-minute experiment that leaves behind a useful design receipt rather than a grade.

## Format choice

- **Lane:** `ai_agent_memory_prototype`
- **Mechanic:** a tactile, single-screen time-lapse darkroom instrument. The user develops one harmless episode with three physical-feeling controls, scrubs or plays a deterministic timeline, watches exact wording separate into durable gist and uncertain residue, and exports a compact receipt or SVG contact sheet. This is a transparent explanatory interaction, not a chatbot, score, benchmark, generated-prose tool, or context debugger.

This lane and mechanic differ from the previous three surprises' creative rotoscoping, time-delayed scratchpad, and live gesture-observatory interactions.

## Explicit bans avoided

Longwave deliberately uses:

- no field guide, zine, atlas, almanac, codex, bestiary, or pocket-guide framing;
- no choose-your-own, branching adventure, microquest, or multiple-ending story;
- no signal, cartographer, constellation, routing, or path-connection metaphor;
- no launch, readiness, or shipping simulator;
- no scorecard, rubric meter, grade, benchmark, or ranking;
- no abstract agent context, preflight, prism, or generic debugger;
- no card sorting; and
- no poetic or generic generator.

## Privacy and implementation

- One self-contained HTML file with inline CSS, JavaScript, and canvas/SVG art.
- No dependencies, cookies, analytics, service workers, fetches, remote assets, or persistent browser storage.
- Custom text lives only in JavaScript memory for the lifetime of the tab.
- Mobile-first layout includes viewport handling, large touch controls, keyboard focus states, readable type, responsive high-DPI canvases, reduced-motion support, and no hover-only interaction.
