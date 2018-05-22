# Scrabble-game
Scrabble game using data structures in C
-Works best on Windows.

-source.c has the main C program.
-word2.txt has all valid English Scrabble game words.
-letters.csv has all the letters(ASCII values) along with their number of occurences.

Project Description:

-This is a 2-player scrabble game.
-All the letters along with number of occurrences are stored in a linked list,after extracting from letters.csv.
-We initially provide 10 randomly generated letter to the player.
-The player should form a valid English word using the provided letters.
-The formed word is validated by checking in words2.txt file having all possible and valid English Scrabble words.
-We have used file operations for validating.
-The letters used up by Player 1 are replaced by randomly generated letters for Player 2.
-A word once accepted,is placed into a Binary Search tree.
-Each subsequent word formed will henceforth be checked for repetition(in Binary Search Tree) and also in word2.txt.
-When letters and the location are entered by player, it checks whether the letters present on either side of given location concatenate to form a valid word or not.
-It ends the game if all tile are exhausted or if a Player enters 3 invalid words.


Concepts Used:
-Arrays
-Linked List
-Binary Search Tree
-File operations
-String Methods
