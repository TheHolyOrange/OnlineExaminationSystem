# ExamEase Online Examinations System

The goal of this system is to develop a comprehensive and interactive online examination platform that supports both students and teachers. The application should allow an admin to set up a repository of multiple-choice questions (MCQs) with options and answers. Teachers will create exams from the question repository and provide keywords for each question to track 
students’ strengths and weaknesses in different subjects or topics. Students will be able to take the exams with a timer, view their results, and receive topic-specific feedback. The system will generate a rank list to display performance and provide insights into areas where students need 
improvement. 

## Features
- ### Authorization
    - Sign-Up
    - Login
    - Forgot Password
- ### Teacher Dashboard
    - Create Exam
    - Create Mock Exam
    - View Student Results
    - View Topic Wise accuracy
- ### Student Dashboard
    - Take Exam
    - Take Mock Exam
    - View past performance
    - View Topic-wise performance


## Tech

- Programming Language: Java language. 
- Data Storage: CSV files for user details, questions, exams, and results stored in AWS cloud using S3 bucket. 
- Front-End: Java Swing for the user interface, with separate dashboards for teachers and students. 

## Execution
Navigate to the folder having the mavenexam.jar file. Then give the following command in the terminal or double click on the mavenexam.jar file.

```sh
java -jar mavenexam.jar
```

