# Word Guessing Game
This is a simple command-line game where the player has to guess a randomly selected word within 10 attempts. The game provides a hint about the word, and the player can guess a letter at a time. If the guessed letter is present in the word, the game reveals its position(s) in the word; otherwise, the game keeps track of the wrong guesses. The game ends if the player guesses the entire word correctly within 10 attempts or runs out of attempts.

## How to Play

1.  **Introduction**: Upon starting the game, you'll be greeted with an introduction and a hint about the word to be guessed.
2.  **Guessing**: You have 10 attempts to guess the word correctly. Input a letter to make your guess.
3.  **Feedback**: If your guessed letter is correct, it will reveal its positions in the word. If it's wrong, it'll be added to the wrong guesses list.
4.  **Win or Lose**: The game continues until you correctly guess the word or run out of attempts.

## Example
```        ---Word Guessing Game---
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
You win! Your word was tomato
```

## Requirements

-   Python 3.x

## Getting Started

1.  Ensure Python is installed on your system.
2.  Clone or download this repository to your local machine.
3.  Run the `word_guessing_game.py` file using a Python interpreter.

## Contributing

We welcome contributions to enhance the game! Feel free to add new features, improve the user interface, or optimize the code. If you encounter issues or have suggestions, please open an issue in the repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

Let the guessing begin! 🎉
