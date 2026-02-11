# Income Plinko Lab

Interactive classroom web app for teaching income distribution with a plinko-style simulation.

Live demo: https://nealcaren.github.io/income-plinko/

## What It Does

- Dollars flow continuously through pegs and levers.
- Students can build and tune a stable routing system in real time.
- Modes:
  - `Flat`
  - `Fair`
  - `Actual U.S.`
  - `Free Play` (no target)
- Evaluation uses a rolling window of the last 100 balls (stability over time).

## Controls

- Draw lever: drag on blank board space.
- Move lever: drag a lever body.
- Rotate lever: drag a lever endpoint.
- Add/delete objects: right-click or long-press on board.
- Extra options: click `...` (Help, Reset Samples, Reset Board).

## Run Locally

No build step is required.

1. Open `index.html` in a browser.

Optional local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Notes

- `_draft/` is ignored by git and not published.
- Main app files:
  - `index.html`
  - `styles.css`
  - `app.js`
