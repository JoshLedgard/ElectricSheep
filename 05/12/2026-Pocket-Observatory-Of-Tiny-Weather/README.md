# Pocket Observatory of Tiny Weather · May 12, 2026

**What it is:** A mobile-first instrument panel for inventing the next little while of weather. Drag three sliders, choose an hour of the day, flip the fog veil on or off — the sky overhead responds, and a small forecast postcard composes itself underneath. Tap *Copy postcard* to pocket it; tap *New reading* to get a fresh phrasing of the same weather.

**Inspiration:** Old paper barometers with their *set fair / changeable / rain in mind* labels, and the small private satisfaction of looking out a window and quietly deciding what the afternoon is going to be.

**How to open:** Open `index.html` in any modern browser. Self-contained, no server, no installs, no network — it runs fully offline.

**Controls:**
- **Cloud cover** slider — from clear-skied to blanketed; controls the number and opacity of clouds in the sky preview, plus whether rain begins to fall.
- **Wind whisper** slider — from hushed to ribboned; scales the wind streaks drifting across the sky and changes which verbs the postcard uses.
- **Warmth** slider — from frostbitten to bronze-hot; shifts the sky's warm/cool tint and selects the postcard's adjectives.
- **Sky hour** pills — *dawn · morning · noon · dusk · night* — moves the sun or moon, repaints the sky, swaps in stars at night. Arrow keys cycle through hours.
- **Fog veil** toggle — drops a soft white veil over the scene and gauzy phrasing into the postcard.
- **Copy postcard** — copies the current postcard (title, body, barometer, mood, filed-at time) to the clipboard.
- **New reading** — rerolls the wording without changing the weather you've dialed in.

**Privacy:** No network calls, no analytics, no cookies, no localStorage, no service workers. Nothing leaves the device; nothing persists between opens.

**Files:**
- `index.html` — the entire toy: HTML, CSS, animated SVG sky, postcard generator, all in one file.
- `README.md` — this overview.
- `READY` — completion marker created after validation.
