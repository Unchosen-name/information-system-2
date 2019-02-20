# information-system-2

This is an information system/database of the paths chosen by past graduates from my high school, A.Y.Jackson. The purpose of
this database is to provide grade 11 and 12 students of A.Y.Jackson a more comprehensive view of the universities and their 
programs. Userswill be able to look at past students who was admitted by a specific program and estimate their chances of
getting in. This project is inspired by the short period of cluelessness I experience during my time of university application. 
The information system will give the students a more accurate standard by comparing them to their seniors, since universities
treat different high schools slightly differently. 

-------------------------------------------------------------------------------------------------------------------------------

Users:
There are three types of users: guest, students, and admins,

Guest users are users who do not attend AY, for example, a student's parents. They have limited access to the data of the past
graduates and the trend-analysis functions of the system. This is to prevent the data from leaking outwards to people who
do not deserve the data. The guest users do not need a username or password to access the system. They will all have the name
"Guest".

Student users are current students enrolled in AY. They have access to all the data of the graduates and all the trend-analysis
functions built into the system. To use the system, the students require an account, which is composed of their name, student
number, and their Ontario Education Number(OEN). If the newly reregistered account have duplication in the student number and 
OEN fields, an error message will appear and the account will not be successfully registered.

Admin users are current teachers working in AY. They have the access to add and remove entries in the database, as well as the
authority to add or remove certain student users. They can also browse the graduate database and use the trend-analysis
functions. The admin account composes of a teacher's name and teacher number. If a newly reregistered account have duplication
in the student number and OEN fields, an error message will appear and the account will not be successfully registered. 

-------------------------------------------------------------------------------------------------------------------------------

Functionality:
All users can browse through the graduate database. Each entry in the graduate database indicates a past graduate of AY.
The entry consists of: year of graduation, top six courses, application average, name(only visible to admins), and program.
The year of graduation contributes in predicting the trend of acceptance average for that specific program. The top six courses
will help the users to determine the most wanted courses the program is looking for. The application average can give the users
a good comparison between themselves and the admitted students, and see how far they are from a competitive average. 

Trend analysis are available to students and teachers. The methods will go through the data of one specific program and output 
a trends like "predicted competitive average of next year". 

Browse function allows students to search for desired results in the database. A variety of categories are available, including
program, average, courses, etc. 

QNA page exists to answer questions that might be asked by the users. When called, the QNA page will give a list of frequently
asked questions and their corresponding answers. The users can also choose to ask a question, which will be answered by an 
admin as soon as possible. 

