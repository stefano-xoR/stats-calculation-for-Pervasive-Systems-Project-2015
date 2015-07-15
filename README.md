# stats-calculation-for-Pervasive-Systems-Project-2015
Some of the stats the app will offer to user's has been showed through this android app (a simple interface). All the logic is in the app cloud code on Parse.


What is actually composing the interface:

------------------------------------------------------INPUTFIELDS------------------------------------------------

There are 3 fields  (text fields) to get inputs in particulare:

1)Students: (in this example student is identified just by his name but indeed anything else can be put in this field  depending  on how tables of the db are filled  

2)Class: is the name of class you're lookg info for

3)Professor: indeed is the name of the professor, courses are idintified by a couple professor-lesson

----------------------------------------------------------------------------------------------------------------

----------------------------------------------CALCULATION REQUESTS-----------------------------------------------

You can ask for 4 different statistics, based on which statistic you asked for, only required input fields will be considered.

1) Button: "Student's Average Attendance" using input field: "student", will calculate how many classes the student has followed dividing them by the total number of classes for courses he/she attended giving a percentage of lesson followed

2) Button: "Student's Course Attendance" will calculate using input fields: "student,class,professor", the percentage of lessons followed by the student for the specified course

3) Button: "Course Attendance" using input field: "class", will calculate the percentage of attendance for the given course keeping in count lessons followed by all students who actually attended the course.

4) Button: "Professor Attendance" using input field: "professor", will calculate for every course a professor held, the percentage of student's attendance.

----------------------------------------------------------------------------------------------------------------
