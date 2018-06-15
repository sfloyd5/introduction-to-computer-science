# Lesson 2.4: Variables <---- Formerly 3.1 ---->

## Learning Objectives

Students will be able to...

-   Use variables to track values throughout a program

## Materials/Preparation

-   [Do Now 2.4: Debugging](do_now_24.md)
-   Lab 2.4 handout - [Guessing Game](lab_24.md) ([Download in Word](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%202%20Word/Lab%202.4%20Guessing%20Game.docx)) ([Link to PDF](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%202%20PDF/Lab%202.4%20Guessing%20Game.pdf))

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 15 minutes | Lecture and introduce activity                |
| 25 minutes | Activity - Guessing Game                      |
| 10 minutes | Debrief and wrap-up                           |

## Instructor's Notes

---

#### Emphasize with students...

#### Content - Tools to aid in the development process

The most important steps in creating computer programs come before you even start to code. The planning and designing stages are important because they ensure that you carefully consider the program you are going to write, and that you carefully consider the skills and components that you have at your disposal, and the ones that you might need.

In order to help you in the development process, you will be provided with a planning worksheet. You have used one of these before in the course. This planning worksheet is a tool that you can use to help make the development process easier. If you fill in all components of the worksheet, then you will be better prepared to start coding.

---


1.  Lecture

    1.  Review user input, specifically the ![](answer.png) block
        -   Ask students to speculate about how the ![](answer.png) block works
            -   Students should recognize that the block must be storing a value somehow and remembering it for later
        -   Ask students whether that type of functionality might be useful in other cases
    2.  Introduce variables
        -   Define and explain the concept of a variable
            -   _a "place" to store a value for retrieval and use later_
        -   Demonstrate creating, assigning, and accessing a variable in SNAP
            -   Ignore global vs. this sprite only for now
            -   Point out that a variable can only hold one value at a time
                -   When a new value is assigned, the old value is lost and cannot be recovered
            -   Emphasize the importance of descriptive, readable names for variables
        -   Show that variables are independent
            -   One variable's value can be assigned to another, as in ![](setVar1ToVar2.png), but changing the value of `var2` later will not update the value of `var1`

2.  Activity

    -   Briefly demonstrate the ![](random.png) block, which will be used in the lab
    -   Direct students to complete [Guessing Game](lab_24.md) individually or in pairs

3.  Debrief

    -   Discuss and demonstrate one or more students' submissions
    -   Ask students for commentary on usage and naming of variables throughout program

---

#### Emphasize with students...

#### Big Ideas - Tools and technologies can be adapted for specific purposes

In this activity you have created a basic number guessing game, then you created a new one with more advanced features. You can sort of consider this upgraded version as Guessing Game 2.0.

As you developed the upgraded game, you didn't just start with a blank program. Instead, you adapted your code from the first guessing game and altered it to include upgrades.

This is similar to how large companies provide upgrades to their software. They add features to preexisting versions. Occasionally they will start entirely from scratch, when a very important, new version of their software is require. But this is rare and they usually include quite a bit of code that was a part of the original version.

---

## Accommodation/Differentiation

-   Advanced students can be encouraged to implement statistics (best score, average guesses/game, number of time each secret number chosen, etc.)
-   Struggling students can be given code that completes part 1.1, and possibly also part 1.2, to get them started
    -   Students who are particularly overwhelmed should focus only on parts 1.2 and 2.2

## Forum discussion

<a href="http://forums.tealsk12.org/c/intro-unit-2-loops/lesson-2-4-variables" target="_blank">
Lesson 2.4 Variables (TEALS Discourse account required).</a>
