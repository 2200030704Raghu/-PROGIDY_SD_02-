# -PROGIDY_SD_02-


Build a program that generates a random number and challenges the user to guess it. The program should prompt the user to input their guess, compare it to the generated number, and provide feedback if the guess is too high or too low. It should continue until the user correctly guesses the number and then display the number of attempts it took to win the game.


Explanation:
Import Random Module: The random module is imported to generate a random number.
Generate Random Number: random.randint(1, 100) generates a random integer between 1 and 100.
Initialize Attempts: The attempts variable tracks the number of guesses the user makes.
Game Loop: The while loop continues until the user guesses the number correctly. It increments the attempts counter and provides feedback on whether the guess is too high or too low.
User Input: The program prompts the user to enter their guess.
Feedback: Based on the user's guess, the program provides feedback and continues the loop until the correct guess is made.
Congratulatory Message: When the user guesses the number, the program prints a congratulatory message along with the number of attempts it took.
