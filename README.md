# React Tic-Tac-Toe Game

Welcome to the React Tic-Tac-Toe game! This is a simple and fun 2-player game built using React.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Structure](#structure)
4. [Roadmap of Future Improvements](#roadmap-of-future-improvements)
5. [MIT License](#mit-license)

## Installation

1. **Prerequisites:** The project requires [Node.js](https://nodejs.org/) and the [http-server](https://www.npmjs.com/package/http-server) package to be installed.
2. Download or clone the repository on your local machine.
3. Navigate to the project directory in your terminal.
4. Install all required packages, including `http-server`:
   ```bash
   npm install -g http-server
   ```

## Usage

1. After installation, run the game with:
   ```bash
   http-server -c-1
   ```
2. This will serve the game on a local server. Open the displayed URL in your web browser.
3. Play the game by clicking on a square. The first player is "X" and the second player is "O". The game will announce the winner once one of the players has won or if it's a tie.

## Structure

- **index.html**: The main HTML document. Contains the root div where our React app will get mounted.
- **styles.css**: Contains styles for the game board, the game buttons, and various game elements.
- **tictactoe.jsx**: Contains the React components for the game. This includes:
  - **Game Component**: The main wrapper component.
  - **Board Component**: Represents the Tic-Tac-Toe board.
  - **Square Component**: Represents a single square on the board.
  - Utility functions for game mechanics.

## Roadmap of Future Improvements

1. **AI Integration**: Introduce a single-player mode where users can play against a computer AI.
2. **Responsive Design**: Ensure the game is playable on tablets and mobile devices.
3. **Themes & Skins**: Allow users to customize the appearance of the game board and symbols.
4. **Player Profiles**: Implement a feature where users can create profiles, track their wins, and see statistics.
5. **Multiplayer Online Mode**: Allow users to play against friends or random opponents online.
6. **Sounds and Animations**: Add sound effects for moves, wins, and a tie. Also, add subtle animations for an enhanced user experience.
7. **Undo Move**: Allow players to undo their last move.
8. **Game History**: Display a history of moves for each game.
9. **Difficulty Levels**: For the AI mode, have varying difficulty levels from beginner to expert.

## MIT License

This project is licensed under the terms of the MIT license. For more details, see the [LICENSE](#) file (assuming you have a LICENSE file in your repository).
