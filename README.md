This is a simple Python console game where the user guesses a randomly generated number between 1 and 10. The program provides hints until the correct number is guessed.

Imports:

Imported Random - This allows the program to generate random numbers.

random.randint(1,10) - Allows a random number between 1 and 10 to be generated. 
This random number gets stored in "random_number" variable.

Setting the initial game state:
A boolean variable correct_guess is set to False to keep the guessing loop running until the correct number is guessed.

Checking the guess:
If the guess matches random_number, a congratulatory message is printed, and correct_guess is set to True to end the loop.

Hinting the user:
If the guess is higher than the random number, it informs the user: "Your guess is too high!"
If the guess is lower, it says: "Your guess is too low!"

End of the game:
Once the correct guess ends the loop, the program prints "Game Over! Good job!"
