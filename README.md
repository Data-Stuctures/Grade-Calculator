# Grade-Calculator

Description: The propose of this Lab, was to create grade calculator, that would calculate the total grade received and the total desired grade of the Cisc-3130 class using data structures.

Instruction: The way we obtain this information goes as following:

The approach that i have chosen to complete this lab was the object-oriented approach for each component is a separate object of the grade. The type of data stucture i have chosen was arraylists i found it the easiest way to go about this lab. Therefore, we need write 7 different classes: Grade, Total Grade, FinalExam, Midterms,Labs, Practice Problems, and Course Grade.

The Grade class gets all the grades of each compont therefore, it would be the first class and consider to be the parent class. This class consists of 3 methods setScore, getScore, and getGrade. The SetScore class sets the numerical value of the grade. The getScore method returns the numerical value of the grade. The getGrade method returns the letter grade of the total grade after retrieving the total numerical grades.

Then we can write the remaining children class: Total Grade, FinalExam, Midterms,Labs, Practice Problems, and Labs. All the Children class have the same functions the only difference is that each class may vary in the grade points and the amount of input required by each component. For example: There are 7 labs for this class and maximum points received is about 2 points each lab. For practice problems there are 8 in total and each weighing about 6 points each. However, all the children class essentially perform the same goal, asks the user to insert their score for each individual tasks, sums the all the individual scores and setting it in the super class. Therefore, we can generalize all the methods in these children class. For each of these classes there is set method; to set individual grade, there is sum method that sums all the individual grade stored in the arraylist, currentGrade that asks the user to insert each of received grade of each task, and the potentialGrade which asks the user to enter their desired potential grade. Each Class has a separate output file recording the information.


The Last step is the CourseGrade class that uses an Array of Grade object of the grade class that stores each component at each index inside the array. Therefore, will have set method for each component stored at a sperate index of the Grade object array. Another, method would need is to calculate what’s the remanding points from our current grade. After that’s all set we implement all the methods in main method and store it a separate text file name "TotalGrade.txt".
