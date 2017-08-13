# Scrabble
Programming the ability to play scrabble in reverse


Daily Programmer Challenge #326
Given Two integers and a Scrabble board find out the order in which the Words were played

Concept for the Program:

1. Find The X and Y values of the board
2. Find the Middle of the board
3. Check to see if there is a word on that line
3a. If there is a word:
  - Write word to another string
  - save word to be printed out later
3b. If there is no word:
  -Add one to the Y value and repeat step 3
4. Check to see if there are any letters connected to the word that was just found
4a. If there were letters found:
  - take all letters and rearange based on their Y or X coordinates
  - Write word to another string
  - save word to be printed later
4.b If there were no letters found: 
  - repeat 3b.
