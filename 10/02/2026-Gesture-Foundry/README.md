# Gesture Foundry

## What it is

Gesture Foundry is a self-contained motion-capture prototype for interface gestures. Draw with a finger, mouse, or trackpad and it measures the path, duration, distance, velocity, acceleration, and pauses. The gesture can be replayed, reversed, scrubbed through time, interpreted with three motion styles, and exported as SVG, CSS keyframes, or normalized JSON.

A built-in gesture is loaded at first open, so the interface is useful before recording anything.

## Privacy-safe inspiration

It was inspired by a broad interest in polished product interfaces, dependable verification, and tools that make normally invisible behavior tangible. It does not represent any real person, company, customer, project, or private conversation.

## How to open

Open `index.html` in a modern browser. It is one self-contained file and needs no server, package install, account, external asset, or network connection.

## Controls

- **Capture stage:** press and drag to record a gesture with touch, mouse, or trackpad.
- **Replay:** reproduce the gesture using its measured timing.
- **Timeline:** scrub to any moment in the motion.
- **Raw hand / Fluid / Snappy:** compare the recorded movement with smoothed and accelerated interpretations.
- **Reverse:** invert the path and timing.
- **Load demo / Clear:** restore the built-in example or empty the stage.
- **Copy SVG / Copy CSS / Download JSON:** export a scalable path, sampled keyframes, or normalized motion data.
- With keyboard focus on the stage, **Enter** or **Space** replays the current gesture.

## Why it was built

Motion design is often reduced to a dropdown of easing names. Gesture Foundry starts with the movement a person actually makes, then exposes its rhythm as inspectable and reusable interface material. It is a small future-product artifact that turns direct manipulation into truthful motion data.

## Format choice

- **Lane:** Future artifact / fake app; real-feeling product prototype
- **Mechanic:** Pointer gesture recording, computed motion analysis, timeline scrubbing, replay, style interpretation, and multi-format export

This differs structurally from the previous surprises’ typing-driven visual instrument, copy-tightening game, and timed drag-and-archive game.

## Explicit bans avoided

This is not a field guide, atlas, almanac, codex, bestiary, zine, or pocket guide. It has no choose-your-own story, branching adventure, microquest, or multiple endings. It uses no signal, cartographer, constellation, routing, or path-connection metaphor. It is not a launch/readiness/shipping simulator, scorecard, rubric meter, preflight/context/prism/debugger, or generic generator. It is not a family/travel planner, baseball/data toy, or home/local utility.

## Privacy, mobile, and accessibility

Everything runs locally. Nothing is uploaded, stored, or tracked. The artifact makes no network requests and contains no names, emails, phone numbers, addresses, financial data, credentials, private quotations, or personal details. The layout is designed to avoid horizontal overflow at 390px, pointer capture supports touch and mouse, primary controls meet a 44px touch-target goal, key status changes use a live region, the capture surface is keyboard focusable, and reduced-motion preferences shorten replay animation.
