
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a Python Hangman-style word guessing game that practices string handling, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Word Selection and Display

#### Description

Create a function that selects a random secret word and displays the current guess progress with underscores for unknown letters.

#### Requirements
Completed program should:

- Choose a secret word from a predefined list.
- Display the current word progress using underscores for letters not yet guessed.
- Example display for `python`: `_ _ _ _ _ _`

### 🛠️ Guess Handling and Game Loop

#### Description

Implement the main game loop to accept letter guesses, update the displayed word state, and track the remaining attempts.

#### Requirements
Completed program should:

- Ask the player to guess one letter at a time.
- Reveal correct letters in the masked word display.
- Deduct an attempt for each incorrect guess.
- Continue until the word is fully guessed or attempts run out.

### 🛠️ Win/Lose Feedback

#### Description

Show clear end-of-game messages and reveal the secret word after the game finishes.

#### Requirements
Completed program should:

- Print a win message when the player guesses the whole word.
- Print a game over message when the player runs out of attempts.
- Reveal the secret word at the end.
- Example output:
  `You win! The word was python.`
  `Game over. The word was python.`
