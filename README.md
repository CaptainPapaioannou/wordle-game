# wordle-game
A basic C implementation of the well-known Wordle game, as per the homonymous CS50 problem set

## Overview ##
Program that behaves simillarly to the popular Wordle daily word game.

**How to play** You pick the a letter size between 5, 6, 7 or 8. Then the game gives you a certain ammount of tries to attempt and guess a specific word. You win when you guess that particular word. After each try, the program returns a color-code markup for the word you gave. 
- If a letter is red it means that it is not in the word you need to guess. 
- If a letter is yellow, then it means that it appears in the word that you are trying to guess but in a different position.
- If a letter is green, then it means that it is in the correct position inside the word.
With this in your mind, you need to try to guess the word within the amount of tries that the games gives you in order to win!

## Usage ##
1. Compile the program as per the bellow bash command:
   ```
   make wordle
   ```
2. Run the program with the wordsize of your preference.
   For example:
   ```
   ./wordle 6
   ```
   This bash command will run the game with a wordsize of 6. Change the number with your choice accordingly.

  


