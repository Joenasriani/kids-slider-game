# Sector Glow: Cyber-Extract

Sector Glow: Cyber-Extract is a 3D sliding-block path-clearing puzzle.

## How it plays

Each level uses a 6×6 grid containing a red horizontal core unit and multiple blocking units. Blocks move only along their configured horizontal or vertical axis.

**select block → slide along permitted axis → reposition blockers → clear exit row → move red core through exit → advance sector**

The game counts moves for the current level and reports the completed level's operation count.

## Controls and progression

- pointer/touch input selects and moves blocks;
- Reset restarts the current level;
- local browser storage retains progress;
- Reset All clears stored progress and returns to Level 1;
- completing a level advances through the authored level set.

## Implementation

The complete game is contained in `index.html`.

It uses Three.js for the 3D board, browser-generated audio, and local storage for progression.

## Event activation

This game was developed as one module in a multi-game interactive children’s edutainment activation in the UAE.

Event production: [Peach Society](https://peach-society.com/) — Dubai-based event and experiential production company.
