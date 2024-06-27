# Student-management-system-DBMS
This is a DBMS project on student management system for a university under some specific requirements
## README

### Overview

This project demonstrates the creation and manipulation of a comprehensive student information system database using SQLite in Google Colab. The database consists of several interconnected tables, including students, courses, enrollments, professors, accommodations, books, and results, with more than 350 entries in the students table alone. The project encompasses the following key functionalities:

### Database Creation and Data Insertion

1. **Database Schema**: Created tables such as `students`, `courses`, `sqlite_sequence`, `enrollments`, `professors`, `accommodations`, `books`, and `results` with appropriate columns and constraints.
2. **Data Insertion**: Inserted initial data into each table, ensuring a robust dataset for subsequent operations.

### Data Operations

1. **Create Operations**:
   - Added 5 new student records to the `students` table.
   - Added 3 new course entries to the `courses` table.
   - Added 3 new book entries to the `books` table.

2. **Read Operations**:
   - Executed queries to retrieve data under specific conditions.
   - Retrieved details of students enrolled in 2019 and their accommodation details.

3. **Update Operations**:
   - Updated specific entries in the `students` table.
   - Updated specific enrollment entries.

4. **Delete Operations**:
   - Deleted 5 entries from the `students` table.
   - Deleted a course from the `courses` table.

### Data Analysis and Reporting

1. **Number of Students and Gender Ratio by Major**: Calculated using SQL queries.
2. **Comparison of Results in Different Majors**: Analyzed average scores using Pandas.
3. **Relationship Between Student Age and Test Scores**: Explored using Pandas for correlation analysis.
4. **Regional Distribution and Test Scores**: Analyzed regional distribution impacts on test scores.
5. **Additional Analysis**: Conducted further analyses, including correlations between various attributes.

### Visualization and GUI

- Implemented a graphical user interface using Python libraries to visualize table entries and analysis results in different types of charts.

### Database Testing

- **DB Test Code**: Developed and executed test code to verify create, read, update, and delete operations, ensuring all tests passed successfully.
- **Concurrent Query Tests**: Ran multiple queries concurrently to test database performance and integrity.

This project showcases the comprehensive development and manipulation of a student information system database, providing a foundation for further enhancements and applications.
