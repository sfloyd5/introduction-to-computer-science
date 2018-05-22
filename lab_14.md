<!--- REVISED -->
# Lab 1.4: Sprites in Action

In this lab, you will use costumes and movement to create simple SNAP animations.


    



## 1. Run, Spot, Run!

1.1) In a SNAP project, click on the file menu, then click costumes.  Import the costumes "dog2-b" and "dog2-c".

![Menu->Costumes](menucostumes.png)

![Import Costumes](importcostumes.png)

1.2) Write a script to make the sprite change costume each time the space bar is pressed. The sprite should switch back and forth between the two costumes.

1.3) Add code so that the sprite will face to the left, move a few steps, and change costume when the left arrow key is pressed. If you've done it right, it should look like the dog is walking when you press the left arrow key repeatedly.

1.4) Add code so that the dog can walk to the right as well.

<table>

<tr> 
<td>
  
<strong>Content - Translation of design specifications into source code</strong></br><br>
The tasks below ask you to create programs based on certain specifications (fire breathing dragon, a sprite that runs from the dragon, etc). When you write a SNAP script you are writing something called source code. All computer programs have source code, this is the programming code that provides the instructions for the computer to execute.<br><br>
Throughout the course, pay close attention to the design specifications and take note of how you translate these specifications into source code.
</td>
</tr>
</table>

## 2. Here be Dragons!

2.1) Create a new sprite. Following the same steps as in part 1.1, import the costumes "dragon1-a" and "dragon1-b"

2.2) Write a script to make the sprite appear to breathe fire when the 'f' key is pressed.  The sprite should switch to the "fire-breathing" costume for a few seconds, then switch back to the "normal" costume.

2.3) Modify your code so that the dragon "attacks" the mouse pointer when the 'f' key is pressed. When the 'f' key is pressed, the dragon should take the following actions in order:

-   Make sure it is in the "normal" costume
-   Point at the mouse pointer
-   Glide to the mouse pointer's position
-   Change to the "fire-breathing" costume
-   Pause to breathe fire
-   Change back to the "normal" costume

## 3. Run Away!

3.1) Add another sprite to your program.  (This sprite can have any costume you choose.)

3.2) Write a script to make this new sprite point away from the dragon and move when the 'r' key is pressed.  (You'll need more than one block to do this.)

3.3) Modify your code so that instead of moving when the 'r' key is pressed, the new sprite moves when the dragon "attacks."  The "fleeing" sprite should move when the dragon starts breathing fire.

3.4) Add a second sprite that runs away from the dragon as well.

## Grading Scheme/Rubric

| **Lab 1.4 Criteria**                              |                |
| ------------------------------------------------- | -------------- |
| 2.2 Dragon breathes fire                          | 0.25 points    |
| 2.3 Dragon attacks mouse pointer correctly        | 0.75 points    |
| 3.2 A sprite runs away from dragon                | 0.25 points    |
| 3.3 Sprite runs away when dragon breathes fire    | 0.5 points     |
| 3.4 Another sprite runs away too                  | 0.25 points    |
| **PROJECT TOTAL**                                 | **2.0 points** |
