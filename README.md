# Snake Game

This is a simple Snake Game implemented using Python and Pygame. The objective of the game is to eat as many apples as possible without running into the snake's own body.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Gameplay](#gameplay)
- [Controls](#controls)
- [Contributing](#contributing)

## Features
- Classic Snake Game mechanics
- Randomly spawning apples
- Increasing difficulty as the snake grows
- Score tracking
- Background music while playing
- Sound effects for eating apples and game over events
- High score tracking
- Boundary wrapping (snake can move through the edges and appear on the opposite side)

## Installation
1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
2. Install Pygame using pip:
    ```bash
    pip install pygame
    ```
3. Clone this repository:
    ```bash
    git clone https://github.com/AayushJoshiCCTECH/SnakeGame.git
    ```
4. Navigate to the project directory:
    ```bash
    cd snake-game
    ```
5. Place the following sound files in the same directory as the game script:
   - `eat_sound.wav`
   - `game_over_sound.wav`
   - `background_music.mp3`

## Usage
To start the game, run the `snake_game.py` script:
```bash
python snake_game.py
```
## Gameplay
- **Objective**: The main objective is to eat as many apples as possible to grow your snake and achieve a high score.
- **Score**: Each apple increases the score by 10 points.
- **Speed**: The snake's speed increases every 50 points.
- **Game Over**: The game ends if the snake crashes into itself. The game over sound will play, and you will have the option to play again or exit.

## Controls
- **Arrow Keys**: Use the Up, Down, Left, and Right arrow keys to control the direction of the snake.
- **Esc Key**: Press the Escape key to exit the game.
- **Y Key**: Press the 'Y' key to play again after the game is over.
- **N Key**: Press the 'N' key to exit the game after the game is over.

## Contributing
If you would like to contribute to this project, please fork the repository and create a pull request with your changes.
