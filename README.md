# War Game of Cards

A simple terminal-based card game inspired by the classic game of War.

## Overview

This project simulates a two-player card battle where each player starts with 26 shuffled cards. Each round, both players reveal one card, and the higher card value wins the round and takes both cards. If both cards are equal, the game enters a war state, where additional cards are drawn until one player wins the pile.

## Included classes

- `Card`: Represents a single playing card with a suit, rank, and numeric value.
- `Deck`: Creates and shuffles a full 52-card deck and deals cards.
- `player`: Represents a single player and manages their hand of cards.

## Game behavior

- A full deck is created and shuffled.
- The deck is split evenly between two players.
- Each turn, both players play one card.
- The player with the higher value card collects both cards.
- In case of a tie, the game enters a war round.
- The game ends when one player runs out of cards.

## How to run

1. Open a terminal in the project folder.
2. Run the script:

   ```bash
   python war_game_of_cards.py
   ```

## Notes

- This is a beginner-friendly Python project that demonstrates object-oriented programming.
- It is designed for learning card-game logic, deck handling, and simple game flow.

## File

- `war_game_of_cards.py`
