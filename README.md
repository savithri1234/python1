
import random

number = random.randint(1, 100) # generate a random number between 1 and 100
guess = None # initialize the guess variable

while guess != number:
    guess = int(input("Guess a number between 1 and 100: ")) # ask the user to guess the number
    if guess < number:
        print("Too low, try again.")
    elif guess > number:
        print("Too high, try again.")
    else:
        print("Congratulations, you guessed the number!")
        
        
