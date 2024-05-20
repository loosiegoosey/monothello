# Monothello

## Overview

Monothello is a simple implementation of the classic game of Othello (also known as Reversi) built with Python and Tkinter. The project allows users to play the game through a graphical user interface.

## Features

- Two-player game with Player1 as white pieces and Player2 as black pieces.
- Graphical User Interface (GUI) built with Tkinter.
- Basic game logic and piece management.
- Unit tests for testing the initialization phase of the game.

## Installation Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Yuriy/monothello.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd monothello
   ```

3. **Install Dependencies:**
   
   Ensure you have `tkinter` installed. If not, you can install it using the following command:
   
   ```bash
   sudo apt-get install python3-tk
   ```

4. **Run the Application:**

   To run the game, execute the following command:

   ```bash
   python monothello.py
   ```

## Usage Examples

To start the game, run the `monothello.py` file. This will launch the GUI where you can start a new game, place pieces, and play Othello.

```bash
python monothello.py
```

Here's a simple example of how to initiate the GUI and game logic:

```python
from monothello import Application

if __name__ == "__main__":
    app = Application()
    app.mainloop()
```

## Code Summary

The project consists of the following key files:

1. **`engine.py`:**
   - Defines different types of game pieces (`Piece`, `EmptyPiece`, `Player1Piece`, `Player2Piece`).
   - Contains the core game logic (to be expanded).

2. **`monothello.py`:**
   - Implements the GUI using Tkinter.
   - Manages the game's main window and user interactions.

3. **`tests.py`:**
   - Contains unit tests for ensuring the correct initialization of the game board and pieces.

## Contributing Guidelines

We welcome contributions! Please adhere to the following guidelines:

1. **Fork the Repository:**
   
   Navigate to the [GitHub repository](https://github.com/Yuriy/monothello) and click "Fork" to create a copy of the repository on your account.

2. **Create a Branch:**

   Create a new branch for your feature or bug fix:
   
   ```bash
   git checkout -b feature-name
   ```

3. **Make Changes and Commit:**

   Make your changes and commit them with a meaningful commit message:
   
   ```bash
   git commit -m "Description of the feature or fix"
   ```

4. **Push to GitHub:**

   Push your changes to your forked repository:
   
   ```bash
   git push origin feature-name
   ```

5. **Create a Pull Request:**

   Open a pull request from your forked repository to the original repository. Provide a clear description of your changes.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software under the terms of the MIT License.

---

Feel free to contribute, report issues, or suggest improvements to make Monothello a more enjoyable game!