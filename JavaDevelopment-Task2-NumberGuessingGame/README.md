# Number Guessing Game

A console-based Number Guessing Game built with Java. The computer selects a secret number, and the player tries to guess it using higher/lower hints within a limited number of attempts.

## Features

- **Three difficulty levels**
  - **Easy:** number from 1–50, up to 10 attempts
  - **Medium:** number from 1–100, up to 7 attempts
  - **Hard:** number from 1–200, up to 5 attempts
- Random number generation for each round
- Input validation for difficulty selection and guesses
- Helpful feedback: `Too High!`, `Too Low!`, and `Correct!`
- Displays remaining attempts
- Reveals the secret number if the player loses
- Option to play multiple rounds
- Scoreboard showing each round's result and total rounds won

## Tech Stack

- Java
- `java.util.Random`
- `java.util.Scanner`
- `ArrayList` and `List`

## Requirements

- Java Development Kit (JDK) installed
- A terminal or command prompt

Check your Java installation:

```bash
java -version
javac -version
```

## How to Run

1. Download or clone this repository.
2. Open a terminal in the folder containing `NumberGuessingGame.java`.
3. Compile the program:

   ```bash
   javac NumberGuessingGame.java
   ```

4. Run the game:

   ```bash
   java NumberGuessingGame
   ```

## How to Play

1. Choose a difficulty level by entering its menu number.
2. Enter a valid guess within the displayed range.
3. Follow the hints:
   - `Too High!` means your guess is greater than the secret number.
   - `Too Low!` means your guess is less than the secret number.
   - `Correct!` means you guessed the number.
4. Try to guess the number before you run out of attempts.
5. Choose whether to play another round.
6. Review your results in the scoreboard.

## Project Structure

```text
numberguessing/
├── NumberGuessingGame.java
└── README.md
```

## Concepts Practiced

- Classes, enums, and objects
- Methods and control flow
- `if-else` statements and `while` loops
- Random number generation
- Console input with `Scanner`
- Collections with `ArrayList` and `List`
- Input validation and round-by-round score tracking

## Internship Task

**Oasis Infobyte (OIB-SIP) — Java Development Internship**  
**Task 2: Number Guessing Game**

## Author

**Tanishq**

## License

This project is created for learning and internship purposes.
