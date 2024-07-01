# Number-Guessing Game

>[!IMPORTANT]
> - This Game Explore the following concepts :
>    - Random Library in Java.
>    - Object-Oriented Programming.
>    - Conditional Statements.
>    - Iterative Statements.

### Description
This is a simple console-based number-guessing game implemented in Java. The user tries to guess a randomly generated number between 0 and 99. The program provides feedback on whether the guess is too high or too low, and counts the number of attempts taken to guess the correct number.

## How to Play
1. Run the program.
2. The program will prompt you to guess a number between 0 and 99.
3. Enter your guess.
4. The program will provide feedback:
   - If your guess is too low, it will print "Too low..."
   - If your guess is too high, it will print "Too high..."
   - If your guess is correct, it will print "Yes you guessed it right" along with the number of attempts taken to guess correctly.
5. Keep guessing until you find the correct number.

## Code
Source code Available in the Above file:
```java
NumberGuessingGame.java
```

## Requirements
- Java Development Kit (JDK) 8 or higher

## Setup
1. Clone the repository or download the code.
2. Compile the Java file:
   ```sh
   javac GuessTheNumberGame.java
   ```
3. Run the compiled Java program:
   ```sh
   java GuessTheNumberGame
   ```

## Example Test Cases

### Test Case 1
**Input:** 
```
Guess the number: 50
```
**Possible Output:**
```
Too low...
```
or
```
Too high...
```
or
```
Yes you guessed it right, it was 50
You guessed it in 1 attempts
```

### Test Case 2
**Input:** 
```
Guess the number: 75
Guess the number: 25
Guess the number: 60
Guess the number: 90
Guess the number: 45
```
**Possible Output:**
```
Too high...
Guess the number: 25
Too low...
Guess the number: 60
Too high...
Guess the number: 45
Too low...
Guess the number: 90
Yes you guessed it right, it was 90
You guessed it in 5 attempts
```
