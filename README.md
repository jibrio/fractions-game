# Cool Fractions

A single-file HTML5 web game that teaches 9-year-olds about fractions in a
playful, hands-on way. No build step, no dependencies, no server — just open
`index.html` in any modern browser (works with mouse on desktop and touch on
mobile).

## Play

Open `index.html` in a browser, or host it (see *GitHub Pages* below) and play
from the URL.

## What's inside

- **20 levels** that ramp from halves up to fifths, eighths, equivalence and
  ordering, with the puzzle type changing level to level.
- **9 puzzle mechanics:** slice an apple, break a chocolate bar into equal
  parts, shade a fraction, fill a glass, place a fraction on a number line,
  build one whole, pick the matching fraction, order fractions smallest →
  biggest, and find two pieces that make a whole.
- **Charming, diverse cartoon characters** drawn in SVG.
- **Synthesised audio** (sound effects + a level-complete celebration) via the
  Web Audio API — no audio files, with a mute toggle.
- Correct answers are **shuffled each load** so position never gives the answer
  away.

## Tech notes

- Everything lives in one self-contained `index.html`: HTML, CSS, SVG art and
  vanilla JavaScript. No external libraries.
- A small "mechanic plugin" architecture (`MECHANICS` registry + data-driven
  `LEVELS` array) makes it easy to add new puzzle types and levels.

## GitHub Pages (optional, free hosting)

After pushing to GitHub: repo **Settings → Pages → Build from branch → `main` /
root**. The game will be live at `https://<your-user>.github.io/<repo>/`.
