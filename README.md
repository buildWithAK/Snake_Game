# 🐍 Snake Game

A classic Snake game built from scratch in Python using the built-in `turtle` graphics library. Control the snake, eat the food, grow longer, and try to beat your highest score without crashing into the walls or yourself!

## Features

* Smooth arrow-key controls (Up, Down, Left, Right)
* Snake grows longer each time it eats food
* Live scoreboard that updates in real time
* Random food spawning within the game boundary
* Collision detection for walls and self-collision
* Automatic game reset after collision
* Persistent high score tracking using a text file
* High score is saved and loaded when the game is restarted

## Demo

(https://drive.google.com/file/d/1biMJ80S2q7wu2Gg-1MftB-3cIr-ZnGLY/view?usp=sharing)

## Tech Stack

* **Python 3**
* **Turtle** — for graphics and rendering
* **Object-Oriented Programming** — Snake, Food, and Scoreboard as separate classes
* **File Handling** — used to store and retrieve the high score

## Project Structure

* `main.py` – Game loop, keyboard controls, and collision logic
* `snake.py` – Snake class: movement, direction control, growth, and reset
* `food.py` – Food class: random food spawning
* `scoreboard.py` – Scoreboard class: current score, high score, and score reset
* `data.txt` – Stores the high score so it is available when the game is restarted

## How to Run

1. Clone this repository

```bash
git clone https://github.com/buildWithAK/Snake_Game.git
```

2. Navigate into the project folder

```bash
cd Snake_Game
```

3. Run the game

```bash
python main.py
```

## Controls

| **Key** | **Action** |
| ------- | ---------- |
| ↑       | Move Up    |
| ↓       | Move Down  |
| ←       | Move Left  |
| →       | Move Right |

## High Score

The game stores the highest score in `data.txt`.

* The current score increases when the snake eats food.
* When the snake hits a wall or itself, the current score is reset.
* If the current score is higher than the saved high score, it is stored in `data.txt`.
* The saved high score is loaded automatically when the game is run again.

## buildWithAK

Built by Aditya as a hobby project.
