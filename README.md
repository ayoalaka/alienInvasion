# alienInvasion
Alien Invasion is a classic arcade-style game implemented in Python using the Pygame library. The game involves controlling a spaceship to shoot down invading aliens while avoiding their attacks.

#### Overview
Alien Invasion is a classic arcade-style game implemented in Python using the Pygame library. The game involves controlling a spaceship to shoot down invading aliens while avoiding their attacks.

#### Installation
To run Alien Invasion, you need to have Python installed on your system along with the Pygame library.

1. **Python**: You can download Python from [python.org](https://www.python.org/downloads/).
2. **Pygame**: Install Pygame using pip:
    ```
    pip install pygame
    ```

#### Running the Game
To start playing Alien Invasion, simply run the `alien_invasion.py` file using Python:
```
python alien_invasion.py
```

#### Controls
- **Movement**: Use the left and right arrow keys to move the spaceship.
- **Shooting**: Press the spacebar to shoot bullets at the aliens.
- **Quit**: Press 'Q' to quit the game at any time.

#### Game Mechanics
- **Aliens**: Aliens move across the screen from right to left and back again. They also move downward once they reach the screen edges.
- **Ship**: The player controls a spaceship at the bottom of the screen. The ship can move horizontally and shoot bullets at the aliens.
- **Bullets**: Bullets are fired from the spaceship towards the aliens. They disappear when they collide with an alien or reach the top of the screen.
- **Score**: Players earn points by shooting down aliens. The score increases with each successful hit.
- **Level**: As the player progresses, the game becomes more challenging by increasing the speed of aliens and the number of aliens in each wave.
- **Lives**: Players start with a limited number of lives (ships). When hit by an alien's attack, the player loses a life. The game ends when all lives are lost.

#### Objective
The objective of the game is to earn as many points as possible by shooting down aliens while avoiding their attacks. The game continues until all lives are lost.

#### Features
- Responsive spaceship controls.
- Dynamic alien movement and behavior.
- Bullet shooting mechanics.
- Score tracking and high-score display.
- Multiple levels of increasing difficulty.
- Play button to start or restart the game.
- Fullscreen mode (commented out in the code).

#### Acknowledgments
Alien Invasion is inspired by the classic arcade game "Space Invaders" and is created using Pygame, an open-source library for making multimedia applications like games.
