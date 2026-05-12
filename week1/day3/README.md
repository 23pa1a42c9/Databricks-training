Query Explanations
1. Display all students and the courses they are enrolled in
Concept Used
LEFT JOIN
Purpose

Shows all students including students who are not enrolled in any course.

2. Find all courses that currently have no students enrolled
Concept Used
LEFT JOIN
NULL checking
Purpose

Identifies courses without enrollments.

3. Display all instructors and the courses they teach
Concept Used
LEFT JOIN
Purpose

Shows all instructors including instructors who are not assigned to any course.

4. Find all courses without an instructor assigned
Concept Used
LEFT JOIN
NULL condition
Purpose

Displays courses that do not have assigned instructors.

5. Display all students and enrollment information using RIGHT JOIN
Concept Used
RIGHT JOIN
Purpose

Shows all students with available enrollment details.

6. Find students who are not enrolled in any course
Concept Used
LEFT JOIN
NULL filtering
Purpose

Displays students without enrollments.

7. FULL OUTER JOIN example for students and enrollments
Concept Used
FULL OUTER JOIN
Purpose

Displays matched and unmatched rows from both tables.

8. Find all courses never used in enrollments
Concept Used
LEFT JOIN
Purpose

Displays courses that never appeared in the enrollments table.

9. FULL OUTER JOIN between instructors and courses
Concept Used
FULL OUTER JOIN
Purpose

Displays all instructors and courses including unmatched records.

10. Student, course, and instructor report
Concept Used
Multiple LEFT JOINs
Purpose

Generates a report containing:

Student name
Course name
Instructor name

Includes rows even if some information is missing.

11. Display every student and every course
Concept Used
CROSS JOIN
Purpose

Creates all possible combinations of students and courses.

SQL JOIN Types Summary
JOIN Type	Purpose
INNER JOIN	Returns matching rows from both tables
LEFT JOIN	Returns all rows from left table
RIGHT JOIN	Returns all rows from right table
FULL OUTER JOIN	Returns all rows from both tables
CROSS JOIN	Returns all combinations
