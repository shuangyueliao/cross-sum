# Cross Sum — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

A kakuro-style number crossword with a newspaper feel. Fill each white cell
with 1–9: digits never repeat in a run and every run must add up to its clue.
30 hand-verified unique-solution puzzles across three grid sizes. Pencil
notes, hints, error check, and best-time tracking included.

## Details

- Genre: Puzzle / Logic / Numbers
- Controls: Touch or mouse (tap a cell, tap a number). Keyboard: arrow keys
  move, 1–9 type, Backspace erases, P pencil, H hint, C check, M mute.
- Features: 30 levels in three tiers (5×5, 7×7, 9×9), every level verified to
  have exactly one solution; pencil-mode candidates; 3 hints per level; check
  button with instant feedback; per-level best times saved locally; mute.
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5, no external
  assets, no tracking, no external links. Works offline once loaded.

## Tags

kakuro, cross sum, number puzzle, logic, sudoku-like, casual, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly), mobile touch + desktop keyboard
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload `cross-sum-gd.zip` (contains only index.html). GD SDK injects ads on
  gamedistribution / gd.games domains; standalone runs load no SDK.

## itch.io
- Upload `cross-sum-itch.zip`, mark "This file is playable in browser",
  entry file: index.html, viewport fits width (square canvas), kind: html.
- Pricing: $0 (donations optional)
