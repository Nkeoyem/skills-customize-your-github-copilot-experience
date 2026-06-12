
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a Hangman game in Python that uses loops, conditionals, and user input to let players guess letters and discover a hidden word.

## 📝 Tasks

### 🛠️ Create the Hangman Game Core

#### Description

Write a Python program that selects a random secret word from a predefined list and lets the player guess letters until the word is solved or attempts run out.

#### Requirements
Completed program should:

- Randomly choose a secret word from a predefined list
- Accept single-letter guesses using `input()`
- Show the current word progress with unrevealed letters as `_`
- Track and display letters guessed so far
- Decrease remaining attempts for incorrect guesses
- End with a win message when the word is fully guessed or a lose message when attempts are exhausted

### 🛠️ Add Game Feedback and Replay Support

#### Description

Enhance the game experience by showing feedback for correct and incorrect guesses and allowing the player to restart the game.

#### Requirements
Completed program should:

- Inform the player when a guessed letter is correct or incorrect
- Display the number of remaining attempts after each guess
- Prevent repeated guesses from counting against the player
- Ask the player if they want to play again after the game ends
- Reset the game state cleanly for a new round if the player chooses to replay
