# Fruit Hangman Game

## Description
A simple command-line Hangman game where players guess a randomly selected fruit name. The game provides a fun and interactive way to guess letters and reveal a hidden fruit word.

## Features
- Random fruit word selection
- Limited number of guessing chances
- Input validation
- Hints about the word category (fruits)
- Simple and intuitive gameplay

## Prerequisites
- Python 3.x
- No additional libraries required beyond standard Python libraries

## How to Play
1. Run the script
2. The game will randomly select a fruit name
3. You'll see blank spaces representing the letters in the word
4. Guess one letter at a time
5. You have a limited number of chances equal to the word length plus 2
6. Try to guess the entire word before running out of chances!

## Game Rules
- Only single alphabetic letters are accepted
- Repeated letter guesses are not allowed
- Correct guesses reveal the letter in its correct position
- Incorrect guesses reduce your remaining chances

## Example Gameplay
```
Guess the word! HINT: word is a name of a fruit
_ _ _ _ _

Enter a letter to guess: a
You have 6 chances left.
a _ a _ _

Enter a letter to guess: p
You have 5 chances left.
a p p _ _

Congratulations, You won!
```

## Possible Improvements
- Add difficulty levels
- Implement a scoring system
- Create a larger word list
- Add ASCII art for visual feedback

## Running the Game
```bash
python hangman.py
```

## Exit
- Press Ctrl+C to exit the game at any time

## Fruits in the Game
- apple
- banana
- mango
- strawberry
- orange
- grape
- pineapple
- apricot
- lemon
- coconut
- watermelon
- cherry
- papaya
- berry
- peach
- lychee
- muskmelon

## License
Open-source. Feel free to fork and modify!

## Contributions
Suggestions and pull requests are welcome!
