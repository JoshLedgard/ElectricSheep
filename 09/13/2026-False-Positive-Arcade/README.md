# False Positive Arcade

## What it is

A self-contained, touch-friendly Monte Carlo experiment about A/B test uncertainty. Set the true conversion rates and sample size, run one animated two-arm binomial race, or run a batch of 100 or 500 trials. The outcome wall separates significant A wins, significant B wins, and inconclusive results, then explains the pattern in plain English.

This is an educational simplification, not a production experimentation calculator. It uses independent binomial samples and a pooled, two-sided, two-proportion z test at the selected confidence threshold. Real decisions also need power planning, data-quality checks, guardrails, and corrections for repeated peeking or multiple comparisons.

## Inspiration

Repeated samples from the same underlying truth can tell surprisingly different stories. The arcade cabinet metaphor makes that variation visible without using any personal data or real experiment details.

## Open instructions

1. Open `index.html` in any modern web browser.
2. No server, installation, package, account, network connection, or external asset is required.
3. For a quick demonstration, choose **No real difference** and press **RUN ×500**.

## Controls

- **Baseline conversion** sets the true conversion probability for arm A. The controls keep expected conversions at five or more per arm so the normal approximation is not offered in its most misleading low-count range.
- **True relative lift for B** changes B relative to A and explicitly includes zero.
- **Visitors per arm** controls the sample size in each simulated experiment.
- **Confidence threshold** sets the two-sided significance cutoff.
- **No real difference** loads equal true rates, making declared winners false positives.
- **Small true lift** loads a modest advantage for B.
- **RUN 1 RACE** animates one reproducible simulated experiment and shows conversions, observed rates, z statistic, cutoff, and verdict.
- **RUN ×100** and **RUN ×500** show the distribution of outcomes across independent trials.
- **Simulation seed** makes each combination of seed, settings, and run type replayable. Press Enter in the seed field to run one race.
- **Reset** restores the original controls, seed, race, and results.
- Changing any experiment setting clears old outcomes so results cannot be mistaken for the newly loaded design.

All native controls support keyboard use. Interactive targets are at least 44 pixels tall, the layout is mobile-first, and reduced-motion preferences shorten the race animation.

## Why built

Statistical significance is often mistaken for certainty. This artifact demonstrates that one result is only one draw from a distribution: equal variants can produce apparently decisive winners, and real differences can still yield inconclusive or wrong-direction results.

## Format choice

- **Lane:** `data_visualization`
- **Mechanic:** A tactile Monte Carlo race board. One simulated two-arm binomial test moves competitors down parallel rails; batches of 100 or 500 tests become an outcome wall of A wins, B wins, and inconclusive trials.

The arcade/lab presentation supports immediate manipulation and visual comparison while keeping the statistical assumptions visible.

## Explicit bans avoided

This is not a field guide, zine, atlas, almanac, codex, bestiary, or pocket guide. It has no branching narrative, choose-your-own-adventure structure, microquest, or multiple endings. It does not use routing, cartography, constellations, or path connection. It is not a launch, readiness, or shipping simulator; not a scorecard or rubric; not an AI context, preflight, or debugger; and not a poetic generator. Its subject matter does not involve family, travel, baseball, home, or local themes.

No real names, email addresses, street addresses, phone numbers, quotations, or sensitive personal specifics appear in the artifact.
