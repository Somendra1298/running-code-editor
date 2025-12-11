# running-code-editor
# Running Code Editor — Visualisation

A small browser demo that turns code characters into animated "runners" on a full-screen canvas,
with a contenteditable CodeJar editor (Prism highlights). Bugs can spawn and chase characters.

## Features
- Lightweight CodeJar editor with PrismJS syntax highlighting (JavaScript example).
- Each non-whitespace character becomes a `Runner` object that moves on the canvas.
- `Bug` objects hunt active runners and can "eat" characters.
- Controls: Run, Back to Code, Toggle limbs (hands), Spawn bug.

## How to run locally
1. Open this folder in Visual Studio Code.
2. Use the **Live Server** extension (recommended) or:
```bash
# Python 3
python -m http.server 8000
# open http://localhost:8000 in the browser
