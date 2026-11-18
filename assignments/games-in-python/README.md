
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a Hangman word-guessing game using Python strings, loops, conditionals, random selection, and user input.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Initialize the words, game state, and random word selection in `starter-code.py`.

#### Requirements
Completed program should:

- Use the provided list of possible words.
- Randomly select one word as the secret word.
- Initialize the guessed letters and the number of incorrect guesses.
- Set a maximum number of incorrect guesses.

### 🛠️ Implement the Game Loop

#### Description
Create the main loop that accepts player guesses and updates the displayed word and game state.

#### Requirements
Completed program should:

- Prompt the player to enter a letter.
- Display the player's progress in `_ _ _` format.
- Add correct letters to the progress display.
- Track incorrect guesses and show how many remain.
- Prevent repeated guesses from being counted as additional incorrect guesses.

### 🛠️ End the Game

#### Description
Add win and lose conditions and display a clear final result.

#### Requirements
Completed program should:

- Continue until the word is fully guessed or the player has no attempts remaining.
- Display a win message when the player guesses the word.
- Display the secret word and a lose message when the player runs out of attempts.
