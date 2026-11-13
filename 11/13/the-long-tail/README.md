# The Long Tail

**Daily Surprise · November 13, 2026**

## What it is
A self-contained, interactive laboratory for exploring how sequential and parallel tool tasks affect the feel of a request. Adjust two synthetic scenarios and compare their simulated P50, P95, and P99 distributions, request timelines, and fan-out behavior. These are illustrative simulations, **not measurements or predictions**.

## Inspiration (privacy-safe)
A general curiosity about the gap between average response times and the slow requests people remember. No personal conversations or private data are embedded.

## How to open
Open `index.html` in any modern browser, including offline from this folder. No install, account, server, or network is required.

## Controls
Choose a preset, then use the Scenario A/B tabs to adjust stage timings, variability, hiccup chance, tool-task count, and sequential/parallel execution. Compare the distributions and the fan-out chart; use **Race again** to replay the request timeline. **New sample** changes the deterministic simulation seed, **Copy A → B** or **Swap** helps compare configurations, and **Reset** restores the original setup. All controls are touch- and keyboard-accessible.

## Why it was built
A tactile way to see why parallelism can improve the middle while adding tail exposure, and why a single average hides important behavior. The sample and assumptions are visible so the tool invites investigation rather than claims of real-world accuracy.

## Format choice
- **Lane:** `data_visualization`
- **Mechanic:** interactive parameter sliders and switches driving side-by-side synthetic latency histograms, animated request timelines, and a fan-out curve.

## Explicit bans avoided
Not a field guide, zine, atlas, almanac, codex, branching adventure, microquest, signal router, cartographer, constellation puzzle, launch/readiness simulator, scorecard, rubric meter, generic AI context/preflight tool, or generic generator. No personal identities, contact details, addresses, financial information, or quotes.
