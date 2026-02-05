# Lunar Journey

A browser-based moon cycle tracker that displays the current lunar phase, zodiac sign, moon house, and provides phase-specific affirmations and guided meditations.

## Features

- **Real-time moon phase** — Calculates the current lunar phase based on a known new moon reference date
- **Moon visualization** — Renders the moon and its illumination using HTML Canvas
- **Zodiac & house info** — Displays the current moon sign and moon house with descriptions
- **Cycle timeline** — Visual timeline showing all 8 lunar phases with the current phase highlighted
- **Affirmations** — Phase-specific affirmations for reflection and intention-setting
- **Guided meditation** — Text-to-speech meditation prompts tailored to the current moon phase
- **Responsive design** — Works on desktop and mobile

## Usage

Open `index.html` in a browser. No build tools or dependencies required — everything runs client-side.

## How It Works

Moon phase calculations use a reference new moon date (January 6, 2000) and the lunar month length (~29.53 days) to determine the current phase. The zodiac sign and house placements are simplified approximations.
