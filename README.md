# Bingo

![The Bingo Board!](BingoBoard.jpg)

The Bingo project consists of a Bingo board that is highlighted as random numbers are announced. As the numbers are called out, each player marks their own Bingo Card. When a person gets a straight line, diagonal or four corners they yell out "BINGO". The game stops and the player's card is verified. If the game is valid, a prize is awarded and the next game begins. If the player does not have a valid Bingo, the game continues until someone gets one. 

The project utilizes BackgroundWorkers to implement multi-threading. Doing so prevents the UI from locking up. It was created in C# using WinForms. Automating the calling of numbers allows all participants to play so there is no need to designate a person to call the numbers. The Bingo board makes it convenient to know which numbers have been called by highlighting each number as it's announced. 
