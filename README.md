# Tic-Tac-Toe

This project is a Tic-Tac-Toe game developed with React and TypeScript, and uses Vite for project development and building.
You can check the result here: [TicTacToe](https://tictactoe-34i.pages.dev/)

## Project Structure

The project is organized into several files and directories:

- src/App.tsx: This is the main component of the application.
- src/components/: This directory contains the React components used in the application, including Board.tsx (the game board), Square.tsx (an individual square on the board), Turn.tsx (displays the current turn), and WinnerDialog.tsx (displays a dialog when there is a winner).
- src/constants.ts: This file contains constants used throughout the application.
- src/logic/: This directory contains the game logic, including board.ts (the game board logic) and storage/index.ts (the logic for storing and retrieving the game state).
- src/main.tsx: This is the entry point of the application.

## How to Run the Project

To run this project in your local environment, follow these steps:

1. Clone the repository.
2. Run `npm install` to install the dependencies.
3. Run `npm run dev` to start the Vite development server.
4. Now you can access the URL indicated in the terminal to see the application in action.

## How to Build the Project

To build this project for production, run `npm run build`. This will generate an optimized version of the application in the dist directory.
