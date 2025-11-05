# GlobeSweeper

A 3D spherical minesweeper game built with Three.js, featuring a geodesic Goldberg tiling on an icosphere.

## Features

- **Spherical Minesweeper**: Play minesweeper on a 3D sphere with hexagonal/pentagonal tiles
- **Modern UI**: Glassmorphic scoreboard with circular progress indicators
- **Debug Panel**: Comprehensive controls for game settings, visuals, and camera
- **Empty Tiles**: Transparent glass tiles that don't count toward exploration
- **Smart Reveal**: Queue-based cascade reveal system for smooth gameplay
- **Solvability Checking**: Ensures boards are solvable without guessing

## Controls

- **Left Click**: Reveal a tile
- **Right Click**: Flag/unflag a tile
- **Double Click**: Reveal adjacent tiles (if all mines are flagged)
- **Ctrl+Shift+Alt+D**: Toggle debug panel

## Game Settings

- **Tile Density**: Number of subdivisions (affects tile count)
- **Mine %**: Percentage of mines on the board
- **Empty Tile %**: Percentage of transparent empty tiles
- **Initial Reveal %**: Percentage of tiles revealed at game start

## Live Demo

Visit the [live demo](https://ozlphrt.github.io/GlobeSweeper/) to play the game.

## License

MIT License

