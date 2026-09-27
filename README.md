# asteroids
A guided project from Boot.dev's Python back-end curriculum, building a clone of the arcade classic Asteroids.

This project was built as part of the [Build Asteroids using Python and Pygame](https://www.boot.dev/courses/build-asteroids-python) guided project on [Boot.dev](https://www.boot.dev). It walks through making a real-time game with [Pygame](https://www.pygame.org/), covering the game loop, delta time, sprite groups, inheritance, and circle-based collision detection. You pilot a triangular ship through a field of asteroids that drift in from the edges of the screen. Shooting a large asteroid splits it into two smaller, faster pieces, and the smallest ones are destroyed outright. The game ends when an asteroid hits your ship.

## Local Setup

### Prerequisites

- Python 3.12+
- [uv](https://docs.astral.sh/uv/) (used for dependency management in this project)
- A desktop environment that can open a window. On Windows, use [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) (Windows Subsystem for Linux) on Windows 11, whose built-in WSLg support displays Linux GUI apps. macOS and Linux should work without modification.

### 1. Clone the repository

```bash
git clone https://github.com/gamefreak431/asteroids.git
cd asteroids
```

### 2. Install dependencies

```bash
uv sync
```

This installs Pygame 2.6.1 into a local `.venv`.

### 3. Run the game

```bash
uv run main.py
```

## Controls

| Key | Action |
|---|---|
| `W` | Move forward |
| `S` | Move backward |
| `A` | Rotate left |
| `D` | Rotate right |
| `Space` | Shoot (at most once every 0.3 seconds) |

Close the window to quit. Game settings like screen size, ship speed and asteroid spawn rate are in `constants.py`.

## Certificate

[![Boot.dev Build Asteroids using Python and Pygame certificate](https://qvault-webapp-dynamic-assets.storage.googleapis.com/certificates/7f1ec262-c14b-4c4b-8587-ecff7408b4f1.jpeg?v=1763620408)](https://www.boot.dev/certificates/7f1ec262-c14b-4c4b-8587-ecff7408b4f1)
