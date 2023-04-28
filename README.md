1.	Project Demonstration
Description: Use an OOP language of your choice, create an automatic Grading Tool that grades assignments and provides feedback to students. The Grading Tool will store the following data in an online database (e.g., Oracle, Amazon, Google, etc.) of your choice:
1.	Student Name
2.	Feedback
3.	Score

This tool is for use by teachers only, not students. There is no authentication, user permission, or user interface (UI) in the tool. the tool is a console application that can be executed at command line, e.g., Windows' CMD or Mac's Terminal. The tool will make a database connection to store the generated feedback for each student, their names and feedback in several database tables in an online database.

Student code is assumed to have already been downloaded on your localhost computer, and named firstname_lastname.[LANGAGE EXTENSION], where LANGUAGE EXTENSION can be cpp, java, c, py, etc.
•	Example: jane_doe.cpp

Your Grading Tool will open each student's submission file to grade it. In this case, your student is asked to write a simple function, e.g.,
•	C++/Java
o	string print_phone_number();
•	C
o	char* print_phone_number();
•	Python
o	def print_phone_number():
to output their own US-based mobile phone number in string, consisting of:
1.	A 3-digit area code, followed by a dash (-)
2.	A 3-digit number, followed by a dash (-)
3.	A 4-digit number
	
Example of a valid phone number string: 999-333-4444 Your Grading Tool has the following features:
1.	Validate the above referenced phone-number format from each student's output.
2.	Detect plagiarism. Namely, each phone number should be unique. If there are multiple students with the same number, report them (see SAMPLE OUTPUT).
3.	Generate automatic feedback corresponding to one of the following strings:

o	"Good work", if student correctly outputs a valid phone number string. The student receives a score of 1.
o	"Incorrect format", if student has the wrong format. The student receives a score of 0.
o	"Same number used by another student. Plagiarism detected". The student receives a score of –


4.	The Tool will make a database connection to an online database hosted externally (e.g., Google, Amazon, etc.)
5.	The Tool will store each student’s name in a database table called “tblStudents”.
6.	The Tool will store each student’s feedback in a database table called “tblFeedback”.
7.	The Tool will store each student’s score in a database table called “tblScores”.

Assumptions:

1.	There are more than one student submissions to grade.
2.	Every submission is assumed to be 100% compile-able, i.e., there’s no compilation issues.
3.	The tool captures each student's name from the submission file name.
4.	Plagiarism detection is based on string-to-string comparison of two output sources. If two strings are lexically the same, they are considered one copy of another, hence plagiarized.
5.	You must sign up for any free or paid cloud account (Oracle, Google, Amazon, etc.) with database access for this project.
6.	You may design your own database schema for this project.

Submission:
1.	Include any high-level UML design of your application. You may include any class, user activity, or sequence diagrams that illustrate your software design and/or architecture for this tool.
2.	Include any database schema design, if available.
3.	A fully compile-able and working console application (executable) in any language of your choice. Please include test student file(s).
4.	All source code for this application.
5.	You will create the following folder structure by including all the above in them:
o	./src
o	./designs
o	./executable
6.	Compress all the above folders in one zip file and upload the compressed file to your GitHub account
(please sign up for one if you don’t have it).
7.	Provide the GitHub link to the compressed file by 4pm on Friday, April 28, 2023, to me via e-mail.
 
Live Demonstration:

1.	Showcase your solution design via a combination of design diagrams and/or code.
2.	Demonstrate your application from an end-to-end perspective, showing how student files are graded, feedback generated, and data submitted to an online database.
