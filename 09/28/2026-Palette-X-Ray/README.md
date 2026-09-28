# Palette X-Ray

## What it is

Palette X-Ray is a self-contained, local-first screenshot color inspector. Drop, paste, or choose an interface image and it samples real pixels, clusters dominant color families, highlights where a selected family appears, identifies near-duplicate tokens, probes WCAG contrast, and exports CSS variables or JSON. A synthetic product screenshot is built in, so it is useful immediately.

No server, account, package install, external asset, upload, or network connection is required.

## Privacy-safe inspiration

Inspired by the generic craft of making polished interfaces and understanding the hidden systems behind screenshots. It does not represent or reproduce any real project, customer, conversation, company, or personal data.

## How to open

Open `index.html` in a modern browser. The built-in demo is analyzed automatically. Imported images are processed entirely in the browser and never leave the device.

## Controls

- **Choose image:** load a PNG, JPEG, WebP, or other browser-supported image.
- **Paste / ⌘V:** import a screenshot from the clipboard where browser permissions allow it.
- **Drag and drop:** drop an image directly onto the preview.
- **Dominant family swatch:** show an X-ray mask over every pixel near that color family.
- **Clear X-ray:** remove the mask while preserving the analysis.
- **Copy CSS:** copy generated custom properties.
- **Download JSON:** save the token receipt locally.
- **Restore demo:** return to the built-in synthetic screenshot.

## Why it was built

Screenshots make a finished interface visible while hiding its design system. Palette X-Ray reverses that relationship: one direct interaction turns pixels into reusable tokens and exposes where visual complexity may be accidental. It is a practical little future-product prototype rather than a canned report—the palette, masks, percentages, contrasts, and exports are computed from the current image.

## Format choice

- **Lane:** Practical micro-tool / real-feeling product prototype
- **Mechanic:** Local image ingestion plus deterministic Canvas pixel sampling, color clustering, tap-to-highlight X-ray masks, contrast probes, near-duplicate detection, and token export

This is structurally distinct from the previous three surprises' responsive music instrument, tactile timeline, and interface-deduction game.

## Explicit bans avoided

This is not a field guide, zine, atlas, almanac, codex, bestiary, or pocket guide. It has no choose-your-own story, branching adventure, microquest, or multiple endings. It uses no signal, cartographer, constellation, routing, or path-connection metaphor. It is not a launch/readiness/shipping simulator, scorecard, rubric meter, abstract AI-agent context/preflight/debugger, or generic generator. It is not a family/travel planner, baseball/data toy, or home/Seattle/local utility.

## Privacy and accessibility

All analysis is local and the page makes no network requests. The built-in screenshot and labels are fictional and generic. The artifact contains no real names, email addresses, phone numbers, street addresses, financial information, credentials, private quotations, analytics, or personal details. Primary controls meet a 44px touch-target goal, the layout is designed for a 390px viewport, keyboard access is provided for image loading, status updates use live regions, and reduced-motion preferences are respected.
