# Tic-Tac-Toe Game 🎮

A simple and interactive Tic-Tac-Toe game built with React, designed for two players to enjoy the classic game on a 3x3 board. The app dynamically checks for winners and ties, providing a seamless and fun experience.

---

## Features ✨

- **Two-player gameplay**: Players alternate turns, placing their symbols (X or O) on the board.
- **Win detection**: Automatically checks for winning patterns after each move.
- **Tie detection**: Alerts when the board is full and no winner exists.
- **Dynamic updates**: Uses React's state to update the board in real-time.
- **Reset functionality**: Reset the board to start a new game with a single click.

---

## Technologies Used 💻

- **React**: Frontend framework for building a dynamic user interface.
- **CSS**: Styling the board and game components.
- **JavaScript**: Game logic and state management.

---

## Project Structure 🗂️

The file structure is as follows:

```
Tic-Tac-Toe/
├── public/
├── src/
│   ├── components/
│   │   └── Square.js      # Square component for individual cells
│   ├── App.js             # Main game logic and board rendering
│   ├── Patterns.js        # Contains winning patterns for the game
│   ├── App.css            # Styling for the app
│   └── index.js           # Entry point of the app
├── package.json           # Project dependencies and scripts
└── README.md              # Documentation
```

---

## How to Run Locally 🖥️

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Nimasaghi-dev/tic-tac-toe.git
   cd tic-tac-toe
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Application**:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`.

---

## Gameplay Instructions 🎲

1. The game starts with player O.
2. Players take turns clicking on empty squares to place their symbol.
3. The game announces the winner when one player gets three symbols in a row (horizontal, vertical, or diagonal).
4. If all squares are filled without a winner, the game declares a tie.
5. The game resets automatically after each round or when the "Reset" button is clicked.

---

## Screenshots 📸
![](src/assets/screenShots/Screenshot%202024-12-22%20at%2018.58.35.png)
![](src/assets/screenShots/Screenshot%202024-12-22%20at%2018.58.14.png)
