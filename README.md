Hangman game in Python
# Hangman Game

This is a simple Hangman game implemented in Python. The game randomly selects a word from a predefined list and allows the player to guess letters or the entire word within a limited number of attempts.

## Features

- Randomly selects a word from a list of predefined words.
- Allows the player to guess letters or the entire word.
- Displays the current state of the Hangman after each guess.
- Keeps track of guessed letters and words.
- Provides feedback on the player's progress and notifies when the game is won or lost.

## Prerequisites

- Python 3.x installed on your machine.

## Getting Started

1. **Clone the repository**

    ```sh
    git clone https://github.com/Aysenur-Erkin/hangman.git
    cd hangman-game
    ```

2. **Run the game**

    ```sh
    python hangman.py
    ```

## How to Play

1. The game will display a series of underscores representing the letters of the word to guess.
2. You can guess a letter or the entire word.
3. If your guess is correct, the letter(s) will be revealed in the word.
4. If your guess is incorrect, you lose one of your tries.
5. The game ends when you guess the word correctly or run out of tries.

### Example

Below is an example interaction with the game:

```plaintext
Let's play Hangman!
   --------
   |      |
   |      
   |    
   |      
   |     
   -

_____

Please guess a letter or word: p
Good job, p is in the word!
   --------
   |      |
   |      
   |    
   |      
   |     
   -

p_____

Please guess a letter or word: y
Good job, y is in the word!
   --------
   |      |
   |      
   |    
   |      
   |     
   -

py____

Please guess a letter or word: x
x is not in the word.
   --------
   |      |
   |      
   |    
   |      
   |     
   -

py____

...

