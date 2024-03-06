# MongoDB Task Management System

This is a MongoDB database design for a task management system that includes collections for users, attendance, tasks, codekata, placement drives, mentors, topics, and tasks.

## Collections

1. **Users Collection**
   - Stores information about users including students and mentors.
   - Fields: id, name, email, role, registration_date, last_login.

2. **Attendance Collection**
   - Tracks user attendance with fields such as user_id, date, and status.

3. **Tasks Collection**
   - Contains information about tasks assigned to users.
   - Fields: user_id, description, deadline, submitted.

4. **Codekata Collection**
   - Stores data related to users' Codekata performance.
   - Fields: user_id, problems_solved, problems_unsolved, codekata_score.

5. **Topics Collection**
   - Includes information about topics taught.
   - Fields: name, description, month, date.

6. **Placement Drives Collection**
   - Manages information about placement drives.
   - Fields: company_name, date, appeared_students.

7. **Mentors Collection**
   - Contains details about mentors and their mentee count.
   - Fields: user_id, specialization, mentee_count.

## Practice_Queries

- **1. Find all the topics and tasks which are thought in the month of October**
- **2. Find all the company drives which appeared between 15 oct-2020 and 31-oct-2020**
- **3. Find all the company drives and students who are appeared for the placement**
- **4. Find the number of problems solved by the user in codekata**
- **5. Find all the mentors with who has the mentee's count more than 15**
- **6. Find the number of users who are absent and task is not submitted  between 15 oct-2020 and 31-oct-2020**


  
## How to Use

1. **Import Collections**
   - Import the provided MongoDB collections into your MongoDB database.

2. **Run Queries**
   - Execute MongoDB queries to retrieve relevant information based on your requirements.

3. **Adjust Schema**
   - Customize the collections and fields according to your application's schema.


