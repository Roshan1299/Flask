# Magical Flask Game

Welcome to the Magical Flask Game, a terminal-based game where you manage chemical flasks and move chemicals between them. The objective of the game is to fill a specified number of flasks with a sealed chemical and win the game.

## Table of Contents

1. [Features](#features)
2. [How to Play](#how-to-play)
3. [Game Rules](#game-rules)
4. [Example Output](#example-output)
5. [License](#license)

## Features

- **Terminal Graphics:** The game uses ANSI escape codes for colorful, visually engaging terminal output.
- **Bounded Stacks & Queues:** The game utilizes bounded stacks and queues to handle the chemical management within the flasks.
- **Multiple Difficulty Levels:** You can choose from different difficulty levels, which impact the number of flasks and chemicals in the game.
- **Interactive Gameplay:** Players select source and destination flasks to transfer chemicals, with real-time visual updates.

## How to Play

- Select a difficulty level (1-4) when prompted. Each difficulty level corresponds to a different set of flask configurations
- The game will display the flasks in the terminal. Each flask can hold up to a specified number of chemicals, and some flasks may already be sealed.
- To make a move, select a source flask (where chemicals are moved from) and a destination flask (where chemicals are moved to). You can type EXIT at any time to end the game.

## Game Rules

- Each flask can hold a limited number of chemicals (typically 3).
- The chemicals are represented by different colors.
- You can transfer chemicals between flasks, but you cannot:
  - Pour chemicals from an empty or sealed flask.
  - Pour into a full or sealed flask.
  - Pour chemicals into the same flask.
- The game ends when the specified number of flasks are sealed with chemicals, or if you exit the game.

## Example Output

## License 

This project is licensed under the MIT License. For more details, please see the [LICENSE](LICENSE) file
