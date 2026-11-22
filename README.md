# processing-visual-sketches

Two small Processing sketches that animate bouncing and drifting circles.

## Features

- `bouncing_ball`: one white circle bouncing off the window edges at a random speed.
- `network_sketch`: press a key to switch between three animations:
  - `a`: a single bouncing circle.
  - `s`: 35 circles joined by 300 lines, drifting slowly.
  - `d`: 30 circles that bounce around and draw a line between any two closer than 120 px.
- `fifa.csv`: a 32-row table of FIFA World Cup team standings (position, team, games, W/D/L, goals, points). It is not read by either sketch yet.

## Tech stack

Processing (Java mode).

## Structure

```
bouncing_ball/bouncing_ball.pde
network_sketch/network_sketch.pde
fifa.csv
```

## Run

1. Install Processing from https://processing.org.
2. Open a `.pde` file (the folder name must match the file name, as it does here).
3. Press Run. For `network_sketch`, click the window and press `a`, `s` or `d`.

## Status

Despite the old repository name, there is no real data visualization yet: the FIFA data is unused. The sketches were not run during cleanup (no Processing install), only a variable-name bug in mode `d` was fixed by reading the code.

## License

MIT
