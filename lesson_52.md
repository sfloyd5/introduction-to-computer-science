# Lesson 5.2: Cloning Sprites

## Learning Objectives

Students will be able to...

-   Demonstrate the difference between sprite and global variables
-   Explain how cloning and prototyping simplify working with numerous similar sprites in the same program
-   Create prototype sprites and clones of the prototype sprite
-   Explain the difference between a "master" sprite and a "clone" sprite

## Materials/Preparation

-   [Do Now 5.2: Star Wars Troopers ](do_now_52.md)
-   [Lab 5.2 handout](lab_52.md) (Lots of Balls) ([Download in Word](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%205%20Word/Lab%205.2%20Lots%20of%20Balls.docx)) ([Link to PDF](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%205%20PDF/Lab%205.2%20Lots%20of%20Balls.pdf))
    -   Test out the lab on student machines before class--  cloning in SNAP! can bring the web browser to a crawl on some machines

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 15 minutes | Introductory discussion                       |
| 30 minutes | Lots of Balls lab                       |
| 15 minutes | Debrief and wrap-up |

## Instructor's Notes

---

#### Emphasize with students...

#### Big Ideas - Personal design interests require thee valuation and refinement of skills
    
As you complete this lesson you are probably starting to think of how the random movement of sprites can be incorporated into some type of video game. Perhaps you have an idea of a sports game, or a ball avoidance game, or a Martian invasion tape of game. You have developed a lot of skills that will help you complete these types of game, but it’s important for you to also consider what skills are missing. Are there other components of a video game that you perhaps don’t understand yet? What can you do to learn more about these components? Are there online tutorials, printed materials, experts in your area?

Evaluating your own skills and refining them is an important aspect of computer programming. There are always new technologies to learn and new concept to apply. A computer programmer is always learning something new, and you should be too!

---

1.   Introductory discussion
    -   Show students a brief video demonstrating space invaders (<https://youtu.be/437Ld_rKM2s?t=15>)
        -   Ask students to think about how we create all the “invaders”?
            -   Answer with current knowledge: make one invader sprite, and copy it many times while adjusting the copies as necessary
        -   Ask what might go wrong or be bad about this approach
            -   If anything in an invader changes, it will need to be changed many times
            -   Lots of sprites clogging up the program that are all basically doing the same thing
    -   Introduce cloning as the automated way of doing the manual copying
        -   Demonstrate how to create a clone using ![](createACloneOf.png)
        -   Point out that clones inherit all aspects of the "master" or "prototype" sprite, including scripts
        -   Emphasize the importance of using ![](whenIStartAsAClone.png) to ensure clones don't duplicate out of control
2.   Activity
    * Students should complete the ["Lots of Balls"](lab_52.md) lab
        * This lab will largely duplicate the code shown in the lecture part of the lesson-- that's OK
        * Students should focus on ensuring they are differentiating between "master" sprites and "clone" sprites, and that the stage is serving as the main "driver" for the program

## Accommodations/Differentiation
* Advanced students can attempt to assign properties to clones (color, size, etc.) so that not all clones look alike.  To do this, they will need to use a global variable to temporary hold the value that can be "claimed" by the clone.
* Struggling students should focus on just creating a single clone from the prototype and not worry about creating multiple clones.


## Forum discussion

<a href="http://forums.tealsk12.org/c/intro-unit-5-cloning/lesson-5-2-cloning-sprites" target="_blank">
Lesson 5.2: Cloning Sprites (TEALS Discourse account required).</a>
