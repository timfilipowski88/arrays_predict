# arrays_predict

Predict 1 
Line    Output  
1       8
2       6
3       7
4       5
5       3
6       0
7       9

Predict 2
Line    Output
1       That is odd!
2       That is odd!
3       8
4       4
5       2
6       0
7       That is odd!

Predict 3
Line    Output
1       -1
2       -3
3       -8
4       Zero
5       -4

1       -5
2       -2
3       -1


^^After checking my code I realize that I made the mistake of thinking that the .push action removed the value from arr. I forgot that the computer would need to be told to .pop that [i] from the arr array in order for this to happen. Therefor the Predict 3 would look like this:
Line    Output
1       [-1, -3, -8, 5, "Zero", 2, -4, 1]
2       [-5, -2, -1]