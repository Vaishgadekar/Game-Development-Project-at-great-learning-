# Game-Development-Project-at-great-learning-
In this we will use the random module to make a word-guessing game. This game is for beginners learning to code in python and to give them a little brief about using strings, loops, and conditional(If, else) statements.

### random module: Sometimes we want the computer to pick a random number in a given range, pick a random element from a list, pick a random card from a deck, flip a coin, etc. The random module provides access to functions that support these types of operations. One such operation is random.choice() method (returns a random item from a list, tuple, or string.) that we are going to use in order to select one random word from a list of words that we’ve created.

# Word guessing game

In this game, there is a list of words present, out of which our interpreter will choose 1 random word. The user first has to input their names and then, will be asked to guess any alphabet. If the random word contains that alphabet, it will be shown as the output(with correct placement) else the program will ask you to guess another alphabet. The user will be given 12 turns(which can be changed accordingly) to guess the complete word.

- In this game, there is a list of words present, out of which our interpreter will choose 1 random word. The user first has to input their names and then, will be asked to guess any alphabet. If the random word contains that alphabet, it will be shown as the output(with correct placement) else the program will ask you to guess another alphabet. The user will be given 6 turns(which can be changed accordingly) to guess the complete word.



- The code starts by asking the user to enter their name.
- The code then prints a message saying “WELCOME TO THE GAME WORD”
and sets a variable called name to the inputted name.
- Next, the code creates a list of words using the built-in function word().
- This function takes in an input string and returns a list of strings.
- The next part of the code is where the randomness happens.
- The code will randomly choose one string from the list of words and store it in variable.
- Then it will print out that word along with a space at the end.
- After printing out each word, the code checks to see if any user has entered an incorrect letter by comparing each character in guess with those in word .
- If they don’t match up then guess is set to “Wrong” and turns is decreased by 1 .
- The code will randomly choose one word from a list of words.
- The user is then asked to enter the characters for that word.
- Once the user enters all of the characters, the code checks to see if those characters are in the word that was chosen.
- If they are not, it prints out “Wrong” and decreases the number of turns left for the user by 1.
- If all turns have been used, then the code will print “You Lose.”


