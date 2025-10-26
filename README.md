# 🕹️ Console Tic-Tac-Toe Game

A simple command-line implementation of the classic game **Tic-Tac-Toe** built using Java.

This project demonstrates basic object-oriented programming (OOP) principles in Java, structuring the game logic into classes like `Game`, `Board`, and `Player`.

---

## ✨ Features

* **Two-Player Gameplay:** Standard Tic-Tac-Toe for two players (X and O).
* **Console Interface:** Simple text-based input/output for an easy gaming experience.
* **Automatic Win Detection:** Checks for a win condition (three in a row, column, or diagonal) after every valid move.
* **Draw Detection:** Automatically detects when the board is full and the game ends in a draw.
* **Unit Tests:** Includes JUnit tests for core game functionalities like initial board state and player moves.

---

## 🛠️ Technologies Used

* **Java** (The core programming language)
* **Maven** (For project building and dependency management)
* **JUnit 5** (For unit testing the game logic)

---

## 🚀 Getting Started

### Prerequisites

You'll need to have the following installed on your system:

* **Java Development Kit (JDK) 8 or newer**
* **Maven** (If you intend to build or run the tests)

### How to Play

The game runs in the console and prompts players to make their moves:

1.  When prompted, **enter the row and column** of your desired move, separated by a space.
    * Rows and columns are **0-indexed**, meaning they range from **0 to 2**.
    * Example: Entering `0 0` marks the top-left corner. Entering `1 2` marks the middle row, right column.

2.  The game alternates turns between **'X'** and **'O'** until a player wins or the game ends in a draw.

---

## 🏗️ Project Structure (Relevant Classes)

| Class | Description |
| :--- | :--- |
| `AppTest.java` | Contains the `main` method. This is the **entry point** for the application, handling user input and displaying the board. |
| `Game.java` | Manages the **game flow**, including player turns, making moves, and checking for win/draw conditions. |
| `Board.java` | Represents the **3x3 grid**. Contains logic for placing marks, checking for wins (rows, columns, diagonals), and checking if the board is full. |
| `Player.java` | A simple class to represent a player and their **mark** ('X' or 'O'). |
