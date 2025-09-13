Pseudocode 

//getComputerChoice
1. create a random number generator (Math.random)
2. Program it to random between 3 numbers
3. For each number assign equivalent between paper, rock and scissor

//getHumanChoice
1. prompt user to input valid choice (prompt())
2. return the input

//player score global variables
1. store 0 value to human score
2. stire 0 value to computer score

//playRound
1. create function and define it to have humanChoice and computerChoice parameters
2. make humanChoice case insensitive by make it lowercase or uppercase
3. For every paper choice of human, assess against each 2 possible random choice of computer (scissor and rock)
4. increment computer score or human score accordingly
5. For every rock choice of human, assess against each 2 possible random choice of computer (scissor and paper)
6. increment computer score or human score accordingly
7. For every scissor choice of human, assess against each 2 possible random choice of computer (paper and rock)
8. increment computer score or human score accordingly
9. The rest is a tie 

//playGame 
1. create a loop that iterates 5 times
2. For each iteration, call the function playRound() with arguments getHumanChoice() and getComputerChoice()
3. When iteration stops, asses scores between human score and computer score
4. console log the winner
