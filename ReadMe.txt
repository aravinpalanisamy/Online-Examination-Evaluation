ONLINE EXAMINATION EVALUATION ---

ALGORITHM :

Step 1: Assign current httpcontext to a variable.
Step 2: Change the server path of the context to a folder that is created within the solution.
Step 3: Initialize MultipartFormDataStreamProvider.
Step 4: Foreach file in Data Stream Provider get the filename.
Step 5: Trim the present in filename.
Step 6: Now combine the server path and filename into a path using Path.Combine(serverpath,filename).
Step 7: Move file to required path when uploaded.
Step 8: End for Step 9: Declare a model "question details" consisting the question number and difficulty of the question as properties.
Step 10: Get the data present in file into StreamReader.
Step 12: Now read the text line by line until it reaches end of page.
Step 11: initialize question number to 0 
Step 13: Search for ? in the line and once it was recognized split line into 2 words and assign it to string
Step 14: Increment the question number always until ? is identified.
Step 15: Now assign the question number and second word(string[1]) in the array to the question details object that was initialized.
Step 16: Now push the object to the list of object List<questiondetails>
Step 17: EndFor 
Step 18: Return the List<questiondetails> which contains the difficulty level of question along with the question number.

EXPLANATION :
PROBLEM STATEMENT :

Derive an algorithm to find difficulty of a question given the following details
1) Question type -- MCQ, Fillup, Programming, Match the following
2) Manually assigned difficulty -- Easy, Medium, Hard
3) Total number of students who have attended this question
    a) Time taken by each student to answer this question
    b) Number of times the answer was changed if it is MCQ type question
    c) Number of times the program was compiled if it is programming question
    d) Number of hints used
    e) Programming language used if it is programming question (c, c++ , java etc)
4) Feedback given for this question by other students
5) Total number of students who have answered it right
6) Total number of students who have answered it wrong
7) Total number of students who have answered it partially correct
8) Maximum marks allocated for this question

ONLINE EXAMINATION SYSTEM FEATURES :

1.Login system must be present and secured by password.
2.Ability to setup multiple choice question paper.
3.Display of quick and accurate results.
4.Rankings , and history of exams attempted can be looked after.
5.Admin panel
	Can add/remove the teachers.
	Can view the feedbacks.
6.Teacher panel
	Can add/remove question papers.
	Can view the individual test results and overall rankings.
7.Student panel
	Can write the exams shown in home page
	Only once a student can attempt the examination , after then the examination is disabled until the teacher removes it.
	Can view the overall ranking and the details of scores and examinations previously attempted.
8.Log out after the over.
9.Users can send the suggestions and feedbacks from the home page , it can be viewed by admin.
What makes our online exam system web project differs from others :
Low internet connection would be sufficient to load the pages, since we haven’t used any picture data(using pictures the user with low internet connection takes time to load the images). In other online exam system websites , we can find only one admin who is surely responsible for the addition or deletion of the test, but we made this site any number of authorized persons can add/remove the examinations and these all authorized persons and users of this site will be controlled by the admin. It could be very helpful for educational institues acting as :
	Admin(headdash.php) --- director of institute
	Teacher(dash.php) --- professors of college
	User(acccount.php) --- students of the college
	home page (index.php) Security with password , even the admin cannot look at the password , ensuring the trust of the users. A feedback system available for suggesting improvements and registering complaints.

My Difficulties :

I have partially done my project on examination evaluation portal.
Where the output get from the project was about the difficulty of the questions where it given from input.
I am not familiar with web and app development.
In this project,I am done with a Visual Studio app which has a API development.
It was new for me, so I have more time to develop the full project.
And I am not sure the project was completed.
This project can use a one more application called POSTMAN Application.
And I develop with C Sharp i.e. C# , HTML and CSS.
