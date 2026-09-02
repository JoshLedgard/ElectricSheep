# Assumption Half-Life Lab

A tactile, mobile-first product prototype for treating product assumptions as decaying assets rather than permanent truths. Each belief has a starting confidence and a half-life. Advance the simulated clock to watch confidence decay, then add supporting or contradicting evidence to intervene on the curve.

## What it is

The lab is a connected portfolio of assumption cards and an animated, multi-line SVG timeline. It makes stale certainty visible: confidence naturally falls between observations, while dated evidence changes the curve at the moment it appears. Connections identify beliefs that depend on another belief.

The fictional demo makes the interaction useful in under 15 seconds. A focused review—scrubbing time, selecting a curve, adding an intervention, and setting a reminder—takes about 2–3 minutes.

## Privacy-safe inspiration

The concept is inspired by the scientific half-life metaphor and by product discovery’s emphasis on falsifiable beliefs. It uses only fictional, generic defaults. It contains no names, email addresses, phone numbers, street addresses, customer records, or other private information.

Everything runs in the browser. Data is stored only in that browser’s `localStorage`. There are no network calls, external dependencies, accounts, cookies, analytics, trackers, or telemetry.

## How to open

1. Open `index.html` directly in any current browser (double-click it in Finder or drag it into a browser window).
2. No install, package manager, build command, or local server is needed.
3. To start over, use **Reset demo**. To remove all locally entered data, use **Clear all**.

## Controls

- **Advance the clock:** drag the 0–90 day timeline scrubber. Left and Right Arrow adjust it one day at a time.
- **Inspect a belief:** tap or click the body of an assumption card to isolate its curve; activate it again to restore every curve.
- **Add evidence:** choose **+ Evidence**, mark it supporting or contradicting, enter a dated observation and impact. The intervention appears as a colored dot and recalculates confidence.
- **Create:** choose **New assumption** or press `N`. Enter the belief, confidence, half-life, and optional connection.
- **Maintain:** each card offers Edit and Delete controls.
- **Remember:** open **Reminders** to schedule a review prompt; due prompts surface in the insight panel.
- **Close:** press Escape, use the close button, or click outside a dialog.

Touch controls are at least 44px tall. The interface supports keyboard focus, readable semantic text, reduced-motion preferences, and a responsive 390px layout without horizontal overflow.

## Why built

Teams often preserve the confidence attached to an early belief while forgetting how old its evidence is. This prototype separates belief, time, and intervention. Its decay model does not claim statistical truth; it creates a practical conversation: “What do we still know, what has expired, and what evidence should we collect next?”

## Format choice

- **Lane:** product prototype / tactile data visualization
- **Mechanic:** timeline scrubbing plus direct evidence interventions on animated decay curves.

A self-contained HTML application was chosen because the central idea needs manipulation, time, and visible recalculation—not a static document. Inline CSS creates the future-software visual system, inline JavaScript owns local state and interactions, and SVG renders smooth multi-line decay curves plus evidence markers. The artifact remains portable, inspectable, offline, and dependency-free.

## Explicit bans avoided

This is **not** a field guide, zine, atlas, or codex. It has no choose-your-own or branching structure. It does not use signal, cartographer, routing, or constellation metaphors. It is not a launch, readiness, or shipping simulator. It is not a scorecard, rubric, preflight, context debugger, or generator.

## Data behavior

- Storage key: `assumption-half-life-lab-v1`
- Demo data is fictional and generic.
- **Reset demo** replaces local state with the bundled fictional portfolio.
- **Clear all** removes assumptions, evidence, and reminders from the application state and saves the empty state locally.
- Nothing is transmitted anywhere.
