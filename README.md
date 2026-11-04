# Solitaire

A browser version of Klondike Solitaire, written in plain HTML, CSS and JavaScript in a single file.

Live page: https://isha-jain-123.github.io/solitare/

## Features

- Standard Klondike layout: stock, waste, four foundations and seven tableau piles
- Draw one card at a time from the stock; click the empty stock to recycle the waste pile
- Drag and drop single cards or stacks between piles
- Double-click a card to send it to a foundation automatically
- Undo button and New Game button
- Move counter, timer and score (+15 for moving a card to a foundation, +5 for turning over a tableau card)
- Win screen showing your moves, time and score

## How to play

Build each foundation up by suit from Ace to King. On the tableau, cards are stacked in descending order with alternating colours, and only a King can go into an empty column. You win once all 52 cards are on the foundations.

## Running locally

Open `index.html` in a browser, or use the small server included in the repo:

```bash
python server.py
```

This serves the game at http://localhost:6543.

## Deployment

`.github/workflows/deploy.yml` publishes the game to GitHub Pages on every push to `main`.
