# Matrix Quiz

A browser-based quiz for practicing matrix addition and subtraction.

## Features

- Randomized questions with text or image-based choices
- Ten questions per round with a progress indicator and score
- High scores saved in the browser using `localStorage`

## Run locally

From the repository root, start a local static server:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000> in a browser.

## Project structure

- `index.html` — start screen
- `game.html` — quiz
- `end.html` — result screen
- `highscores.html` — local high-score list
- `questions.json` — question data
- `css/` and `js/` — styles and game logic

High scores are stored in the current browser and are not synced between devices.
