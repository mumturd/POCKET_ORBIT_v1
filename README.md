# Pocket Orbit

A compact browser arcade game: collect golden stars, dodge asteroids, and beat your personal best.

## Play locally

Open `index.html` in Safari, Chrome, or Firefox. No installation or build step is required.

For a local web server, run this from the project folder:

```sh
python3 -m http.server 5173
```

Then visit http://localhost:5173.

## Controls

- Left / Right arrows or A / D: move
- Move the pointer over the play area: steer with a mouse or trackpad
- Space: start, pause, or resume
- P or Escape: pause or resume
- Restart button: begin a new run

Golden stars earn 10 points. You have three lives, and the game gets faster over time. Your best score is saved in your browser when local storage is available. Leaving the window pauses the game.

## Project layout

- `index.html`: the complete game, including styles and JavaScript
- `.gitignore`: excludes common local files

The game uses HTML Canvas and has no external dependencies or network requests.

## Development

Edit `index.html` and reload the browser. Check starting, movement, star collection, collisions, pause/resume, restart, best-score persistence, and layout in a small window before committing changes.
