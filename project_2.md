<!--- REVISED -->
# Project 2: Boingy Bouncer

Students will implement a well-written and engineered version of the classic arcade game Pong, or a game of their own choice that includes an animated projectile, a "paddle" and boundaries.

## Overview

In 1972, when video games were still very new and relatively unknown, a new game took the world by storm.  A simple simulation of tennis using two-dimensional graphics, minimal sounds, and extremely basic controls, Pong became the first arcade game to achieve widespread popularity and is credited as the genesis of the modern video game industry.  Today, the game has been played, remade, spun-off, and referenced innumerable times and it remains, to many, the single most identifiable and recognizable game in the history of video games.

## Details

1.  **Behavior**
    1.  **Gameplay** <br/>
        Pong is played by two players each controlling a paddle with the goal of defending their end of the "field."  A ball begins play in the middle of the screen and, at the start of each round, moves in a random direction.  The ball bounces off the upper and lower edges of the field and the players' paddles.  Each time the ball bounces off a paddle, its speed increases by a small amount.  When the ball bounces off a paddle, its direction is reversed with a small random variation to add unpredictability to the game.
    2.  **Scoring** <br/>
        If the ball touches the left or right edge of the field, a point is scored for the opponent of the player who was defending that edge and the ball resets to the middle of the field.  When one player reaches 5 points, the game is over and that player is the winner.  The winner is announced on the screen and the players are given the opportunity to start a new game.
    3.  **Player Control** <br/>
        Paddles are positioned a short distance away from the side they are defending, and can only move up and down, not side to side.  Each player should have two keys to control the movement of their paddle: one for up, and one for down.  Paddles move at a set speed that is the same for both players can cannot be controlled.  The player on the left will control his/her paddle with the 'w' and 's' keys.  The player on the right will use the up arrow and down arrow keys.
         

2.  **Required Checkpoints**
    1.  Players can control paddles; the ball starts in the middle, moves in a random direction, and bounces
    2.  The ball speeds up when it hits a paddle, and resets to the middle when it hits the left or right edge
    3.  Final due date: A point is scored when the ball hits the edge on the opponent's side of the field; the game ends when one player reaches five points; players can start a new game after the game ends

## Planning Worksheet
For this task you will revisit the Applied Design process in order to create a program similar to Pong.

Your project should involve a projectile (a ball, a bird, a boomerang, a character, a cupcake, etc) that will collide with an object (a paddle, a racket, another character, etc) and will allow the user to score points.

You can recreate the pong game if you wish (perhaps changing some sprites or rules), or you can create some type of game that uses similar rules and logic, but with different or additional features.

If you chose to create something different, just ensure that your program includes the following requirements:
1. Player can control an object (a paddle, a racket, another character, etc) with keys 
2. The projectile begins in a certain location at the start of the game and after each “point”
3. The projectile has consistent action in how it rebounds off of edges of screen
4. he projectile’s speed is altered at some point in the game
5. Points are scored in an effective and logical manner
6. Game has an ending based on specific rules of reaching a given score
7. Winning and losing players are indicated at the end of the game
8. Players can begin a new game

Before you begin your project, you will select an end-user for your game (friend, classmate, teacher, relative, etc) and you will interview this end-user in order to learn about their interests. You will then use their interests to shape the design and implementation of your game. This end-user will later test your program and provide feedback before you complete your final version.

As you interview your end-user, create the Boingy Bouncer using SNAP, and then test and share the program, you will proceed through the Applied Design stages. The Applied Design Stages document (CSIntroUnit2Project-AppliedDesign.docx) will lead you through the following stages (you should submit this to your teacher when complete):

**Understanding Context - Defining - Ideating - Prototyping - Testing – Sharing**

## Grading Scheme/Rubric

| Functional Correctness (Behavior)                                                    |           |
| ------------------------------------------------------------------------------------ | --------- |
| Players can control paddles with required keys                                       | 2 points  |
| Ball begins play at middle of field at start of game and after each point            | 3 points  |
| Ball bounces correctly off upper and lower edges and paddles                         | 4 points  |
| Ball increases in speed each time it bounces off a paddle                            | 3 points  |
| A point is scored for the opponent each time the ball touches the left or right edge | 3 points  |
| Game ends when one player reaches five points                                        | 2 points  |
| Winning player is shown when game ends                                               | 1 point   |
| Players can begin a new game                                                         | 1 point   |
| Total                                                                                | 19 points |
| Technical Correctness (Implementation)                                               |           |
| ------------------------------------------------------------------------------------ | --------- |
| Gameplay is smooth, polished, and intuitive                                          | 3 points  |
| Program shows good creativity and effort                                             | 2 points  |
| Program is well-documented and exhibits good style                                   | 2 points  |
| Checkpoint 1                                                                         | 4 points  |
| Checkpoint 2                                                                         | 4 points  |
| Total                                                                                | 15 points |
| ------------------------------------------------------------------------------------ | --------- |
|Applied Design Steps and Log	                                                       |           |
|Understanding Context components are complete and thorough	                           | 1 point   |
|Defining components are complete and thorough	                                       | 1 point   |
|Ideating components are complete and thorough	                                       | 1 point   |
|Ideating/Prototyping are components complete and thorough	                           | 3 points  |
|Testing components are complete and thorough	                                       | 1 point   |
|Sharing components are complete and thorough	                                       | 1 point   |
|Total                                                                                 | 8 points  |
| Grand Total                                                                          | 42 points |
