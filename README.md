Download Link: https://assignmentchef.com/product/solved-c-program-to-allow-processing-of-exam-grades-for-students-in-a-course
<br>
You will design and implement a menu-based program using C++ programming language to allow processing of exam grades for students in a course.

<h1><strong> </strong>The Main Menu</h1>

Your program will start by showing a main menu to the user. The menu will have the following parts

<ol>

 <li>Input a student grade</li>

 <li>Display all grades</li>

 <li>Display a Student’s exam statistics</li>

 <li>Display an Exam’s statistics</li>

 <li>Exit</li>

</ol>

Your program will ask the user to make a choice from the menu and accordingly complete the requested ask and go back to the main menu. The program will terminate only when the user chooses the ‘Exit’ option<em> in the main menu. </em>Make sure to add <strong>Input Validation</strong> to your program, so that the user is asked to enter a menu choice until the entered choice is valid. For example, if the user enters an invalid choice such as 0, 5, or -1, … etc. the user will be asked to enter the menu choice again. Hint: You need to write a loop to ask the user’s menu choice.

Choice: Input a Student’s Grades

When the user selects this choice, the program will ask the user to enter the four pieces of information:




<ul>

 <li>Student ID: should be a number between 1-9999</li>

 <li>Exam 1 grade: should be a number between 0-100</li>

 <li>Exam 2 grade: should be a number between 0-100</li>

 <li>Exam 3 grade: should be a number between 0-100</li>

</ul>




Make sure to add <strong>Input Validation</strong> to your program, so valid range of numbers are entered for each of Student ID and Exam,1, 2, and 3 grade (Hint: You need a loop when asking each piece of information).

After the user enters all the information for<em> a single student</em>, the program will record the data to a text file (you can name your text file as “grades.txt”). Each line of the text file will have information about a single student as below

StudentID     Exam1Grade    Exam2Grade    Exam3Grade

Once the student is added (hint: you need to <u>append</u>) to the text file, your program will go back to the main menu (that is show the main menu to the user again to allow the user make another choice from the main menu).

<h2>Choice: Display all grades</h2>

When the user selects this option,  your program will open the text file and read all of the data (all the studentIDs, and exam grades) and display it in a nicely formatted manner on the screen. Make sure

<ul>

 <li>to show column headers and</li>

 <li>align the columns on the screen.</li>

</ul>




You can use system(“cls”) to clear the screen before showing the data on the screen. Your program then should pause to allow the user view the displayed data (hint: you can use system(“pause”) or cin.get() function calls).




Finally, your program needs to go back to the main menu (that is show the main menu to the user again to allow the user make another choice from the main menu).

<h2>Choice: Display a Student’s Exam statistics</h2>




When the user selects this option, you will ask the user to enter the studentID. Then you will open the text file and search for this ID.

<ul>

 <li>If you cannot find the entered ID in the text file, displaying a message “The student ID and record cannot be found”</li>

 <li>If the ID is found in the text file, then show the Exam1, 2, 3 grades for the student and also the average of the three exam grades</li>

</ul>

You can use system(“cls”) to clear the screen before showing the data on the screen. Your program then should pause to allow the user view the displayed data (hint: you can use system(“pause”) or cin.get() function calls).




Finally, your program needs to go back to the main menu (that is show the main menu to the user again to allow the user make another choice from the main menu).

<h2>Choice: Display an Exam’s statistics</h2>




When the user selects this option, you will ask the user to enter an <strong>exam number</strong> and then show the following statistics for the requested exam. Make sure to make <strong>Input Validation</strong> as the user can only enter 1, 2, 3 as exam number. (Hint: You need to use a loop when asking the exam number from the user).

<ul>

 <li>Number of students who took the exam</li>

 <li>Exam Average</li>

 <li>Min grade</li>

 <li>Max Grade</li>

 <li>Standard Deviation standard deviation in this link <u><a href="https://www.mathsisfun.com/data/standard-deviation-formulas.html">https://www.mathsisfun.com/data/standard-deviation-formulas.html</a></u></li>

 <li>Grade Distribution you will count and display how many students for a grade between 90-100, 80-89, 70-79, … 0-9.</li>

</ul>

You can use system(“cls”) to clear the screen before showing the data on the screen. Your program then should pause to allow the user view the displayed data (hint: you can use system(“pause”) or cin.get() function calls).




Finally, your program needs to go back to the main menu (that is show the main menu to the user again to allow the user make another choice from the main menu).

<h1>Requirements</h1>

<ul>

 <li><strong>code should be Modular Program using functions </strong></li>

</ul>

For each sub task, such as getting an input from the user, calculating a particular value, showing the menu etc. you should write a function.

<ul>

 <li>One or more <strong>void</strong> functions</li>

 <li>One or more <strong>value returning</strong> functions</li>

 <li>One or more functions with <strong>value parameters</strong></li>

 <li>One or more functions with <strong>reference parameters</strong></li>

</ul>

Do <em>not</em> use any global variables<em>, </em>but using global CONSTANTS are allowed <strong>(2 pts) Use Comments:</strong> Use appropriately for each function, and variable names, or functionality of your code.

<ul>

 <li><strong>Choose Appropriate Names for your identifiers (variables, constants, and functions): </strong>Choose appropriately long and explanatory names.</li>

</ul>


