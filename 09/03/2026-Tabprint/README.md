# Tabprint

## What it is
Tabprint is a self-contained, privacy-first browser-tab analyzer. Paste tab titles and URLs—or open the built-in synthetic demo—and it turns the pile into an interactive radial fingerprint grouped by domain. Repeated and near-repeated research is highlighted, each domain can be isolated, and the visualization can be exported as a PNG.

## Privacy-safe inspiration
Inspired generically by the usefulness of tools that inspect and structure messy information while keeping the user in control. It contains no details from private conversations or personal data.

## How to open
Open `index.html` in any modern browser. It requires no server, account, package install, network connection, or external assets.

## Controls
- Paste one tab per line as `Title — https://domain/path`, a bare URL, or a plain title.
- Choose **Make tabprint** to parse and redraw the visualization.
- Choose **Load demo** for a safe synthetic data set or **Clear** to reset.
- Tap/click a colored domain band—or its accessible domain button—to isolate that group; tap it again to show everything.
- Pink markers and bordered rows identify exact or near-repeated title sets.
- Choose **Export PNG** to save the current fingerprint locally.

## Why it was built
Open tabs are an accidental record of curiosity, unfinished loops, and repeated research. Tabprint makes that shape visible without turning it into a judgment, productivity score, or cloud service. It is a small example of a useful personal-data tool that can remain entirely local.

## Format choice
- **Lane:** practical micro-tool + tactile data visualization / future-feeling fake app
- **Mechanic:** local parsing of pasted tab lines into a touch-selectable radial domain fingerprint, with duplicate inspection, domain isolation, and working PNG export

## Explicit bans avoided
No field-guide, zine, atlas, almanac, codex, bestiary, or pocket-guide framing; no choose-your-own or branching story, microquest, or multiple endings; no signal-routing, cartography, constellation, or path-connection metaphor; no launch, readiness, or shipping simulator; no generic scorecard or rubric meter; no abstract AI-agent preflight or context debugger; no poetic or random generator; and no family, travel, baseball, or local utility.

## Privacy check
The artifact contains no real names, email addresses, phone numbers, street addresses, financial data, private quotes, credentials, trackers, analytics, external assets, or network requests. Its demo data uses only reserved `.example` domains. User input, similarity analysis, drawing, and PNG export remain in the browser.

## Verification
- Complete single-file HTML/CSS/JavaScript artifact with no dependencies.
- Responsive layout includes a 390px breakpoint, wrapping controls, minimum 44px button targets, and no fixed-width page content.
- Mouse, keyboard, and touch-compatible domain selection; accessible detail-list fallback; reduced-motion support.
- Deterministic in-page parser/duplicate self-test reports `Tabprint self-test: PASS` in the console and sets `data-self-test="pass"` on the document root.
- PNG export serializes the live SVG, renders it to a local canvas, and downloads the result.
- Privacy scan found only synthetic `.example` data and the generic local-only explanation above.
