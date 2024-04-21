# Battleships Game

This JavaScript program implements a simple Battleships game where the player tries to sink all the ships on the board by guessing their locations.

## Usage

1. **Open the HTML file**: Open the HTML file containing the JavaScript code in a web browser.

2. **Game Setup**: The game will automatically initialize with a 10x10 board containing one Battleship (size: 5) and two Destroyers (size: 4 each). The ships are randomly placed on the board.

3. **Playing the Game**:
   - The player will be prompted to enter coordinates to target a location on the board (e.g., A5).
   - Enter the coordinates in the format `Letter` `Number`, where the letter represents the column (A-J) and the number represents the row (0-9).
   - After each guess, the program will display whether it's a Hit, Miss, or if the player has already targeted that location.
   - Continue guessing until all the ships are sunk.

## Features

- **Random Ship Placement**: Ships are randomly placed on the board, ensuring a different game experience each time.
- **Interactive Gameplay**: The player can input coordinates via prompts and receive feedback on their guesses.
- **Win Condition**: The game ends when all the ships are successfully sunk.

## Gameplay Controls

- **Input**: Enter coordinates when prompted to target a location (e.g., A5).
- **Output**: The program will display messages indicating the result of each guess (Hit, Miss, or Duplicate).

## Game Logic

- **Ship Placement**: Ships are placed either horizontally or vertically on the board, ensuring they do not overlap.
- **Targeting**: The player's guesses are checked against the board, and if a ship is hit, it will be marked as sunk when all its segments are targeted.

## Development Environment

- **Environment**: The game can be played directly in a web browser with JavaScript support.
