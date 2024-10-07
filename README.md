# Student Database Filter Program

This program reads student data from a binary file (`db.bin` by default) and applies a filter to display information about students based on certain conditions. It processes and prints student information such as their name, surname, course year, average grade, and course details. The code also provides a way to count the students who meet specified criteria.

## Features

- Reads student data from a binary file.
- Displays student details including their names, course year, average grades, and spoken languages.
- Filters students based on conditions:
  - Students with zero courses (modifiable filter).
  - Processes course names and grades for each student.
  - A count of how many students pass all applied filters is printed.

## File Structure

The `Student` structure contains the following information:

- `name`: Student's first name.
- `surname`: Student's last name.
- `course`: The year of study.
- `average`: Average grade of the student.
- `load`: The number of courses the student is enrolled in.
- `courses`: Names of the courses the student is taking.
- `grades`: Grades for the corresponding courses.
- `languages`: Languages spoken by the student.

## How to Run

1. Compile the code using `gcc` (or any C compiler):
   ```bash
   gcc -o student_database student_database.c
