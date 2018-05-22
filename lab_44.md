# 1 - Number Cruncher

In this lab, you will continue practicing processing lists, this time using lists of numbers instead of words.

<table>
<tr> 
<td>  
<strong>Curricular Competencies - Applied Design - Testing</strong></br><br>
Testing is an important stage in design. So far, you’ve probably tested your programs quickly by running them and inputting one or two different types of data. When designing large software applications, programmers create formal testing plans. They indicate different inputs and expected outputs, then they run the program with the input and keep track of the actual output. If the generated output is different than expected then they make changes to the program and log the changes in a test log.</br><br>
For the program below, a test log has been created for you. When you are done each component of the program, test it using the indicated output.
</td>
</tr>
</table>




## Summarizing Numbers

1.  Write a custom SNAP reporter block called "sum" that takes a list as an argument and reports the sum of all the numbers in the list.  You can assume that all items in the list passed as the argument will be numbers, though you should not assume anything else.

2.  Write a custom SNAP reporter block called "average" that takes a list as an argument and reports the average of all the numbers in the list.  As above, you can assume that all items in the list passed as the argument will be numbers, but you should not assume anything else.

3.  Write a custom SNAP predicate block called "includes negative" that takes a list as an argument and reports true if the list contains at least one negative number, and false if all numbers are non-negative.

4.  Write a custom SNAP predicate block called "increasing?" that takes a list of numbers as an argument and reports true if each value in the list is greater than or equal to the one before it.

5.  Write a custom SNAP reporter block called "maximum" that takes a list as an argument and reports the largest number in the list.

## 2 - Transforming Lists

1.  Write a custom SNAP reporter block called "make all positive" that takes a list of numbers as an argument and reports a new list that is the same as the argument, except all negative numbers have been replaced by their absolute value.  

2.  Write a custom SNAP reporter block called "only evens" that takes a list of integers as an argument and reports a new list that contains only the even numbers from the argument list.  The result list should have its values in the same order as the original list, but with the odd integers removed.  (Remember that "mod" block can be useful in determining whether or not a number is even.)

3.  BONUS: Write a custom SNAP reporter block called "add all" that takes two list of numbers as arguments and returns a new list that contains the sum of the corresponding values in each argument list.  For example, if the arguments to "add all" are (1, 4, 6) and (2, 2, 3), the result should be (3, 6, 9).  You can assume the two lists will be the same size.

## Grading Scheme/Rubric

| **Lab 4.4 Criteria**                                   |                 |
| ------------------------------------------------------ | --------------- |
| 1.1 sum reporter                                       | 0.25 points     |
| 1.2 average reporter                                   | 0.25 points     |
| 1.3 includes negative predicate                        | 0.25 points     |
| 1.4 increasing? predicate                              | 0.25 points     |
| 1.5 maximum reporter                                   | 0.25 points     |
| 2.1 make all positive reporter                         | 0.5 points      |
| 2.2 only evens reporter                                | 0.25 points     |
| 2.3 Bonus: add all reporter                            | 0.25 points     |
| **PROJECT TOTAL**                                      | **2.25 points** |
