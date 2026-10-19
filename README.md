# Walled

A two-player strategy board game that runs in the browser. Race your pawn to the far side of a 9×9 board, and use walls to block your opponent. You can never seal anyone in completely.

**Play it:** open `index.html` in any browser, or play online at https://altmarf4.github.io/Walled/

## Features

- Play against the computer (easy, medium, or hard) or against a friend on the same device
- Undo, move history, and light and dark themes
- Works with a mouse or a touch screen
- One self-contained file with no dependencies or build step

## Rules

- Blue starts at the bottom and Red at the top. Blue moves first.
- On your turn, either move your pawn one square or place one wall. Each player has 10 walls.
- A wall is two squares long. Walls can't overlap or cross.
- A wall may never cut off a player's last route to their goal row.
- If the pawns are face to face, you can jump over the other pawn. If a wall or the edge of the board is behind it, step diagonally instead.
- The first player to reach the opposite row wins.

## Controls

- Click a highlighted square to move.
- Point at the groove between squares to preview a wall, then click to place it.
- At a crossing, press `R` or right-click to rotate the wall.
- On a touch screen, tap once to preview a wall and tap again to place it.
- `Ctrl+Z` / `Cmd+Z` undoes a move.

## Hosting on GitHub Pages

In the repository, go to **Settings → Pages**, set **Source** to "Deploy from a branch", pick `main` and `/ (root)`, and save. The game will be live at `https://altmarf4.github.io/Walled/`.
