# Classic Snake Game

This project is a web-based implementation of the classic Snake game, developed using HTML5, JavaScript, and Tailwind CSS for styling. The game is rendered on a `canvas` element, and players control the snake using the arrow keys. The objective is to eat food, grow the snake, and avoid collisions with the snake's body or the walls.

## Demo

You can try out the game by opening the `index.html` file in your web browser.

![Snake Game Screenshot](screenshot.png)  
_Example screenshot of the Snake game._

## How to Play

1. Use the arrow keys to move the snake:
   - **Up Arrow**: Move up
   - **Down Arrow**: Move down
   - **Left Arrow**: Move left
   - **Right Arrow**: Move right
2. The goal is to eat the red food that appears randomly on the grid.
3. Each time you eat food, your score increases by 10 points, and the snake grows longer.
4. Avoid hitting the walls or your own tail; otherwise, it's game over!

## Features

- Simple, intuitive controls using the arrow keys.
- Dynamic score display.
- Food randomly spawns on the grid.
- Game over alert when the snake hits the wall or itself.
- Automatic restart after a game over.

## Technologies Used

- **HTML5**: Provides the basic structure and canvas element for rendering the game.
- **JavaScript**: Implements the game logic, controls, and rendering.
- **Tailwind CSS**: Used for simple, modern styling and responsive layout.

## File Structure

```bash
.
├── index.html    # Main HTML file with embedded JavaScript and Tailwind CSS
└── README.md     # Project documentation
```

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/snake-game.git
   ```
2. Open the `index.html` file in your web browser to start playing the game. No additional installation or dependencies are required.

## Customization

- You can modify the grid size, speed, or color scheme by tweaking the `gridSize`, `tileCount`, and interval in the `setInterval()` function inside the JavaScript code.
  
## Contributing

Feel free to submit issues or pull requests if you'd like to improve the game or add new features!

## License

This project is licensed under the MIT License.