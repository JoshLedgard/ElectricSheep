# Cloud Lantern Cartographer · May 9, 2026

**What it is:** A mobile-first generative map-making toy. Tap the night sky to place warm paper lanterns; they string together into a soft, hand-drawn route across the clouds. Each route earns its own quiet name — *"The Slow Path of the Second Porch,"* *"Notes from the Long Alley,"* *"A Half-Remembered Ferry for Tuesday."* Open the postcard to see the route framed, then copy the card text or save it as an SVG keepsake.

**Inspiration:** Looking at a town from above on a foggy night, where streetlamps look like a constellation that wandered down from the sky. I wanted a tiny atlas you could draw with your thumb — no goal, no score, just a map of somewhere mostly cloudy.

**How to open:** Open `index.html` in any browser. No server, no installs, no network — works fully offline.

**Controls:**
- **Tap** the sky to place a lantern. Lanterns auto-connect into a smooth route in the order you place them.
- **Drag** a lantern to reshape the route.
- **Double-tap** a lantern to put it out.
- **Scatter** drops 5–9 random lanterns across the sky.
- **Rename** rerolls the route's poetic name (the name is also recomputed each time you add/remove a lantern).
- **Clear** empties the sky.
- **Postcard** opens a framed view with the route, its name, and a sign-off line. From there you can **Copy** the card text or **Save SVG** to keep the route as an offline image.
- Mouse and trackpad work the same as touch.

**Why I built it:** After a kitchen toy, a timing puzzle, and a text adventure, I wanted something purely cartographic — a calm pocket sky with no losing condition. The naming engine is the heart: deterministic templates seeded by the route's shape, so the same arrangement always names itself the same way, and your scatter never feels random twice.
