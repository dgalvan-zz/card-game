# card-game


---

# Magic: The Lambda-ing - Card Game

This repository hosts the code for a Python-based card game, "Magic: The Lambda-ing." The game involves strategic card play, drawing from decks, and unique card effects. Players compete against each other to win rounds based on their card powers and ultimately aim to be the first to secure eight victories for the match.

### Getting Started

To initiate the game, run the command `python3 cardgame.py` in your terminal.

### Files in the Repository

- **classes.py**: Contains the implementations for the Card and Player classes, fundamental to the gameplay.


- **cardgame.py**: Manages the game itself, acting as a bridge to the classes for game logic.


- **cards.py**: Holds default cards and decks, allowing customization and addition of new cards for unique gameplay.

### Game Rules Overview

- **Players and Decks**: Each player starts with a deck and a hand of cards. Decks are drawn from to obtain cards.


- **Playing Rounds**: Players select a card from their hand each round.


- **Power Calculation**: Card powers are determined by their attack and defense stats, influencing the outcome of each round.


- **Win Conditions**: The first player to win 8 rounds wins the match.

### Implementations (As Referenced in Questions)

- **Q1 - Making Cards**: Implemented the Card class constructor and power method for power calculation between cards.


- **Q2 - Making a Player**: Constructed the Player class, enabling players to draw cards and play them in the game.


- **Q3 - Tutors: Flummox**: Developed the effect method for Tutors, affecting the opponent's hand by discarding and re-drawing cards.


- **Q4 - TAs: Shift**: Created the effect method for TAs, which swaps the attack and defense of an opponent's card.


- **Q5 - The Professor Arrives**: Implemented the effect method for Professors, influencing the player's and opponent's decks based on the opponent's card.
