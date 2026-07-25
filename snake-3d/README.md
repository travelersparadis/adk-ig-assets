# Snake 3D

A polished 3D take on the classic Snake game, built with [Three.js](https://threejs.org/).
Everything lives in a single self-contained `index.html` — no build step.

## Play

Open `snake-3d/index.html` in any modern browser. That's it.

> Three.js is loaded from a CDN via an import map, so the first load needs an
> internet connection. To run fully offline, download `three.module.js` locally
> and point the import map at it.

## Controls

| Action | Keys |
| ------ | ---- |
| Steer  | Arrow keys or `W` `A` `S` `D` |
| Pause  | `Space` or `P` |
| Restart | `Enter` (on the menu / game-over screen) |
| Mobile | Swipe in any direction |

## Features

- Angled 3D board with soft shadows, glowing walls, and a checkerboard floor
- Snake that speeds up as you eat, with alternating-color body segments
- Floating, spinning food orb with a pulse-on-eat effect
- Score + persistent high score (saved to `localStorage`)
- Wall and self-collision detection with distinct game-over messages
- Responsive layout and touch swipe controls for phones
