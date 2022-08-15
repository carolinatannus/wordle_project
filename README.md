## 1. Wordle: This project is an initial try to simulate the game of Wordle
#### If you are not familiar with the game, please visit <https://www.nytimes.com/games/wordle/index.html> to understand how it works.

## 2. Project Description
### What it does?
For now, the Wordle function created demands an initial five-letter word as its only argument. Having entered the word, first it checks if the user input is valid, then it generates a random five-letter word within the English dictionary.
While the guessed word is different from the generated random word, it returns which combination of letter and position were guessed correctly, and gives up to 6 chances for the user to guess the random word.
### Chosen technologies
For this project, I used the main technologies below:
##### random library: used to generate the random word
##### re library: used to guarantee the user input is a 5-letter word
### Improvements Needed
1) Review structure: the code is not running smoothly yet, I want to reaccess its structure to guarantee the user receives perfect instructions.
2) Complete game logic: Wordle not only shows the user when he guesses a right word an position, but also a right word in a wrong position - and this second logic is missing.
3) Import dictionary: in this first version I copied an online dictionary and transformed it into a list with 5-letter English words. In order for the code to process faster, it is interesting to import a working dictionary.
4) Automatically generate a new random word each day: to be faithfull to Wordle itself, I still need to define a random word per day, automatically. For the moment the function generates a new random word each time it is called.
5) Rethink errors: some errors were already inputed, but more tests are necessary to improve error handling.
6) Visual Output: it would be better to see the word horizontally (instead of vertically)
7) Return to Game: if the user's input is not a 5-letter word, I should allow him to return to the game with another try, without having to start from the beginning.ers to move around the project with ease.

## 4. How to Install and Run the Project
For now you can just copy and paste the current code and the list of words.
