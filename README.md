# Atmen

A single-file web app for guided breathing exercises — "Atmen wie Heike" —
following Heike Trautwein's recommendation of a ~5.5-second breath rhythm
(coherence breathing).

Open `index.html` in any modern browser. No build step, no dependencies.

## Features

- Animated breath column with an on-screen countdown clock
- Audio cues: tone and/or spoken voice (EN / FR / DE)
- Nine tone characters, previewed on tap in Settings:
  - Chime, Bell, Wood, Air
  - Temple: Bowl, Tingsha, Ghanta (Himalayan) · Gong, Bamboo (Thai) —
    synthesised approximations, not recordings
- Four themes: Night (default), Sage and Meadow (light, green), Forest (dark green)
- Presets: Coherence 5.5, Box 4-4-4-4, 4-7-8
- Fully adjustable rhythm (inhale / hold / exhale / hold) and session length
- Settings persist on the device (`localStorage`)
- Checks once per launch for a newer deployed version and reloads past the cache
  (iOS Safari otherwise serves a stale copy for days)
- Screen wake lock keeps the display on during a session
