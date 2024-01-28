# Student Grades Analysis Project

## Overview
This project is designed to demonstrate SQL database skills through the creation of a `student_grades` table. It involves storing and analyzing student grade data, including their name, numeric grade, and the fraction of coursework completed.

## Database Structure
The `student_grades` table includes the following columns:
- `id`: A unique identifier for each student.
- `name`: The student's name.
- `number_grade`: The numeric grade of the student.
- `fraction_completed`: The fraction of the course completed by the student.

## Queries
Two key SQL queries are used in this project:
1. Query to select the name, number grade, and calculate the percentage of coursework completed.
2. Query to determine the letter grade based on the numeric grade and count the number of students in each grade category.

## Example Query Results
### Percentage of Coursework Completed
| Name       | Number Grade | Percent Completed |
|------------|--------------|-------------------|
| Winston    | 90           | 81                |
| ...        | ...          | ...               |

### Letter Grade Distribution
| Letter Grade | Number of Students |
|--------------|--------------------|
| A            | 2                  |
| B            | 3                  |
| ...          | ...                |


