# Snake Game - Python with Tkinter

## Introduction
This is a simple Snake Game implemented in Python using the Tkinter library. The game features a snake that moves around the screen, eating food, growing longer, and accumulating points. The game ends when the snake collides with the edges of the game window or with itself.

## How to Play
- Use the **arrow keys** (`Up`, `Down`, `Left`, `Right`) to control the direction of the snake.
- The goal is to eat the red food, which causes the snake to grow and your score to increase.
- If the snake collides with the walls or its own body, the game ends.
- You can restart the game by pressing the **"Restart"** button.

## Features
- Real-time snake movement using Tkinter's `after()` method.
- **Collision detection** for walls and the snake's own body.
- **Scoreboard** that updates when the snake eats food.
- A **Restart** button to reset the game after a game over.

## Game Configuration
- **Game Window Size**: 700x700 pixels
- **Snake Color**: Green (`#00FF00`)
- **Food Color**: Red (`#FF0000`)
- **Background Color**: Black (`#000000`)
- **Snake Speed**: 50ms per step
- **Snake Initial Size**: 3 body parts

## Controls
- Arrow Keys for movement:
  - **Up**: Move the snake upward.
  - **Down**: Move the snake downward.
  - **Left**: Move the snake left.
  - **Right**: Move the snake right.

## Requirements
- Python 3.x
- Tkinter (included with Python standard library)

## How to Run the Game
1. Save the code in a file with a `.py` extension.
2. Run the Python file using the command:  
   ```bash
   python snake.py
