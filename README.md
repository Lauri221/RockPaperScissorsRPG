# Rock, Paper, Scissors RPG

## Description
This is a simple text-based RPG game based on the classic game of Rock, Paper, Scissors. The player battles against the computer in a series of rounds, with each round consisting of a game of Rock, Paper, Scissors. The winner of each round deals damage to the loser, and the first to reach 0 HP loses the game.

## Features
- Text-based interface
- Player vs Computer gameplay
- Random damage rolls with critical hits and fails
- Health and score tracking

## Game Mechanics
- **Critical Hits**: If the damage roll is a 20, it's a critical hit! The hit does double damage.
- **Critical Fails**: If the damage roll is a 1, it's a critical fail! Instead of dealing damage, the opponent heals

## How to Play
At the beginning of each round, you must choose a move: Rock (R), Paper(P), or Scissors(S). Both you and the computer begin the game with 50 HP. When either player or opponent wins, they roll a 20-sided die for damage. The first to reach 0 hp gets knocked out and loses.

## Installation
1. Clone this repository
2. Install the required dependencies with `pip install -r requirements.txt`
3. Run the game with `python main.py`

## Dependencies
- Python 3
- colorama

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
MIT
