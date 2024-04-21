# CMS
- This repository contains files for a College/School Management System based on MERN stack
- This web application can perform many tasks such as:
    Admin:
    -  Create/Delete Classes.
    -  Create/Delete Subjects.
    -  Add/Remove students from classes and Subjects.
    -  Post Notices visible to Students and Teachers.
    -  Can add, change and view marks, attendance of Student.
    
    Some notes: Teacher can only be created/assigned if any subject doesn't have a teacher.
    
    Teacher:
    - Can add, change and view marks, attendance of Student.
    
    Student:
    - Can view subjects and marks.
      
To use the Web App, follow the below steps:
A. Go to terminal with the project directory and type 
  cd frontend 
  npm start

  [Starts User interaction based components]
  
B. Open another terminal with the project directory and type 
  cd backend
  npm start
  
  [Starts MongoDB service]

  - Also, replace the MongoDB URL from the .env file to your own MongoDB connection URL.

