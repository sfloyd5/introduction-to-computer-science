<!--- REVISED -->
# Lab 4.3 - Guess Who

In this lab, you will create a list of names and then look through the list pulling out different subsets of the names.  (Adapted from Jeff Tyson: <http://tealsclass.com/mod/assign/view.php?id=13490> and <http://tealsclass.com/mod/assign/view.php?id=13489>) 

## 1 - Role Call

1.  Create a list of names with at least six different names.  Try to vary the names as much as you can.

2.  Write a SNAP script to welcome each person to the program by name, one at a time.  (For example, "Welcome, John."  "Welcome, Mary."  "Welcome, Scott.")  Make sure not to modify the list of names when you run the script—you'll want the list again later.  Also make sure your script still works even if the list of names changes.

3.  Write a new SNAP script that welcomes all the players at once.  So, for example instead of saying "Welcome, John," "Welcome, Mary," and "Welcome, Scott." separately, you're new script should say "Welcome John, Mary, and Scott."  Start by writing a script that can say all the names on one line, then try to add the commas and "and".  Make sure your script works correctly no matter how many names are in the list.

4.  BONUS: Modify your code so that instead of using a pre-determined list of names, the user can enter the names to be included in the list one at a time.  You'll need to decide how to determine when the user has entered all the names.

<table>
<tr> 
<td>  
<strong>Content - Structures within existing code</strong></br><br>
As you’ve done a number of times in this course, you’ll be altering the structures within your existing code in order to create new capabilities for the program. This is an important way to program. Rarely do programmers write code for their entire program and then click run.</br><br>
Instead they design in small stages, accomplishing smaller subtasks and building upon these structures in order to add complexity. So as you create more programs and as you design your own, begin by creating simpler versions  and then add layers of complexity as you get each stage to run.
</td>
</tr>
</table>






## 2 - I'm Looking For...

1.  Write a script that says every other name in a list one at a time when the space bar is pressed.  Use the same list of names from above.  For example, if the list is [Eric, Sally, Michelle, John, Sam, Caleb], the names Eric, Michelle, and Sam would be said.

2.  Write a script that says the names in the list one at a time in reverse order when the '0' key is pressed.  For example, if the list is [Eric, Sally, Michelle, John, Sam, Caleb], the names Caleb, Sam, John, Michelle, Sally, and Eric would be said.

3.  Write scripts so that when each of the following keys is pressed, the corresponding subset of names from the list is said one at a time.

| When this key is pressed... | Say the names in the list that...                   | For example...        |
| --------------------------- | --------------------------------------------------- | --------------------- |
| 1                           | Have more than four letters                         | Sally, Michelle       |
| 2                           | Start with the letter 'c'                           | Caleb                 |
| 3                           | End with the letter 'y'                             | Sally                 |
| 4                           | Are not the first two or last two names in the list | Michelle, John        |
| 5 (optional)                | Contain the letter 'e'                              | Eric, Michelle, Caleb |

## Grading Scheme/Rubric

| **Lab 4.3 Criteria**                                   |                |
| ------------------------------------------------------ | -------------- |
| 1.2 Welcome by name                                    | 0.25 points    |
| 1.3 Welcome all at once                                | 0.25 points    |
| 1.4 Bonus: Enter list, then welcome all at once        | 0.25 points    |
| 2.1 Every other name                                   | 0.25 points    |
| 2.2 Reverse order                                      | 0.5 points     |
| 2.3.1 > 4 letters                                      | 0.25 points    |
| 2.3.2 start with C                                     | 0.5 points     |
| 2.3.3 End with y                                       | 0.5 points     |
| 2.3.4 Not first 2 or last 2                            | 0.5 points     |
| 2.3.5 Bonus: Contain e or E                            | 0.25 points    |
| **PROJECT TOTAL**                                      | **3.5 points** |
