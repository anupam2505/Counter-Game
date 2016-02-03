# Counter game

## Problem
Louise and Richard play a game. They have a counter set to N. Louise gets the first turn and the turns alternate thereafter. In the game, they perform the following operations.

If N is not a power of 2, reduce the counter by the largest power of 2 less than N.
If N is a power of 2, reduce the counter by half of N.
The resultant value is the new N which is again used for subsequent operations.
The game ends when the counter reduces to 1, i.e., N == 1, and the last person to make a valid move wins.

Given N, your task is to find the winner of the game.

## Input 
The first line contains an integer T, the number of testcases. 
T lines follow. Each line contains N, the initial number set in the counter.

##Output
For each test case, print the winner's name in a new line. So if Louise wins the game, print "Louise". Otherwise, print "Richard".

##Input Sample
```python 
1
6
```

##OutPut Sample
```python 
Richard
```
