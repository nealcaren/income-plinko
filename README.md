# Trickle Down

Interactive classroom web app for teaching U.S. income and wealth inequality with a plinko-style simulation.

Live demo: https://professorcaren.github.io/trickle-down/

![QR code for Trickle Down](qrcode.png)

## What It Does

- Dollars fall continuously through pegs and levers into quintile bins.
- Students draw and adjust levers to redirect the flow until their distribution matches real U.S. income inequality.
- Score is based on a rolling window of the last 200 balls — consistency matters.
- A 5-minute game timer adds urgency.
- Reaching a score of 85+ in income mode unlocks **Wealth Mode**, which challenges students to recreate the even more extreme U.S. wealth distribution.
- Guided onboarding walks first-time users through the mechanics step by step.

## Controls

- **Draw lever**: drag on blank board space.
- **Move lever**: drag a lever body.
- **Rotate lever**: drag a lever endpoint.
- **Add/delete objects**: right-click or long-press on board.
- **Pause**: view detailed stats comparing your distribution to the target.

## Run Locally

No build step is required.

1. Open `index.html` in a browser.

Optional local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Files

- `index.html`
- `styles.css`
- `app.js`
