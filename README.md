# Four in a Row (Web Edition)

A Connect Four strategy game built with Python and Pygame-CE. Connect four pieces horizontally, vertically, or diagonally against an AI opponent.

Playable locally and in modern web browsers via WebAssembly ([Pygbag](https://pygame-web.github.io/)).

## How to Run Locally

### Prerequisites
- Python 3.10+
- `pip install pygame-ce pygbag`

### Play Locally
```bash
python main.py
```

### Run in Browser Locally
```bash
python -m pygbag main.py
```
Open `http://localhost:8000` in your web browser.

## Controls
- **Mouse Move**: Aim token at a column
- **Mouse Click**: Drop token
- **Escape**: Quit game
