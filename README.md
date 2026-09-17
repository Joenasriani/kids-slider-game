# Sector Glow: Cyber-Extract

Sector Glow: Cyber-Extract is a 3D sliding-block path-clearing puzzle developed within the same multi-game interactive children’s edutainment activation in the UAE as the other `kids-*` game repositories.

## Game structure

Each level uses a 6×6 grid containing a red horizontal core unit and multiple blocking units. Blocks move only along their configured horizontal or vertical orientation.

**select block → slide along permitted axis → reposition blockers → clear the exit row → move the red core unit through the exit → advance sector**

The game counts moves for the current level and displays the completed level’s operation count on extraction. Authored level layouts are stored directly in `index.html`.

## Controls and persistence

- pointer/touch interaction selects and moves puzzle blocks;
- resetting restarts the current level;
- local browser storage retains progress;
- `Reset All` clears stored progress and returns to the first level;
- completing a level advances through the authored level set.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Repository scope

The complete game is contained in `index.html` and uses Three.js plus browser audio generation and local storage.

No live public deployment is verified for this repository in the current audit.

`index.html` is preserved as the game artifact. Documentation must not alter level layouts, block dimensions/orientations, collision rules, movement, exit conditions, move counting, local progress, controls, camera behavior, audio, visuals or runtime behavior.
