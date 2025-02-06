# Tic Tac Toe Game

This project is a simple Tic Tac Toe game built using React. The implementation follows the official [React tutorial](https://react.dev/learn/tutorial-tic-tac-toe).

## Getting Started

### Prerequisites

- Node.js and npm installed
- Basic knowledge of React

### Installation

1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd tic-tac-toe
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

## How It Works

### Components

The game consists of the following components:

- **Board**: Displays the game board and contains the logic for rendering squares.
- **Square**: Represents a single square in the grid.
- **Game**: Manages the game logic, including turns and history tracking.

### Props

Props are used to pass data between components:

- `Square` receives a `value` prop to display either "X" or "O".
- `Square` also receives an `onClick` function as a prop to handle user interactions.

### State

State is managed in the `Game` component:

- `history`: Tracks the state of the board at each move.
- `stepNumber`: Keeps track of the current move.
- `xIsNext`: Determines whose turn it is.

## How to Play

1. Click on a square to make a move.
2. The game alternates between "X" and "O".
3. The game declares a winner or a draw when conditions are met.
4. Players can view past moves and jump to any previous state.
