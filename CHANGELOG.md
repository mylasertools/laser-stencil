# Changelog

## 0.1.1

- The README covers installing and using the package; development commands moved to CONTRIBUTING.md.
- Fix: on some curved letters the cut outline ran along the outer end of a bridge, so a laser cut the bridge off. Bridges are now removed from the cut as full rectangles that reach past the outline.
- Fix: a counter narrower than the bridge (down to half its width), like the middle of a thin A, now gets a bridge in the chosen direction instead of a diagonal one.

## 0.1.0

First release.

- `stencilSvg`, `stencilPolygons`, `findIslands` and `toPathData`.
- Vertical, horizontal and shortest-angle bridges, 1 to 4 per island, checked across their full width.
- Nested islands, outline-only artwork, physical units and transforms.
- `laser-stencil` CLI with JSON reports and a non-zero exit code for unbridged islands.
- Interactive browser demo.
