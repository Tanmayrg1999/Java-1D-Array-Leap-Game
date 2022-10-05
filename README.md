LEAP GAME :


Let's play a game on an array! You're standing at index 0 of an n-element array named game you can perform one of the following moves:

1. Move Backward: If cell  exists and contains a 0, you can walk back to cell i-1.

2. Move Forward:
   
    If cell i+1 contains a zero, you can walk to cell i+1.
    
    If cell i+leap contains a zero, you can jump to cell i+leap.

If you're standing in cell n-1 or the value of i+leap>=n, you can walk or jump off the end of the array and win the game.

In other words, you can move from index i to index i+1 ,i-1 , or i+leap as long as the destination index is a cell containing a 0.

If the destination index is greater than , you win the game.

![image](https://user-images.githubusercontent.com/53641559/155670942-399d65be-d3c7-4a69-89d7-5a84389c2aba.png)
