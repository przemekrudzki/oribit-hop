# Orbit Hop

A small space arcade game built with HTML, CSS, and JavaScript. Launch a tiny moon from one planet's orbit to the next, collect stars, and see how far you can go.

## Play

Open `index.html` in a modern browser. No installation, dependencies, or build step is required.

Click **PLAY**, then tap, click, or press **Space**, **Arrow Up**, or **Enter** to launch. Your moon flies along a tangent; time your jump to reach another planet's orbit.

- The first orbit is safe and includes a launch cue.
- The dotted aiming preview highlights a predicted target.
- Later orbits shrink. Watch the countdown ring and launch before crashing.
- Reach new planets and collect gold stars to earn points.
- Planets spread in different directions, and some move as difficulty increases.
- Your best score is saved locally in your browser.

Use **AGAIN** after a game ends to restart.

## Development

All markup, styling, rendering, game logic, and synthesized audio live in `index.html`. Graphics use Canvas 2D, sounds use the Web Audio API, and scores use `localStorage`.

For an optional local server:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.
