# Snake Game

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Curses](https://img.shields.io/badge/Curses-CLI-00ADD8?style=for-the-badge&logo=gnubash&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

A classic Snake game implemented in Python using the `curses` library for terminal-based gameplay.

## Description

Control a snake to eat food and grow longer while avoiding walls and your own tail. The game ends when the snake collides with the boundaries or itself. Each food item increases your score and the snake's length.

## Requirements

- **Python 3.x** — `curses` library included with Python standard library on Linux/macOS
- **Windows users:** Install `windows-curses` via pip (`pip install windows-curses`)

## How to Run

```bash
git clone https://github.com/spaciousejar/snake-game.git
cd snake-game
python snake.py
```

### Controls

| Key | Action |
|-----|--------|
| Arrow keys / WASD | Move snake |
| Q | Quit game |

## Features

- Classic snake mechanics with increasing difficulty
- Score tracking
- Game-over detection (wall and self collision)
- Terminal-native rendering via curses

## License

MIT
