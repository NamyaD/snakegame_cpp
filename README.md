# 🐍 Snake King - Snake Game in C++

A simple console-based Snake Game built using C++. The player controls the snake using keyboard keys, collects fruits to increase the score, and the game ends when the snake collides with its own body.

## 🚀 Features

- Console-based interactive gameplay
- Real-time snake movement
- Keyboard controls using `W`, `A`, `S`, `D`
- Random fruit generation
- Score tracking system
- Snake tail growth after eating fruit
- Self-collision detection
- Wall wrap-around movement
- Game-over screen with final score

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows%20API-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Console%20Application-000000?style=for-the-badge&logo=windows-terminal&logoColor=white" />
  <img src="https://img.shields.io/badge/Game%20Logic-FF6F00?style=for-the-badge&logo=gamemaker&logoColor=white" />
</p>

## 🎮 Controls

| Key | Action |
|---|---|
| `W` | Move Up |
| `A` | Move Left |
| `S` | Move Down |
| `D` | Move Right |

## 📚 Concepts Used

- C++ Functions
- Loops and Conditional Statements
- Arrays for snake tail tracking
- Enum for direction handling
- Real-time keyboard input using `_kbhit()` and `getch()`
- Console screen clearing using `system("cls")`
- Game loop implementation
- Collision detection
- Random fruit generation
- Score tracking

## 🧠 How It Works

- The snake starts from the center of the console board.
- A fruit is generated at a random position.
- The player controls the snake using `W`, `A`, `S`, and `D`.
- When the snake eats the fruit, the score increases by 10.
- The snake's tail length increases after eating fruit.
- The game ends when the snake collides with its own body.
- If the snake touches the wall, it appears from the opposite side.

