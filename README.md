# Retro Snake Game (C++)

A lightweight, classic Snake game built from scratch using **C++** and the **Raylib** library. This project focuses entirely on clean logic and object-oriented architecture without relying on external visual sprites.

## 🚀 Features & Technical Highlights

- **Object-Oriented Architecture:** Modular design utilizing encapsulated `Snake`, `Food`, and `Game` classes to handle system rendering and state updates independently.
- **Optimized Data Structures:** Managed the snake's growing body using a Double-Ended Queue (`std::deque`), enabling efficient $O(1)$ updates for movement handling.
- **Smart Spawning Mechanics:** Implemented real-time coordinate verification against the player's current body array to prevent food from spawning on top of the snake.
- **Collision Detection:** Programmed frame-independent boundary checks and self-intersection logic for seamless game-over resets.
- **Audio Integration:** Real-time audio feedback for interaction cues (eating food, hitting walls).

## 🛠️ Prerequisites & Dependencies

- C++17 compiler or later
- [Raylib Library](https://www.raylib.com/)

## 🎮 How to Play
- Use the **Arrow Keys** to change directions.
- Eat the food to grow your snake and increase your score.
- Avoid crashing into the outer white borders or your own tail!
