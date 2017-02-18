# HW - {HANGMAN GAME}

## Hangman is a word guessing game where the word to be guessed is represented by a row of dashes, each dash representing the letter of the word to be guessed.

## RULES:
#### In this HANGMAN game, the player is allowed 9 guesses to correctly enter the letter corresponding to the word in play.

- A correct guess replaces the dash with the correct letter.

- An incorrect guess reduces the number of guesses by 1. If number of guesses reaches zero, the game is over and the user has the option of playing again.

- If all of the letters are correctly guessed without using up the number of available guesses, the player wins.

## PROGRAMS USED:
- HTML
- CSS
- BOOTSTRAP
- JavaScript

## METHODS USED:
- Functions  (to start game, track letters guessed, track number of wins/losses)
- for Loop  (to iterate through length of word for the letter guessed)
- Math.Floor and Math.Random  (to generate a random word to put into play from the word list)
- Arrays  (for word and letter lists)
- Variables  (to capture values like number of wins/losses, number of guesses)
- If/Else  (conditional statements to determine whether letter guessed is correct)
- Key Event  (to enter letters and play game)
- toLowerCase  (to ensure code works on any entered letter, regardless of case)
- document.getElementById  (to generate dashes representing the letters of the word to be guessed)

-------------

## Sample Code:

### Math.Floor, Math.Random, Variable and Array were used to generate a Random Word from Word List
var wordList = [
 "planet",
 "meteor",
 "gravity",
 "voyager",
 "universe",
 "orbit",
 "saturn",
 "jupiter"
];

var chosenWord = "";

chosenWord = wordList[Math.floor(Math.random() * wordList.length)];

```