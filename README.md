🎯 Number Guessing Game (C++)

📌 Description

This program randomly selects a number between 1 and 100, and the user has to guess it.
After each guess, the program tells the user whether the guess is too high, too low, or correct.
The game continues until the correct number is guessed.

🧠 Pseudo Code

START
GENERATE a random number between 1 and 100 → secretNumber
REPEAT
    PROMPT user to enter a guess
    IF guess > secretNumber THEN
        PRINT "Too high! Try again."
    ELSE IF guess < secretNumber THEN
        PRINT "Too low! Try again."
    ELSE
        PRINT "Congratulations! You guessed it!"
    END IF
UNTIL guess == secretNumber
STOP
