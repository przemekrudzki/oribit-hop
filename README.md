# Orbit Hop

A small space arcade game built with HTML, CSS, and JavaScript. Launch a tiny moon from one planet's orbit to the next, collect stars, and see how far you can go.

## Play

**[Play Orbit Hop online](https://przemekrudzki.github.io/oribit-hop/)**

Open `index.html` in a modern browser. No installation, dependencies, or build step is required.

Click **PLAY**, then tap, click, or press **Space**, **Arrow Up**, or **Enter** to launch. Your moon flies along a tangent; time your jump to reach another planet's orbit.

- The first orbit is safe and includes a launch cue.
- The dotted aiming preview highlights a predicted target.
- Later orbits shrink. Watch the countdown ring and launch before crashing.
- The camera looks ahead to show your next destination.
- A narrow assisted catch zone helps with near misses.
- Routes mix wide diagonal jumps, short recovery hops, and star-rich detours.
- Reach new planets for one point. Consecutive quick hops add up to three bonus points.
- Stars are worth one point in orbit and two points in flight, with floating score feedback.
- Planets spread in different directions, and some move as difficulty increases.
- Your best score is saved locally in your browser.

Use **AGAIN** after a game ends to restart. Use the **Pause** button, **P**, or **Escape** to pause and resume. The game pauses automatically when the tab loses focus and waits for you to resume. Use **Mute** or **M** to toggle audio; your choice is remembered.

The online version is served by GitHub Pages from the `main` branch.

## Development

All markup, styling, rendering, game logic, and synthesized audio live in `index.html`. Graphics use Canvas 2D, sounds use the Web Audio API, and scores use `localStorage`.

For an optional local server:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.
