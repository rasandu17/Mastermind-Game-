# Mastermind Game in Python

This is a simple implementation of the Mastermind game in Python, where a player tries to guess a randomly generated multi-digit number.

## Game Rules

- Two players take turns guessing the number.
- Player 1 sets the number, and Player 2 tries to guess.
- The game provides hints about correct digits and their positions.
- The game continues until Player 2 guesses the number or vice versa.
- The winner is the one who guesses in fewer tries.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mastermind-python.git
   cd mastermind-python
   ```

2. Run the Python script:

   ```bash
   python mastermind.py
   ```

3. Follow the instructions to play the game.

## Examples

### Example 1

```plaintext
Player 1, set the number: 5672
Player 2, guess the number: 1472
Not quite the number. You did get 2 digits correct.
X X 7 2

Enter your next choice of numbers: 3562
Not quite the number. But you did get 3 digits correct!
X X 7 X

Enter your next choice of numbers: 5672
You've become a Mastermind!
It took you only 2 tries.
```

### Example 2

```plaintext
Guess the 4 digit number: 2164
Not quite the number. But you did get 2 digit(s) correct!
Also these numbers in your input were correct.
X X 6 4

Enter your next choice of numbers: 3564
Not quite the number. But you did get 2 digit(s) correct!
Also these numbers in your input were correct.
X 5 6 4

Enter your next choice of numbers: 1564
You've become a Mastermind.
It took you only 3 tries.
```

## Make it Harder

You can modify the code to make the game harder by increasing the number of digits or not disclosing the correct positions of guessed digits.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Remember to replace "your-username" in the GitHub clone URL with your actual GitHub username. Also, make sure to include the license file if you decide to choose a specific license for your project.
