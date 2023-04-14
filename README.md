# Word-Guessing-Game
This is a simple command-line game where the player has to guess a randomly selected word within 10 attempts. The game provides a hint about the word, and the player can guess a letter at a time. If the guessed letter is present in the word, the game reveals its position(s) in the word; otherwise, the game keeps track of the wrong guesses. The game ends if the player guesses the entire word correctly within 10 attempts or runs out of attempts.

# Usage
- The game will provide a hint about the word.
- The player has to guess a letter at a time and press Enter.
- If the guessed letter is present in the word, the game will reveal its position(s) in the word.
- If the guessed letter is not present in the word, the game will keep track of the wrong guesses.
- The game ends if the player guesses the entire word correctly within 10 attempts or runs out of attempts.
- The player can play the game again by running the python word_guessing_game.py command again.

# Example
`        ---Word Guessing Game---
You have 10 attempts to guess the word correctly.
Hint: It is red in color!
The word is of 6 letters.
_ _ _ _ _ _
Guess a letter: a
_ _ _ a _ _
You have 9 attempts left.
Guess a letter: e
You guessed a wrong letter
_ _ _ a _ _
You have 8 attempts left. 
Guess a letter: i
You guessed a wrong letter
_ _ _ a _ _
You have 7 attempts left. 
Guess a letter: o
_ o _ a _ o
You have 6 attempts left.
Guess a letter: t
t o _ a t o
You have 5 attempts left.
Guess a letter: m
t o m a t o
You win! Your word was tomato`

# Contributing
Contributions are welcome! Here are some ways you can contribute:
- Report bugs and give feedback.
- Suggest new features or enhancements.
- Write code and fix issues.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
