# DeepSnake

A silly 3D snake game made with Three.js.

The premise: a state-of-the-art neural network trained on exactly one snake.
Eat donuts, avoid walls, and try not to eat yourself.

## Controls

- Arrow keys or `WASD` to turn
- On phones, use the on-screen arrow pad, or swipe
- `Space` / `Enter` to restart after a crash

## Run locally

```bash
python3 -m http.server
```

Then open <http://localhost:8000/>.

Three.js is loaded from a pinned jsDelivr CDN, so the page has no build step.
