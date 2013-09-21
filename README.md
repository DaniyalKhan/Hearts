#Hearts, Terminal Style!#

Classic game of hearts takes an 8-bit turn onto your computer monitor!

Originally made as the final project for cs246 (Object Oriented Software Development in C++)

Developers: 
- Daniyal Khan
- Shahzaib Bhatti

- Max number of players: 4
- Min number if players: 0 (watch the AIs duke it out!)

Running Instructions:
======================
1. If the "Hearts" file is not int he repository, run the makefile to compile it by running: "make".
2. Otherwise ensure the Hearts file is executable bu running "chmod a+x Hearts"
3. ./Hearts to run the file!

Command Line Options
=======================
If you run the file without any options, 4 AIs will automatically play the game for you.
To specify number of players, enter on the command line:
  ./hearts -p [name_1] [player_type_1] [name_2] [player_type_2] [name_3] [player_type_3] [name_4] [player_type_4]
where: 
- <player_type> is either H (human), R (random AI player), or S (smart AI player) and 
- <name_x> is the name of the player. 
  - Players that are 'Human' will have an 'h' prefixed to their name
  - AIs that are 'smart' will have 's' prefixed to their name
  - AIs that are 'random' will have an 'r' prefixed to their name

Example:
  running: ./Hearts -p Superman H Batman H Spiderman H Hudson S
  will create 3 human players (Superman, Batman, Spiderman) and 1 smart AI player (Hudson) 
  
How To Play:  
===============
During each player's turn, they can see the cards they have in their hand. 
They can then play a card from their hand by typing the card in the terminal and hitting enter.
The game follwos the traditional rules of hearts, with a few exceptions.
First player to empty their hands of cards wins!
