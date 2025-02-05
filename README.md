# Database-management-project

Create and use the following student-society database schema for a college to answer the given (sample) queries using the standalone SQL editor.
<br>
Table -> <b>STUDENT</b>
<br>
Roll No (Primary Key) - Char(6), StudentName - Varchar(20), Course - Varchar(10), DOB - Date
<br>
Table -> <b>SOCIETY</b>
<br>
SocID (Primary Key) - Char(6), SocName - Varchar(20), MentorName - Varchar(15), TotalSeats - Unsigned int
<br>
Table -> <b>ENROLLMENT</b>
<br>
Roll No (Foreign Key) - Char(6), SID (Foreign Key) - Char(6), DateOfEnrollment - Date
<br>
QUERIES ->
<br>
1.
Retrieve names of students enrolled in any society.<br>
2.
Retrieve all society names.<br>
3.
Retrieve students' names starting with letter ‘A’.<br>
4.
Retrieve students' details studying in courses ‘computer science’ or ‘chemistry’.<br>
5.
Retrieve students’ names whose roll no either starts with ‘X’ or ‘Z’ and ends with ‘9’<br>
6.
Find society details with more than N TotalSeats where N is to be input by the user<br>
7.
Update society table for mentor name of a specific society<br>
8.
Find society names in which more than five students have enrolled<br>
9.
Find the name of youngest student enrolled in society ‘NSS’<br>
10.
Find the name of most popular society (on the basis of enrolled students)<br>
11.
Find the name of two least popular societies (on the basis of enrolled students)<br>
12.
Find the student names who are not enrolled in any society<br>
13.
Find the student names enrolled in at least two societies<br>
14.
Find society names in which maximum students are enrolled<br>
15.
Find names of all students who have enrolled in any society and society names in which at least one student has enrolled<br>
16.
Find names of students who are enrolled in any of the three societies ‘Debating’, ‘Dancing’ and ‘Sashakt’.<br>
17.
Find society names such that its mentor has a name with ‘Gupta’ in it.<br>
18.
Find the society names in which the number of enrolled students is only 10% of its capacity.<br>
19.
Display the vacant seats for each society.<br>
20.
Increment Total Seats of each society by 10%<br>
21.
Add the enrollment fees paid (‘yes’/’No’) field in the enrollment table.<br>
22.
Update date of enrollment of society id ‘s1’ to ‘2018-01-15’, ‘s2’ to current date and ‘s3’ to ‘2018-01-02’.<br>
23.
Create a view to keep track of society names with the total number of students enrolled in it.<br>
24.
Find student names enrolled in all the societies.<br>
25.
Count the number of societies with more than 5 students enrolled in it<br>
26.
Add column Mobile number in student table with default value ‘9999999999’<br>
27.
Find the total number of students whose age is > 20 years.<br>
28.
Find names of students who are born in 2001 and are enrolled in at least one society.<br>
29.
Count all societies whose name starts with ‘S’ and ends with ‘t’ and at least 5 students are enrolled in the society.<br>
30.
Display the following information:
Society name; Mentor name; Total Capacity; Total Enrolled; Unfilled Seats<br>
