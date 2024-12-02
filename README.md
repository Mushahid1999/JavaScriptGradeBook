# JavaScriptGradeBook
This is a simple JavaScript application designed to help you review JavaScript fundamentals, including functions, variables, conditionals, loops, and more. The Gradebook App calculates class averages, assigns grades based on individual scores, and determines if a student has passed or failed a course.

## Features
* Calculate the average score for a class.
* Assign a letter grade based on a student's score.
* Determine whether a student has passed or failed.
* Display a summary message with the class average, individual grade, and pass/fail status.
## How It Works
### Functions
1. getAverage(scores)
* Takes an array of scores.
* Returns the average score.
2. getGrade(score)
* Takes an individual score.
* Returns a letter grade (A++, A, B, C, D, or F).
3. hasPassingGrade(score)
* Takes an individual score.
* Returns true if the grade is not F; otherwise, returns false.
4. studentMsg(totalScores, studentScore)
* Takes an array of class scores and an individual student's score.
* Returns a message summarizing: The class average, The student's letter grade, and Whether the student passed or failed.
