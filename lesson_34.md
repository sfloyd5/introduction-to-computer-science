<!--- REVISED -->
# Lesson 3.4: Customization II

## Learning Objectives

Students will be able to...

-   Build custom reporter and predicate blocks in SNAP

## Materials/Preparation

-   [Do Now 3.4: Practice using Arguments](do_now_34.md)
-   [Lab 3.4 handout](lab_34.md) (If My Calculations Are Correct...) ([Download in Word](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%203%20Word/Lab%203.4%20If%20My%20Calculations%20Are%20Correct.docx)) ([Link to PDF](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%203%20PDF/Lab%203.4%20If%20My%20Calculations%20Are%20Correct.pdf))

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 10 minutes | Lecture and introduce activity                |
| 25 minutes | Custom reporter activity                      |
| 15 minutes | Debrief and wrap-up                           |

## Instructor's Notes

1.  Lecture
    1.  Introduce reporter blocks
        -   Ask students to find blocks with the reporter shape (round) and speculate as to what they do
            -   Point out familiar examples, such as ![](xposition.png), ![](answer.png), ![](pickrandom.png), etc.
        -   Explain the concept of reporting (returning) a value, and how reporter blocks are used to provide values to commands
        -   Emphasize that reporters do not (and should not) perform any action—they are used to compute values which are in turn used by commands
    2.  Introduce predicate blocks as a special case of reporter blocks
        -   Emphasize that predicates must return true or false
            -   Be aware, but don't necessarily tell students, that SNAP does not enforce this
        -   Point out examples, such as ![](touching.png), ![](lessThan.png), ![](and.png)
        -   Ask students why it might be useful to differentiate predicates from other reporters
            -   Only predicates can be used in a conditional
2.  Activity
    -   Students should complete the ["If My Calculations Are Correct..."](lab_34.md) activity individually.
        -   This lab consists of a series of independent custom blocks.  The blocks need not necessarily be completed in the order given.
        -   Work with students to ensure they are testing their blocks properly and reporting correct values.
        -   Part 2.2 is challenging and requires traversing a String.
3.  Debrief
    -   Ask a different student to provide their solution to each part.  If time permits, go over multiple students' work for each part.
        -   Point out differences and discuss advantages and disadvantages to different approaches.
        -   Emphasize that custom blocks do not have to be long and complicated to be useful.

---

#### Emphasize with students...

#### Content - Pre-built libraries and their documentation

In some programming language there are a number of tasks that already have custom code created for them. In Java for example, there are subroutines called min and max and indexOf that determine the minimum of two numbers, the maximum of two numbers and whether or not a word contains a specific letter.

These subroutines come in packages called libraries. The programmer using these libraries doesn’t have to know the code that exists within each subroutine. Instead the programmer just needs to know how to use the subroutine (what information needs to be sent to the subroutine and what information will be returned). Libraries usually have documentation that explain how to use the different subroutines.

---

## Accommodations/Differentiation

-   Struggling students should focus on just the first 2 or 3 parts of the lab.  Even if they cannot move on to the more difficult problems, getting used to defining custom reporters is helpful and important.
-   Advanced students who finish quickly can be utilized to assist other students.
-   Students who struggle in math may not be familiar with the distance formula used in part 2.1.  Help students to translate the math into SNAP code, but understanding the formula and its applications is not necessary for the activity.
    -   If most students are not equipped to handle this math, a simpler computation, such as area of a triangle or average of three numbers, can be substituted.


## Forum discussion

<a href="http://forums.tealsk12.org/c/intro-unit-3-variables-and-customization/lesson-3-4-customization-ii" target="_blank">
Lesson 3.4: Customization II (TEALS Discourse account required).</a>
