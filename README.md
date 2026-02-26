# Chugger

A minimal hydration tracker that lives in a single HTML file.

## How to run

Open `index.html` directly in any browser. No build step, no server required.

## Tech stack

- Bootstrap 5 (CDN) — layout and components
- Vanilla JS — all interaction logic
- Single HTML file — no bundler, no dependencies to install

## Features

- Track daily water (or juice/coke) intake glass by glass
- Visual glass that empties as you drink
- Progress bar showing glasses completed toward the daily goal
- **Daily goal: 8 glasses**, resets automatically at midnight
- Progress persists across page refreshes via `localStorage` (keyed by date)
- Bubble animations in the glass
