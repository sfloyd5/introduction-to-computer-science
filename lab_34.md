<!--- REVISED -->
# Lab 3.4 - If My Calculations Are Correct...

In this lab, you will write custom reporter blocks to perform a number of useful calculations and computations.

---

#### Content - Pre-built libraries and their documentation

In some programming language there are a number of tasks that already have custom code created for them. In Java for example, there are subroutines called min and max and indexOf that determine the minimum of two numbers, the maximum of two numbers and whether or not a word contains a specific letter.

These subroutines come in packages called libraries. The programmer using these libraries doesn’t have to know the code that exists within each subroutine. Instead the programmer just needs to know how to use the subroutine (what information needs to be sent to the subroutine and what information will be returned). Libraries usually have documentation that explain how to use the different subroutines.

---

## 1 - Simple Computations

1.  Write a custom SNAP reporter block called "min" that determines which of two numbers is smaller and reports that value.  If the two numbers are equal, report either one.

2.  Write a custom SNAP reporter block called "max" that determines which of two numbers is larger and reports that value.  If the two numbers are equal, report either one.

3.  Write a custom SNAP predicate block called "between" that determines if a number is between two other numbers.  If the first number is equal to either of the other two numbers or is between them, the block should report "true".

4.  Write a custom SNAP predicate called "at least as long as" that determines whether or not word has at least a specified number of letters.

## 2 - Stepping Things Up

1.  Write a custom SNAP reporter block called "distance to" that computes and reports the distance from a sprite's position to another point.  Use the "x position" and "y position" blocks to determine the sprite's position.  Remember that the formula for the distance between points (x1, y1) and (x2, y2) is sqrt((y2-y1)^2+(x2-x1)^2).

2.  Write a custom SNAP predicate block called "contains letter" that determines whether or not a word contains a particular letter.  You can consider upper-case and lower-case letters to be different for the purposes of matching.

## Grading Scheme/Rubric

| **Lab 3.4 Criteria**            |                |
| ------------------------------- | -------------- |
| 1.1 min                         | 0.25 points    |
| 1.2 max                         | 0.25 points    |
| 1.3 between                     | 0.5 points     |
| 1.4 at least as long as         | 0.5 points     |
| 2.1 distance to                 | 0.5 points     |
| 2.2 contains letter             | 0.5 points     |
| **PROJECT TOTAL**           | **2.5 points** |

