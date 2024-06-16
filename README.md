# School-Result-Management-system-in-python
School Management System is designed to automate various administrative tasks of a school. The appl provides functionalities for both teachers and students, allowing them to manage and access academic information like logging in as a teacher or student, viewing results, searching for roll numbers, and entering student information.


Key Features
Main Menu:

Teacher Login
Student Login
Exit

Teacher Console:

Get Result: View a student’s results by entering their roll number.
Search Roll No: Find a student's roll number using their name.
Enter Student Info: Add new student information, including name and marks.
Exit: Log out and return to the main menu.


Student Console:

Get Result: View their results by entering their roll number.
Search Roll No: Find their roll number using their name.
Exit: Log out and return to the main menu.

Implementation

Data Storage:

student_db: Stores student details (name, English marks, Math marks).
teacher_db: Stores teacher login credentials.


User Interface:

The system uses a text-based interface where users input numeric choices and provide details when prompted.


Core Functions:

print_header(): Displays headers with the school name.
user_input(): Handles user input with retries and error messages.
first_screen(): Displays the main menu and gets user choice.
verify_cred(): Authenticates teacher credentials.
teacher_console(): Displays teacher options and gets user choice.
get_rollno(): Generates a new roll number.
enter_stud_info(): Allows entry of new student details.
get_result(): Displays student results, including rank.
student_login(): Displays student options and gets user choice.
search_rollno(): Finds roll number by student name.
get_rank(): Calculates and returns student rank based on total marks.
main(): Manages the overall application flow.

Rank Calculation:
The rank is determined by comparing total marks (English + Math) against all students.

Error Handling:
The system manages invalid inputs and limits retries, ensuring a smooth user experience with clear error messages.
The School Management System provides an effective way to handle academic data, facilitating easier administrative work for teachers and accessible information for students.
