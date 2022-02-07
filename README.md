# Bingo

![The Bingo Board!](BingoBoard.jpg)

This game was created to function as a Bingo Caller. Below I describe the game of Bingo. The project utilized background workers to implement multithreading, to prevent the UI from locking up. It was created in C# using WinForms. 

The game is used to simulate the Bingo Caller and display which numbers have been called in the game, Bingo.  Automating the calling of numbers allows all participants to play so there is no need to designate a person to call the numbers.

The game begins and the numbers are called out one by one until someone gets a Bingo. The player's card is compared to the Bingo board to determine if the numbers that were marked on the players card were called. Once verified the winner gets their prize and the game continues. 
