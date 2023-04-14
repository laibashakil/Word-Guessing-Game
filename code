import random

def main():
    # List of words to choose from
    words = ['apple', 'chilli', 'tomato', 'ruby', 'rose']

    # Introduction to the game
    print("\t---Word Guessing Game---")
    print("You have 10 attempts to guess the word correctly.")
    print("Hint: It is red in color!")

    # Select a random word and initialize variables
    wrong_list = []
    original_word = random.choice(words)
    guessed_word = ["_"] * len(original_word)

    # Display the initial guessed word
    print(f"The word is of {len(original_word)} letters.")
    print(*guessed_word)

    # Main game loop
    attempts = 10
    while attempts > 0:
        attempts -= 1
        guessed_letter = input("Guess a letter: ")

        if guessed_letter in original_word:
            # If the guessed letter is in the word, replace the corresponding underscores with the letter
            for i in range(len(original_word)):
                if original_word[i] == guessed_letter:
                    guessed_word[i] = guessed_letter
        else:
            # If the guessed letter is not in the word, add it to the wrong_list
            print("You guessed a wrong letter")
            wrong_list.append(guessed_letter)

        # Display the updated guessed word
        print(*guessed_word)

        # Check if the player has won
        if original_word == "".join(guessed_word):
            print("You win! Your word was", original_word)
            return

        # Display the number of attempts left
        print(f"You have {attempts} attempts left.")

    # If the player runs out of attempts, they lose
    print(f"You lost the game. The original word was {original_word}")

if __name__ == "__main__":
    main()
