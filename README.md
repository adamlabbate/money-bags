# Savings Catch 🐷🌱

A savings-themed catch game, built as a single self-contained HTML file — no build step, no dependencies. Clone it, open it, play it.

**[Play it here](money_bags/savings-catch-game.html)** (or enable GitHub Pages on this repo for a live link)

## How to play

Set a savings goal, then catch falling coins with your saver before they hit the ground. Reach your goal to win.

- **Move:** `←` / `→` or `A` / `D`
- **Coins:** pennies, nickels, dimes, quarters, and rare dollar coins — each worth its real value and falling at its own speed
- **Goal:** pick any target from $1–$500 on the start screen

## Features

- Live savings goal and running-total HUD with a progress bar
- Five coin denominations with weighted rarity and increasing difficulty over time
- Smooth keyboard-driven movement
- A win screen with stats (total saved, coins caught, time)
- Two selectable themes:
  - 🐷 **Piggy Bank** — a bank vault / passbook look (default)
  - 🌱 **Money Tree** — a garden scene where your plant grows and blooms as you save

## Tech

Plain HTML, CSS, and vanilla JavaScript (canvas 2D rendering). No frameworks, no build tools, no external scripts beyond Google Fonts.

## Run it locally

```bash
open money_bags/savings-catch-game.html
```

Or just double-click the file in Finder/Explorer.
