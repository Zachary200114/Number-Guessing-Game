## Number Guessing Game

This is a **Simple Number Guessing Game** built using Python. The program generates a random number between 1 and 10, and the user has to guess the correct number. The game provides feedback if the guess is too high or too low until the user guesses correctly.

## Features

- Random number generation between 1 and 10.
- Feedback for each guess (too high, too low).
- Success message when the correct number is guessed.
- Infinite attempts until the user wins.

## Requirements

Ensure you have Python installed. To check your Python version, run:

```bash
python --version
```

## How to Run

1. Copy the code into a `.py` file, for example: `number_guessing.py`.

2. Open a terminal in the same directory as the file.

3. Run the program with:

```bash
python number_guessing.py
```

4. Follow the on-screen instructions and guess the number.

## Example Usage

```
Guess a number between 1 and 10!: 5
Your guess is too low!

Guess a number between 1 and 10!: 8
Your guess is too high!

Guess a number between 1 and 10!: 7
You got it congratulations!
Game Over good Job!
```

## Customization

- **Range:** Change `random.randint(1, 10)` to any range you prefer.
- **Difficulty:** Add a guess limit if you want to make it more challenging.
- **Replay Option:** Modify the code to restart the game after each win.

## Known Issues

- Entering a non-integer input will raise a `ValueError` and crash the program.
