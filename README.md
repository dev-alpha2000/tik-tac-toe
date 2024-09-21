## Overview

This project is a Tic Tac Toe Game built using React. It is a simple two-player game where playe## rs take turns marking spaces on a 3x3 grid. The goal is to align three of their marks either vertically, horizontally, or diagonally before their opponent.

## Features

Two-Player Gameplay: Play alternates between two players (X and O).

Game Logic: The game detects a winner or a tie based on the current game state.

Restart Option: Players can reset the board to start a new game after a win or a tie.

Responsive Design: The game is playable on both desktop and mobile devices with a simple and clean interface.

## Installation
To run this project locally, follow these steps:

Clone the repository:

bash code

git clone https://github.com/yourusername/tic-tac-toe-app.git
cd tic-tac-toe-app

Install the dependencies:

bash code
npm install
Start the development server:

bash code
npm start
The app will be available at http://localhost:3000.

## Usage

Start the Game: The game starts when the page loads.

Player Turns: Player X always goes first, followed by Player O. Click on any available square to mark it.

Win or Tie: The game will detect a win (three marks in a row) or a tie (all squares filled with no winner).

Restart: After a game ends, you can restart the game to play again by clicking the reset button.


## Example
When you open the app:

Players can click on any empty square to mark it with "X" or "O".

The game will automatically detect a winner or a tie and display the result.

After the game ends, a reset button allows players to start a new round.

## Dependencies

React: Frontend framework for building the UI.

State Management: Manages game state, player turns, and win/tie detection using React’s state and hooks.

CSS for Grid Layout: Uses CSS to create the board and manage responsive layout.

