# 2D Tank Game

## Task 1

I ensured the tank does not go out of bounds by modifying the tank movement logic in the `updateGame()` function. Since my tank dimensions are not 40x40, I made some adjustments accordingly.

## Task 2

Features I added to the tank game:

1. Added enemy targets that can shoot bullets to attack the player
2. Added visual feedback for: taking damage, invincibility frames, death, and enemy death
3. Added Start, Pause, and Restart buttons

The webpage is now a fun mini-game!

## Description

This is a simple 2D tank game built with **HTML5 Canvas** and **vanilla JavaScript**. You control a tank on a flat battlefield, move it around, and shoot bullets at enemy targets.

The project is intentionally small and dependency‑free, making it ideal for learning basic game loops, keyboard input handling, and simple 2D rendering.

## How to Run

1. Make sure you have a modern web browser (Chrome, Edge, Firefox, etc.).
2. Open the project folder.
3. Double‑click `index.html` to open it in your browser.
4. Click the **Start** button to begin the game.

> Tip: For development, you can also serve the folder with a simple HTTP server (for example, using VS Code Live Server or `npx serve .`) to avoid certain browser security restrictions.

## Controls

### Buttons (UI)
- **Start**: Starts the game or resumes from pause
- **Pause**: Pauses the game
- **Restart**: Resets and restarts the game

### Keyboard
- **Movement**
  - **W**: Move up
  - **S**: Move down
  - **A**: Move left
  - **D**: Move right

- **Shooting**
  - **Space**: Fire a bullet (only when game is started and not paused)

## Game Mechanics

- **Health**: You start with 10 health points
- **Enemies**: An enemy appears 5 seconds after starting the game
- **Invincibility**: After taking damage, you have a brief invincibility period (flashing effect)
- **Game Over**: When health reaches 0, the game ends and shows "GAME OVER"

## Credits

- **Author**: Ning Tang
- **Course / Lab**: CMAA5043 – Lab 5, 2D Tank Game
- **Technologies**: HTML5, CSS, JavaScript (no external libraries)

Feel free to fork, modify, and extend this project as part of your learning or assignments.
