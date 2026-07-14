# pure-vibes

A general testing ground for **pure vibe-coding** — exploring what current frontier AI models can produce end-to-end, with minimal human scaffolding.

The goal is to one-shot complete, working projects in a single session (a few hours at most), leaning entirely on the model's ability to design, implement, and debug without hand-holding.

---

## What is vibe-coding?

Vibe-coding is the practice of describing what you want at a high level and letting an AI model generate the full implementation — code, structure, assets, and all. No step-by-step guidance, no partial scaffolding: just a prompt and a result.

---

## Possible projects

### 🎮 Games
- **Snake** — classic grid-based snake game with score tracking and increasing speed
- **2048** — sliding tile puzzle with animations and a high-score board
- **Asteroids clone** — canvas-based space shooter with physics and particle effects
- **Wordle clone** — daily word-guessing game with colour-coded feedback and a share button
- **Tower Defence** — wave-based tower placement game with multiple enemy types and upgrade paths

### 📱 Apps
- **Pomodoro timer** — focus/break cycle tracker with sound alerts and session history
- **Markdown notes app** — local-storage-backed editor with live preview and tag filtering
- **Habit tracker** — daily habit check-in with streaks, calendar heatmap, and progress charts
- **Budget splitter** — enter a bill and a list of names, get per-person breakdowns with optional tip
- **Flashcard quiz app** — spaced-repetition study tool with deck import/export via JSON

### 📊 Data visualisations
- **Real-time crypto dashboard** — price ticker and candlestick chart pulling from a public API
- **World population explorer** — interactive choropleth map with time-slider and country drill-down
- **GitHub contribution graph** — personalised activity heatmap using the GitHub public API
- **CO₂ emissions over time** — animated line chart across countries using open climate datasets
- **Music taste analyser** — radar/bar charts from a Spotify export showing genre and audio-feature breakdowns

---

## Structure

Each project lives in its own subdirectory. Every subdirectory should be self-contained and runnable without external build steps where possible.

---

## Contributing

Open a PR with a new project directory. Include a short `README` inside the directory describing what was built and any relevant one-shot prompt used.
