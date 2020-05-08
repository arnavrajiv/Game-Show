# ENGG1340: COMPUTER PROGRAMMING 2                                                 Group 142

## Team Members:-

* NAME: Jaffery Syed Muhammad Ali Murtaza   
  UID:  3035718046
  
* NAME: Rajiv Arnav   
  UID:  3035709057

# Description of the Text-Based Game -

* Our project is dedicated to emulate a trivia based gameshow. This game show would include several rounds bound by a sequential game     pattern i.e. succession of rounds in an order.
* The project structure is based on our user earning points in the form of money by answering trivia questions. 
  Every right decision would lead to addition of points, in turn every error would lead to the reduction of points i.e. the game money. 
  The currency of money earned can be entered by the user or using default value be set to game currency.
* The questions will be divided into different rounds. 
  In some rounds, the questions will be answered by manually by entering the answer, while in other rounds the user would have to select   an option.
* The topics would include but are not limited to science, sports, politics, gk. 
* The game will include rapid fire rounds and lucky 7 round's that would allow the user to gamble with large amounts of money.
  and rounds which would create chances to earn more money by gambling.
* At the end of the game, a player report will be generated and a score status of current player would be displayed.

# Features we plan to Implement:

## How Does Our Program Implement Random Events?
* As our game is trivia based, we intend to use functions under rand() to randomly select questions that the user will answer.
  These questions will be randomly chosen from sata structures which store the questions, options and answers.
* The lucky 7 round uses rand() function to randomly generate numbers for the betting game.

## How Do We Use Data Structures?
 * The game is based on trivia questions. These questions are stored in structures.
 * Some questions are stores in arrays.
 * User data is stored using structures as well.

## How Do We Implement Dynamic Memory Management?
 * The rapid fire round is based on the users demands.
 * As per the users choice, the number of questions are entered to a dynamic array and the answers are stored in another dynamic array. 
   These questions and answers are then used to play the rapid fire round.

## Use Of File input/output:
 * All of the user data is stored in a file.
 * Some of the game variables would be also written in files to maintain proper records of game choices and other implementation of game    features.
 * If one player quits the game in the middle of the game, he/she can restart from last saved checkpoint by entering name and loading      data

## How Do We Impliment Program code in multiple files?
 * Program code will be stored in multiple files to implement the game functionality without any errors.
 * These files would help to regulate the process used in the game.

