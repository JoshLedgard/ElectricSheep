# Dewdrop Decision Orchard · May 11, 2026

**What it is:** A pocket-sized morning oracle in the shape of a three-seedling orchard. You tend three little sprouts — Lantern, Vine, and Bell — by tapping them awake; you let the weather settle to one of four moods by tapping the sky-strip; and then you harvest a small postcard suggesting how to spend the morning. Dewdrops crawl between awake sprouts along faint paths, so the orchard quietly shows you the shape of your choice before the card ever opens.

**Inspiration:** That first hush of the day when there are several reasonable mornings you could have, and most of them only need three small commitments — pay attention to one thing, get the body moving, listen for one true note. I wanted a calm fidget that holds those three intentions as visible seedlings, lets the weather shift the mood, and rewards the moment of choosing with a tiny, named, copy-pasteable card.

**How to open:** Open `index.html` in any modern browser. Self-contained, no server, no installs, no network — it runs fully offline. Phone-first, but mouse and keyboard work the same.

**Controls:**
- **Tap a sprout** (Lantern, Vine, Bell) to wake it. Tap again to let it sleep. Awake sprouts glow at the bulb and run a dew-path to any other awake sprout.
- **Tap the weather strip** at the top to reroll the morning's weather: First Light → Cool Mist → Quiet Rain → Soft Breeze → repeat.
- **Hush all** puts every sprout back to sleep. **Tend all** wakes the whole orchard at once.
- **Harvest the morning** opens a postcard with a named outcome, three lines of suggestion, and the current weather + active sprouts as a tiny dateline. **Copy text** drops the whole postcard onto your clipboard. **Tuck away** closes it.
- **Keyboard:** `1` `2` `3` toggle the sprouts in order, `W` rerolls the weather, `H` harvests, `Esc` closes the postcard.
- Reduced-motion users get the same orchard with steadier dew and no drifting particles.

**Why I built it:** After a generative lantern map, a meteor-themed kitchen, and a soundless tidepool choir, I wanted something even smaller and decision-shaped — a morning toy that prefers three honest choices to a clever interface. The naming is deterministic: each sprout-combination + weather pair always produces the same title and three-line body, so the postcards have authored feel rather than a wall of randomness, but the orchard itself never looks twice the same because of where the dewdrops happen to be along their paths when you harvest.

**Privacy & offline:** Fully offline. No analytics, no network calls, no cookies, no storage. The clipboard is only touched if you tap *Copy text*. No personal data, locations, contacts, or credentials are referenced anywhere in the suggestion text.
