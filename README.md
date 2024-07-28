# Contest-Management-System

This project is a Database Management System (DBMS) designed to manage and organize coding contests, similar to platforms like Codeforces. The system stores information about users, contests, problems, submissions, authors, and more. Below is an overview of the project's ER diagram and relational schema.

Features:

- User Management: Store user details such as name, email, city, country, rating, and institute/company.

- Contest Management: Organize contests with details like contest name, division, duration, participation, and date.

- Problem Management: Manage problems with attributes such as description, difficulty level, time constraint, and memory constraint.

- Submission Tracking: Track submissions with details like submission time, language, score, and verdict.

- Author Contributions: Track contributions of authors.

- Problem Tags: Categorize problems with tags.

- Participation Records: Record user participation in contests.

- Problem Assignments: Assign problems to contests.

ER Diagram

- The ER Diagram visually represents the relationships between the different entities in the system. The main entities are User, Contest, Problem, Submission, Author, Problem Type, and the relationships between them like User Participation, Written By, and Contest Problems.


Relational Schema

- The relational schema defines the tables and the relationships between them in the database. Each relation is in BCNF (Boyce-Codd Normal Form), ensuring minimal redundancy and dependency.

- Each relation is proven to be in BCNF with its minimal FD set provided in the project documentation.

Conclusion

- This DBMS project provides a comprehensive system for managing coding contests, ensuring efficient organization and tracking of all related data. The ER diagram and relational schema facilitate a clear understanding of the system's structure and data flow.

For further details, refer to the ER Diagram and the complete Relational Schema.
