# Guess Again
Using basic python functionality to create a basic games called "Guess Again". In this made up game, 3 random  numbers will be selected from a list from 1 to 10. We will then get the average of those numbers. Once we have this average we allow the program (player2) to select 3 numbers and the end user (player1) to do so as well: Points will be given out as follows:

2 points - guessing the average perfectly   
1 point - guessing within 1.5 of the random average  
0.5 points - guessing within 2.5 of the average   
0 points - guessing outside 2.5 of the average 

In this notebook project we will aim to: 
- Create the game "Guess Again" by making a basic Python function.
- Explore the use of new packages like `random`.

## GUESS AGAIN FUNCTION  
Using the basic Python `def` contructor we created a function known as "Guess Again".

1) This function has the arguments: play1, play2, play3 that represents the input the user enters.
2) We then define our total possible play which are the numbers from the sequence 1 to 10 in the list `plays`.
3) We then store these plays in the list `player1` and calculate its average `player1_avg` which is the avergae score of the users scores.

**For loop**    
We create a for loop that will run for 3 iterations until and select a number form the sequence of 1 to 10 for what the computer will select for its guesses.
We then create an empty list called `player2` to store the computer selections.  
We then use the `random` package to randomly select these 3 values from our list `plays`.    
These selections are then appended into the list `player2`.
Finally we get the average of these plays and store them in `player2_avg`.  

This is then replicated with a completely random score for the computer that we will compare player1 and player 2 to. 

**Game winning Criterion**   
We then define what the criteria for each player being awarded a score is.   
We use if statements for each player to determine their points. 
It follows the criteria above and uses `and` and `or` logical operators. 

2 points - guessing the average perfectly   
1 point - guessing within 1.5 of the random average  
0.5 points - guessing within 2.5 of the average   
0 points - guessing outside 2.5 of the average

We then finish the function up using format strings to print out the scores for both player 1 and 2. 

 ## PROJECT STRUCTURE      
|[Guess Again](https://github.com/leta199/Guess-Again)  
|├── [game code](https://github.com/leta199/Guess-Again/tree/main/game_code)     
│  └──[Guess Again ipynb](https://github.com/leta199/Guess-Again/blob/main/game_code/Guess_Again.ipynb)    
│  
|└──[kernel](https://github.com/leta199/Guess-Again/tree/main/kernel)   
│  
|└──[README](https://github.com/leta199/Guess-Again/blob/main/README.md)
  
## AUTHORS   
[leta199](https://github.com/leta199)  


  
