# College-Exam-Seat-Planner
 
College Exam Seat Planner
    
    ~Objective

To develop a web-based application that allocates classrooms for exams using the minimum number of rooms while giving priority to lower-floor classrooms using a greedy allocation approach.

    ~Problem Statement

In colleges, manual seat allocation during exams is time-consuming and may lead to inefficient use of classrooms.
This system automates the process and ensures:

Total capacity is sufficient for all students

Minimum number of classrooms are used

Lower floor classrooms are preferred

    ~Technologies Used

HTML – Page structure

CSS – Colorful and responsive UI design

JavaScript – Logic and greedy algorithm implementation

    ~Data Model

Each classroom contains the following fields:

Field Name	Description
roomId	Unique classroom ID
capacity	Number of seats
floorNo	Floor number
nearWashroom	True / False

Example:
{ roomId: "A101", capacity: 40, floorNo: 1, nearWashroom: true }

    Functional Requirements Implemented
    Add Classroom

User can add classroom details using form:

Room ID

Capacity

Floor Number

Near Washroom option
All fields are mandatory and validation is applied.

     ~View All Classrooms

All classrooms are displayed in a table format.
Each record has a Delete button to remove the entry.

   ~ Allocate Exam Seats

User enters total number of students.
System:

Sorts classrooms by floor number (ascending order)

Selects minimum rooms using greedy method

Stops when total capacity ≥ total students

If capacity is insufficient, system displays:
    Not enough seats available

    ~Algorithm Used — Greedy Algorithm
Steps:

Sort classrooms by floor number

Initialize totalCapacity = 0

Select rooms one by one

Stop when totalCapacity ≥ totalStudents

Why Greedy Algorithm?

Because selecting the lowest floor room first gives priority to lower floors and ensures minimum number of rooms are used.

Time Complexity:

Sorting: O(n log n)
Allocation: O(n)

    ~User Interface Features

Gradient background

Card-based layout

Colorful buttons

Responsive table

Error messages for empty fields

Result display panel

    ~How to Run the Project

Download the file index.html

Open it in any web browser

Add classroom details

Enter total number of students

Click Allocate

No installation or server required.

    ~Future Enhancements

Database integration

Edit classroom feature

Department-wise seat allocation

Washroom priority optimization

Admin login system

~Live Demo
https://illustrious-meringue-9ad722.netlify.app/


 ~Developed By

Mohd Aseem
B.Tech (CSE)


