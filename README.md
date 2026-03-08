# Double Pendulum Simulation

A physics-based double pendulum simulation that visualizes chaotic motion using Matter.js.

二重振り子のカオス的な動きを可視化する物理シミュレーションWebアプリ。

## Quick Start

```bash
docker compose up -d
```

Open http://localhost:8888 in your browser.

## Features

- Real-time double pendulum physics simulation
- Trail visualization with gradient fade effect
- Parameter adjustment (length, mass, angle, gravity)
- Playback controls (pause, resume, reset, speed)
- Energy display (kinetic, potential, total)
- Responsive design for portrait mode

## Controls

| Parameter | Description |
|-----------|-------------|
| L1, L2 | Length of each pendulum arm |
| m1, m2 | Mass of each pendulum bob |
| θ1, θ2 | Initial angle of each pendulum |
| Gravity | Gravitational acceleration |
| Speed | Simulation speed multiplier |

## Technology Stack

- HTML5 Canvas
- Matter.js (physics engine)
- Vanilla JavaScript

## License

MIT
