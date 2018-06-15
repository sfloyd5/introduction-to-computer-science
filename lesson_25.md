<!--- REVISED -->
# Lesson 2.5: Boole in the House

## Learning Objectives

Students will be able to...

-   Define and identify Boolean expressions and operators
-   Evaluate Boolean expressions
-   Utilize Boolean operators (and/or/not) to create compound conditions

## Materials/Preparation

-   [Do Now 2.5: Variables Practice](do_now_25.md)
-   [Lab 2.5 handout (Triangles of All Kinds)](lab_25.md) ([Download in Word](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%202%20Word/Lab%202.5%20Triangles%20of%20All%20Kinds.docx)) ([Link to PDF](https://tealsk12.gitbooks.io/introduction-to-computer-science/content/Unit%202%20PDF/Lab%202.5%20Triangles%20of%20All%20Kinds.pdf))

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 20 minutes | Review and lecture                            |
| 20 minutes | Triangles activity                            |
| 10 minutes | Debrief and wrap-up                           |

## Instructor's Notes

---

#### Emphasize with students...

#### Big Ideas - Personal design interests require the evaluation and refinement of skills

As you start to create more interesting programs, and as you eventually start to create programs of your own design, you will have to start evaluating and refining your skills. In this lab you are asked to use Boolean operators in your program as a way of adding logic and decision making to your software. Think carefully about whether or not you know enough about Boolean operators and how to implement them in SNAP. If you don’t review the lesson on Boolean operators or ask for help from your teacher or classmate.

It's important to always evaluate and refine the skills needed in your projects so that you can create some great stuff!

---

1.  Review
    -   Remind students about conditional statements, and ask what the blocks that can go in the holes in if blocks have in common
        -   Blocks are "pointy" and all  are "yes/no" or "true/false" questions
2.  Lecture
    -   Introduce and define "Boolean expressions" as expressions that evaluate to true or false
        -   If desired, explain that the term "Boolean" is derived from [George Boole](https://en.wikipedia.org/wiki/George_Boole)
        -   In SNAP, all Boolean expressions are pointy six-sided blocks
    -   Present the three Boolean operators: and, or and not
        -   Define the operators and describe when each will return true
        -   Show the truth tables for each operator and explain how to read them (see below for trueth table example)
            -   Truth tables are simply one way of expressing how the Boolean operators work; if students are struggling, other depictions (such as an exhaustive list of all possible results) can be substituted
        -   Emphasize that since Boolean operators are themselves Boolean expressions, they can be nested
        -   Practice evaluating Boolean expressions, starting simple and moving to more complex nested operations
            -   Start with simple expressions: e.g. `5 < 7 AND 4 > 2`
            -   Introduce variables: e.g. `x = 7; x < 5 OR x > 10`
            -   Nest operations: e.g. `(x = 4; y = -3; x == y OR (x > 0 AND y < 0))`
        -   Discuss short-circuiting in evaluation of Boolean expressions
    -   Discuss situations in which the Boolean operators might be needed
        -   The lack of <= and >= operators in SNAP makes for a great example
3.  Activity
    -   Students should complete the ["Triangles of All Kinds"](lab_25.md) activity individually or in pairs
        -   A number of geometric concepts (Triangle Inequality Theorem, Pythagorean Theorem, etc.) are used in this lab, but students need not have a deep understanding of them.  The necessary points are explained in the lab.
        -   Encourage students to think about whether an "and" or an "or" is appropriate in each case.  Draw out truth tables if necessary.
4.  Debrief
    -   Walk through a student's response
        -   Point out uses of Boolean operators
        -   Discuss how nested or chained if blocks could potentially be used to obtain the same behavior, but would result in longer, less-readable code

## Logical AND truth table

|   p   |   q   | p and q |
| ----- | ------| ------- |
| true  | true  | true    |
| true  | false | false   |
| false | true  | false   |
| false | false | false   |

## Logical OR truth table

|   p   |   q   | p or q |
| ----- | ------| ------ |
| true  | true  | true   |
| true  | false | true   |
| false | true  | true   |
| false | false | false  |

## Logical NOT truth table

|   p   | not p |
| ----- | ------|
| true  | false |
| false | true  |


## BJC Lecture Suggestions
####Good for Classroom Instruction
 * BJC Video Suggestion: [BJC Lecture 2: 3D Graphics](http://www.youtube.com/watch?v=hdSFuhyGTIg&t=5m50s)
  - [Modelling](http://www.youtube.com/watch?v=hdSFuhyGTIg&t=5m50s) 5:50-10:57

## Accommodations/Differentiation

-   Students that have not taken Geometry made be intimidated by some of the concepts in the lab.  Deep understanding of the theorems is not necessary; encourage the students to simply focus on the equations and inequalities presented.
    -   If the students continue to struggle, help them build the necessary expressions, but encourage them to assemble them into the full condition on their own.
-   Advanced students, especially those who have taken higher levels of math, can be encouraged to add additional functionality, such as using [Heron's formula](https://en.wikipedia.org/wiki/Heron%27s_formula) to calculate the triangles area or using trigonometry to attempt to draw the triangle.
    -   Drawing the triangle is very challenging.

## Forum discussion

<a href="http://forums.tealsk12.org/c/intro-unit-2-loops/lesson-2-5-boole-in-the-house" target="_blank">
Lesson 2.5 Boole in the House (TEALS Discourse account required).</a>
