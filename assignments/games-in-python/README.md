# 📘 Assignment: Games in Python

## 🎯 Objective

Build a simple Hangman-style game in Python using strings, loops, and user input while practicing basic programming logic.

## 📝 Tasks

### 🛠️ Create the Game Setup

#### Description
Set up the core variables and word selection for your game so the player can begin guessing.

#### Requirements
Completed program should:

- Choose a secret word from a predefined list using `random.choice()`.
- Keep track of guessed letters and remaining incorrect guesses.
- Display the current word progress using underscores for unguessed letters.

### 🛠️ Build the Game Loop

#### Description
Create the main loop that lets the player guess letters, updates the game state, and ends when the word is solved or attempts run out.

#### Requirements
Completed program should:

- Ask the player to enter one letter at a time.
- Reveal matching letters in the hidden word.
- Count incorrect guesses and stop the game when the limit is reached.
- Print a clear win or lose message at the end.
