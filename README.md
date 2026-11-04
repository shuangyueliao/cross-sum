# Cross Sum

A free, single-file HTML5 kakuro-style number crossword. Fill every white cell
with 1–9 so that each horizontal and vertical run of white cells contains no
repeated digit and adds up to the clue printed on its diagonal black cell
(top-right = column clue, bottom-left = row clue).

Play: https://shuangyueliao.github.io/cross-sum/

## Features

- 30 procedurally generated levels, every one verified to have exactly one
  solution (constraint propagation + backtracking solution counter)
- Three tiers: Easy (5×5), Medium (7×7), Hard (9×9), 10 levels each
- Pencil mode for candidate notes, 3 hints per level, instant error checking
- Timer with per-level best times saved locally
- Newspaper-style visuals: paper texture, serif digits, diagonal clue cells,
  green flash on correct entries, red flash on errors
- Touch + mouse + keyboard input (arrows move, 1–9 type, P pencil, H hint,
  C check, M mute)
- Procedural graphics (canvas) and synthesized sounds (WebAudio) — zero
  external assets, works offline once loaded
- Portal SDKs load only on their own domains (CrazyGames / GameDistribution);
  standalone builds load nothing external

## Run locally

Open `index.html` in any modern browser, or serve the folder:

```
python3 -m http.server 8000
```

## Tech

Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking, no external
links. Single `index.html`, ~38 KB.
