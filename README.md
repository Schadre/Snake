# 🐍 The Snake Game

Welcome to the Snake Game! This is a simple implementation of the classic Snake game using Python and the Tkinter library. 

## Features
- Classic Snake gameplay.
- Use arrow keys to control the snake.
- Simple graphics and easy-to-understand code.

---

## Getting Started
Follow these steps to run the Snake Game on your machine:

### Prerequisites
1. **Install Python**: Ensure Python 3 is installed on your system.
   - Download it from [python.org](https://www.python.org/).
2. **No additional libraries required**: The game uses the built-in `tkinter` module, which comes with Python.

### Running the Game
1. **Download the project**:
   - Clone this repository or download the ZIP file.
   ```bash
   git clone https://github.com/Schadre/Snake.git
   ```
   Extract the ZIP file if downloaded.
2. **Run the game**:
   ```bash
   python main_snake.py
   ```

---

## How to Play
1. Use the **arrow keys** on your keyboard to move the snake:
   - **Up**: Move up.
   - **Down**: Move down.
   - **Left**: Move left.
   - **Right**: Move right.
2. Eat the red tile (food) to grow longer and increase your score.
3. Avoid running into the walls or yourself. If you do, the game is over.

---

## Code Overview
The game is structured into the following key components:

1. **Tile Class**:
   - Represents a grid tile with an `x` and `y` coordinate.

2. **Main Functions**:
   - `change_direction(e)`: Handles snake direction changes based on user input.
   - `move()`: Updates the snake’s position and checks for collisions.
   - `draw()`: Handles the game rendering, such as drawing the snake, food, and game over message.

3. **Game Loop**:
   - The game uses `window.after(100, draw)` to create a loop that updates the game every 100 milliseconds.


---

Have fun coding and playing!

