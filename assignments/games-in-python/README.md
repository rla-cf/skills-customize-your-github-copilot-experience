
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a console-based Hangman game to practice string manipulation, loops, conditionals, and handling user input. Emphasize clear game flow and friendly prompts so a peer can play without instructions.

## 📝 Tasks

### 🛠️ Random Word Selection & Main Game Loop

#### Description
Create the core Hangman game: randomly choose a secret word, run a loop that accepts letter guesses, updates and displays progress, and ends when the player wins or runs out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list (in-code list or a simple text file).
- Display current progress using underscores for unknown letters, e.g. _ _ a _ _.
- Accept single-letter guesses (case-insensitive) and reveal matching letters.
- Ignore repeated guesses and inform the player if a letter was already tried.
- Track and display remaining incorrect attempts (suggested default: 6).
- End the game with a clear win or lose message showing the secret word.

Example interaction:

```text
Secret: _ _ _ _ _
Guess a letter: a
Progress: _ a _ _ _
Incorrect guesses left: 5
```

### 🛠️ Input Validation & Difficulty Options

#### Description
Improve robustness and student control by validating input and adding at least two difficulty levels that change allowed attempts.

#### Requirements
Completed program should:

- Validate input to ensure only single alphabetical characters are accepted; prompt again for invalid input.
- Provide at least two difficulty options (e.g., "Easy" = 8 attempts, "Hard" = 4 attempts) selectable at game start.
- Handle non-letter input and empty input gracefully without crashing.
- Optionally provide a simple hint mechanism (e.g., reveal one correct letter) as an extra-credit feature.

