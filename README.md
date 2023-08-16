# Learn to Play Flappy Bird using Cartesian Genetic Programming (Evolutionary Computation)

## Features

- Compared with other AI flappy bird projects, this game is **more difficult**. Instead of a fixed number, the horizontal distance between adjacent pipes and the gap are all random within a given range.
- With a small population of size 10, it typically takes **less than 50 generations** to get a *proficient* bird who can fly a very, very long distance before death.
- Support adding a human player (a blue bird) at any time to compete with the AI birds.
- No neural networks are involved (if this can count as a feature).
- It is easy to understand and straightforward to implement Cartesian genetic programming. No extra libraries are needed.

## Installation
### Dependencies:
- Python 3.5 or higher
- [pygame](https://www.pygame.org/news).  Install it with `pip install pygame`
### Download this reposity 
`git clone https://github.com/kir-an/FlappyBird`
or download as a zip file directly.
## How to play
### Run the game
First change your directory into the downloaded *gpFlappyBird*. Then, run the game by 
`python main_entry.py`

### Shortcut keys
- <kbd>Ctrl</kbd>+<kbd>H</kbd>: add a human player (a blue bird) at any time

- <kbd>Space</kbd>, or <kbd>UpArrow</kbd>: flap the human player's bird

- <kbd>Ctrl</kbd>+<kbd>P</kbd>: pause/continue game

- <kbd>Ctrl</kbd>+<kbd>M</kbd>: switch ON/OFF sound effect

  If you want to accelerate the evolution process, you can speed up the game by 

- <kbd>Ctrl</kbd>+<kbd>1</kbd>: speed x1

- <kbd>Ctrl</kbd>+<kbd>2</kbd>: speed x2

- <kbd>Ctrl</kbd>+<kbd>3</kbd>: speed x3
